# CS252_assignment
This repository contains solutions of Problem 2.24 and 3.19 from the textbook Operating System Concepts 10th Edition by Abraham Silberschatz, Peter Baer Galvin and Greg Gagne.

•Name     : Thejaswi.N    

•Roll No. : 201ME159


#Problem 2.24
#Statement

In Section 2.3 (System Calls), we described a program that copies the contents of one file to a destination file. This program works by first prompting the user for the name of the source and destination files. Write this program using either the POSIX or Windows API. Be sure to include all necessary error checking, including ensuring that the source file exists. Once you have correctly designed and tested the program, if you used a system that supports it, run the program using a utility that traces system calls. Linux systems provide the strace utility, and macOS systems use the dtruss command. (The dtruss command, which actually is a front end to dtrace, requires admin privileges, so it must be run using sudo.) These tools can be used as follows (assume that the name of the executable file is FileCopy: Linux: strace ./FileCopy macOS: sudo dtruss ./FileCopy Since Windows systems do not provide such a tool, you will have to trace through the Windows version of this program using a debugger.
