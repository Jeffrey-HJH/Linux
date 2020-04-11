Assignment a id number to the system call what you add into the syscalls.h

the first step need to get into the system call table, "syscall_64.tbl".

{

cd/usr/src/linux-4.18.14/arch/x86/entry/syscalls

vim syscall_64.tbl

}

or 

{

sudo vimarch/x86/entry/syscalls/syscall_64.tbl

}

then 

you will see some data like this :

(333    common(depend on you virtual machine is 32bit or 64bit)    function_name   sys_helloworld)

my virtual machine is 64 bit, so I use 64 :

(335 64 hello_world __x64_sys_helloworld)

so add 335 64 hello_world __x64_sys_helloworld follow the 334.
