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

Krita is an open-source software I used to use for image editing and digital drawing before I started using
a paid software. It possesses similar basic features compared to paid software like Photoshop and Paint Tool SAI,
and actually has some features unique to it like multiple built-in engines for brushes (although Photoshop and SAI
have features unique to them as well). Being open-source, it also supports add-ins in the form of Python plug-ins.
One such plugin I looked allows for the execution of bash commands and programs on currently open images in Krita.

## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information, I used the following command:

lscpu			# <-- Using this command displays info such as the CPU's model, MHz, and # of threads and cores.

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution

ps aux			# <-- CPU usage is under "%CPU", while Memory usage is under "%MEM".

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution

cd /			# <-- move to root directory
which bash		# <-- locate the directory bash is located: "/usr/bin/bash"
cd /usr/bin		# <-- move to the directory containing bash
bash -- version	# <-- check bash's version information (current version: GNU bash, version 5.0.16(1)-release (x86_64-pc-linux-gnu))
