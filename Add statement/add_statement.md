get into the syscalls.h to add the statement what you write in the sys.c

use 
{

cd /usr/src/linux-4.18.14/arch/x86/include/asm/

vim syscalls.h
![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Add%20statement/get-in-syscalls.h.png)
}

and add the statement in the bottom 
![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Add%20statement/add%20statement.png)

{

asmlinkage long sys_helloworld(void)

}

then use ":wq" to quit syscalls.h


