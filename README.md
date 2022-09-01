# ME 701 -- Homework 1 -- Your Name Here

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution
During ME 400 I coded daily using VSCode. 
The source code for VSCode is availible under the MIT License and is therefore open source, 
but the binary code you donwnload from microsoft is not.
the code reports telemetry, tracks usage, errors, and provides information for future updates to the IDE.
I am not always the happiest with "Big Brother" looking over my shoulder so I looked into an fully open source alternative.
I found one called VSCodium which is pretty identical and has compatability with the microsoft version but does not send out telemetry.


Write your solution here.  Note, in the past, we've used a full, graphical
version of Linux.  With WSL, you probably don't have as direct a path for
exploring software in the Software Manager.  However, use the power of
Google (or AskJeeves) to explore what sorts of open-source software is out
there for technical or other applications.


## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information, I used the following:
```bash
Command:
       lscpu | egrep 'Model name|Socket|Thread|NUMA|CPU\(s\)
Output:
       (base) scoofdaddy@DESKTOP-IPC2HNA:/mnt/c/WINDOWS/system32$ lscpu | egrep 'Model name|Socket|Thread|NUMA|CPU\(s\)'
       CPU(s):                          8
       On-line CPU(s) list:             0-7
       Model name:                      Intel(R) Core(TM) i7-8550U CPU @ 1.80GHz
       Thread(s) per core:              2
       Socket(s):                       1
       (base) scoofdaddy@DESKTOP-IPC2HNA:/mnt/c/WINDOWS/system32$
```

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution



## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution
