FreeRTOS special for ARM Cortex-M
=================================

This repository is the FreeRTOS source but removing all ports except
for the GCC ARM_CM ports. I am only using these parts with GCC in my
projects so this reduces the clutter.  I also removed the Demo directory.
The main reason I made this repo is so that I can easily add it as a
submodule to my projects that use FreeRTOS.

This is the same source as downloaded from freertos.org web site.  I
added a tag to the repo to mark release snapshots.

License
-------
This source code is subject to the original FreeRTOS license.  See the
`license.txt` file for the complete license terms.

* * * * *

Original README
===============

Directories:

+ The FreeRTOS/Source directory contains the FreeRTOS source code, and
  contains its own readme file.

+ The FreeRTOS/Demo directory contains a demo application for every
  official FreeRTOS port, and contains its own readme file.

+ See http://www.freertos.org/a00017.html for full details of the
  directory structure and information on locating the files you require.

The easiest way to use FreeRTOS is to start with one of the pre-configured
demo application projects (found in the FreeRTOS/Demo directory).  That
way you will have the correct FreeRTOS source files included, and the
correct include paths configured.  Once a demo application is building and
executing you can remove the demo application file, and start to add in
your own application source files.

See also -
http://www.freertos.org/FreeRTOS-quick-start-guide.html
http://www.freertos.org/FAQHelp.html

