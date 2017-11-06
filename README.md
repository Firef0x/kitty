What is KiTTY ?
===

[KiTTY](http://kitty.9bis.net/) is a fork from version 0.70 of PuTTY, the best telnet / SSH client in the world. 
KiTTY is only designed for the Microsoft® Windows® platform. For more information about the original software, or pre-compiled binaries on other systems, you can go to the [Simon Tatham PuTTY page](http://www.chiark.greenend.org.uk/~sgtatham/putty/). 


How to compile KiTTY under MinGW ?
===

1. Install MinGW with msys2.
2. You'll need to install `mingw-w64-i686-mpc` lib inside of MinGW.
3. Get the KiTTY source by cloning this repository.
4. Run the MinGW msys terminal, Change directory to `0.70_My_PuTTY/windows` and execute:

```sh
make -f MAKEFILE.MINGW putty.exe
```