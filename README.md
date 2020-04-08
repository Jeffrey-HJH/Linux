# Linux

Name : JIAHUI HU

Student Number : 200364402

The topic of OS : Add a system call in the Linux operating system

Description ：
	First build the environment in the Linux operating system in the virtual machine
	A set of subroutines for implementing various system functions are set in the Linux kernel, called system calls. Create a system call function as an example to illustrate how to add system calls to the kernel. First of all, a new kernel will be built during the process. I am using the linux-4.18.14. After adding a new system call to test, to ensure that the system call is added successfully. Then write a test file to test the added system call.

Challenges ：
	(1) : in the user mode cannot call casually the function of the kernel mode.
	(2) : Build a new kernel

Description and Instruction to reproduce the project
