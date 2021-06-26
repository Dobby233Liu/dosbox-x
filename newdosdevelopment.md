---
layout: sub
title: DOSBox-X and Continued DOS Development Efforts
---

Despite the rumors of its demise DOS is actually never dead. <span style="font-weight: 600">There are many continued development efforts in the DOS world including now.</span>

For example, even though Microsoft had ended support for its MS-DOS systems about two decades ago, there is also the open source [FreeDOS project](https://freedos.org) which is designed to be a free DOS system compatible with MS-DOS and is under active developments as of this day.

There are many other DOS software being actively maintained and updated as well. Just to name a few examples:

* <span style="font-weight: 600">Want to play music?</span> [MPXPLAY](http://mpxplay.sourceforge.net/) is a powerful audio player for DOS that supports many multimedia formats such as MP3, AAC, OGG, and FLAC.

* <span style="font-weight: 600">Want to manage files?</span> [Doszip Commander](https://github.com/nidud/doszip) is a long filename (LFN)-aware file manager (Norton Commander clone) with built-in Zip and UnZip support.

* <span style="font-weight: 600">Want to program in Pascal?</span> [Free Pascal](https://www.freepascal.org/) is a versatile and open-source Pascal compiler that can target many processor architectures, with DOS version available.

* <span style="font-weight: 600">Want to run network applications?</span> [mTCP](http://www.brutman.com/mTCP/) is a set of TCP/IP applications for DOS and include applications like DHCP, FTP, FTPSRV, HTGET, and other networking tools.

* <span style="font-weight: 600">Want to run Windows console applications in DOS?</span> [HX DOS Extender](https://github.com/Baron-von-Riedesel/HX) is a free DOS extender with built-in Win32 PE file format support and development tools. (We're using it for our DOS package too!)

DOSBox-X is designed to be a general-purpose DOS emulator that is both complete and accurate, including emulations of all PC systems used by MS-DOS (or compatible) between 1980 and 2000 (e.g. 8086, 286, 386, 486, Pentium, Pentium Pro, etc). <span style="font-weight: 600">Apart from emulating existing DOS games and applications (and DOS-based Windows like Win3.x/9x), we also hope that DOSBox-X can help with new DOS developments</span> (also called <span style="font-style: italic">retro-developments</span> or <span style="font-style: italic">futuristic developments</span> sometimes). We would like to implement DOS emulation that is accurate enough to help make new DOS developments possible with confidence the program(s) will run properly on actual DOS machines. It is DOSBox-X's goal to cover all pre-2000 DOS and Windows 9x based hardware scenarios, including peripherals, motherboards, CPUs, and all manner of hardware that was made for PC hardware of that time.

It is very encouraging to see developers to write new DOS games or applications, even if they are 32-bit C++17 code compiled with [MinGW](https://osdn.net/projects/mingw) and to run with the help of HX DOS Extender or even JavaScript code interpreted by a JavaScript programming environment for DOS such as [DOjS](https://github.com/SuperIlu/DOjS).

DOSBox-X is very flexible and provides many configuration parameters in its full configuration file (take a look at [dosbox-x.reference.full.conf](https://raw.githubusercontent.com/joncampbell123/dosbox-x/master/dosbox-x.reference.full.conf)). The many tweaks and configuration parameters are there to help you describe to DOSBox-X what particular PC configuration(s) you want to emulate for that goal. With the power of configuration, you can also test your program against odd scenarios or problems with systems that may cause some programs to not function properly. If you have any questions or suggestions, please feel free to post them in the [DOSBox-X issue tracker](https://github.com/joncampbell123/dosbox-x/issues).

Not only we have DOSBox-X for emulating DOS, we also have [DOSLIB](https://github.com/joncampbell123/doslib) and [DOSLIB2](https://github.com/joncampbell123/doslib2) which provide numerous DOS programming example libraries (and sample code for Windows 3.x/9x) which are also used to test DOSBox-X and real DOS systems, as well as [Hackipedia](http://hackipedia.org/) which is a comprehensive online documentation collection for DOS-related programming. Be sure to check them out too!
