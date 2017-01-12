# CoBASH

## What is CoBASH:
CoBASH is a project with the same goal as the original CoLinux (Which this is modelled off of), to have native Linux Applications run on Microsoft Windows. How this happens is by using two componients, the Windows Subsystem for Linux, and xMing. Where this project is different is the Linux Kernel isn't actually running, only the BASH Terminal is, however by exploiting the power of xMing (X11 for Windows) a graphical user interface (such as a Desktop Environment or Window Manager) can be loaded. What this project will do is provide source for the xMing (renamed/remodelled coBASH and license it GNU GPLv3 instead of Public Domain), provide a script which will configure xMing (coBASH) to communicate with the Linux Subsystem, and link the two with a master script. I'm keeping it BASH (go figure) due to simplicity and not much needed to be done to achieve such goal, but hopefully this will recieve more support or even be supported by Microsoft, but for now its a concept.

## What CoBASH is NOT:
CoBASH isn't an alternative to using real Linux Distributions, as I love each and every one of them myself, but more as a tool to help developers that code in Linux but don't want to be slowed down by a virtual machine or switch to another partition. Something this also isn't is an Emulation or Virtualization, the Linux Subsystem communicates with the NT Kernel **DIRECTLY** and many things can be accessed by both (including filesystems, networking, etc.) Also, until the Creators Update for Windows 10 comes out, I'm not sure how the updated Linux Subsystem will react to this, so hoping it helps this project instead of completely break it or make it useless.

## Proof-Of-Concept:
TBA

## License:
* xMing - Public Domain [To be relicensed as GNU GPLv3 once CoBASH]
* CoBASH Scripts - GNU GPLv3
* Linux Subsystem - Some Windows License, idk.

## Contributors:
* AwlsomeAlex (At the time...)
