# Introduction
Reverse Engineering is a very broad field it includes decompiling and disassembling of exectuable files and libraries, and analysis of system data. In cybersecurity it is usually used to study malware activity. 


## **The Roadmap**
So here I have listed some good resources that will help you get started in revesrse engineering aswell as help you advance your existing knowledge in the field. 

### Getting Started
For starters you need to know about assembly language (just be able to read it) and C language.
Here are some good resources to get you started.

[C-Programming Crash Course](https://www.youtube.com/watch?v=1uR4tL-OSNI)

[Nightmare - Intro to Assembly ](https://guyinatuxedo.github.io/01-intro_assembly/assembly/index.html)

[Architecture 1001 - OpenSecurityTraining2](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Arch1001_x86-64_Asm+2021_v1/course/)


### Binary Analysis
A binary file is obtained by compiling a source code and it can be executed on the platform it is compiled for. For example a You have a hello_world.c file (in linux) which prints "Hello World" to run this program you need to compile it using `gcc hello_world.c -o hello_world` This will create a a compiled elf executable called hello_world which you can then execute. There are two types of binary analysis:

**1. Static Analysis**
In static analysis you analyse the binary without executing it as the name suggests. One may use tools like IDA and Ghidra for doing static analysis. Here a few resources that will get you familiar with these tools.

[Ghidra Quickstart](https://www.youtube.com/watch?v=fTGTnrgjuGA)

[The Basics of IDA Pro](https://resources.infosecinstitute.com/topic/basics-of-ida-pro-2/)

[IDA Pro Book 2nd Edition](https://www.amazon.com/IDA-Pro-Book-Unofficial-Disassembler/dp/1593272898)


**2. Dynamic Analysis**
In dynamic analysis you analyse the binary by executing it in real time and observing its behaviour / looking for loopholes in real time. For dynamic analysis you can use GDB with GEF extension on linux, WinDBG and x64dbg for Windows, Binary Ninja, Angr, Z3, IDA Pro. Here are resources for dynamic analysis.

[Introductory GDB - OpenSecurityTraining2](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Dbg1012_GDB_1+2021_v1/course/)

[Introductory WinDBG - OpenSecurityTraining2](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Dbg1011_WinDbg1+2021_v1/course/)

[Debugging with GDB - Nightmare](https://guyinatuxedo.github.io/02-intro_tooling/gdb-gef/index.html)


### Linux ELF
An ELF (Executable and Linkable Format) is the standard binary format on operating systems such as Linux. Now the program structure differs for different programming languages the structure of a C program will be different while the structure of a rust program will be different. This is something that will require practice to understand. It is recommened to start with C programs as they are simple. The best way to practice reversing linux elf programs is by tryping out some ctf's or crackmes online. Here are some to get you started.

[crackmes.one](http://crackmes.one/)

[Flare-On CTF](http://flare-on.com/)

[Linux Reverse Engineering CTF's for Beginners - Infosecwriteups.com](https://infosecwriteups.com/linux-reverse-engineering-ctfs-for-beginners-4cf03ff2cfb4)

[Reversing ELF - TryHackMe](https://tryhackme.com/room/reverselfiles)


### Windows PE
A Windows PE (Portable Executable) is a file format for executables, object code, DLLs and others used in 32-bit and 64-bit versions of Windows operating systems. Unlike linux the program structure of windows PE files are slightly complex even in C programs. Here are some good resources to help you get started.

[Reverse Engineering for Beginners - Marcus Hutchins](https://www.youtube.com/watch?v=DFHug3Nq7eU&list=PLPsJIruML_ZivGWUd6bPkwDe-KFOIYg7p)

[Primary Methods of Reverse Engineering PE Files](https://eshagalawatta.medium.com/primary-methods-to-reverse-engineering-pe-files-exe-files-848bca8ba9a1)

[Win64 Assembly - TryHackMe](https://tryhackme.com/room/win64assembly)

[Windows Reversing Intro - TryHackMe](https://tryhackme.com/room/windowsreversingintro)


## Some Extra Resources
[Binary Exploitation / Memory Corruption by LiveOverflow](https://www.youtube.com/watch?v=iyAyN3GFM7A&list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)

[Open Security Training 2](https://p.ost2.fyi)

[Quick Tips on Reverse Engineering - OALabs](https://www.youtube.com/watch?v=vdyyg72tc2w&list=PLGf_j68jNtWFA_K0IEgdXUuigbTWFj9_u)

[Basics of x64 assembly with NASM - Undevs](https://un-devs.github.io/low-level-exploration/Trying-to-fit-that-x64-in-one/)

[Reverse Engineering Series - Slava Moskvin](https://www.youtube.com/watch?v=nLp3hr6Jf2M&list=PLDzElNZogx2tkCDJBzOmA6ParID2ogY36)


