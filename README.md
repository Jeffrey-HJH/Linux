# Linux

Name : JIAHUI HU

Student Number : 200364402

The topic of OS : Add a system call in the Linux operating system

	Description ：

	Add a new system call in the kernel of the Linux operating system.
	Shows how to build an environment step by step, install a new Linux kernel and debug newly added system calls.
	premise:
	
	(1): Computer system: macOS Catalina
	(2): Virtual machine parallels desktop
	(3): Linux version: Ubuntu 18.04
	(4): New kernel version: 4.18.14
	
	
	The Folder order
	(1) -> Environment
	(2) -> new linux kernel
	(3) -> Add system call
	(4) -> Add statement
	(5) -> Assign system call id
	(6) -> Recompile the kernel
	(7) -> Install kernel
	(8) -> Problem
	
	Challenges ：
	(1) : In the user mode cannot call casually the function of the kernel mode.
	(2) : Build a new kernel
	(3) : Install and compile the kernel

	Description and Instruction to reproduce the project:
	(1): Set up the environment in the Linux operating system in the virtual machine, download ubuntu-4.18.14, ubuntu-		18.04-desktop and parall desktop
	(2): Download and install various required packages.
	(3): Download and install ubuntu-4.18.14
	(4): sudo vim kernel / sys.c // Add system call
	(5): Add "Hello World" to sys.c
	(6): The system call id is allocated in syscall_64.tbl, depending on whether the system is 32-bit or 64-bit
	(7): Compile and install a new kernel.
	(8): Restart the virtual machine
	(9): Select the newly installed Linux kernel
	(10): Write code to test system calls
DONE.
