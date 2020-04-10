(1) open the terminal in the Linux operating system with a new version kernel
{ 
vim hello.c  (Write test source program)
![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/Test%20system%20call/hello.c.png)
     
gcc hello.c  (Compile the test source program)
![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/Test%20system%20call/gcc-hello.png)
        
./a.out  (Output result)
![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/Test%20system%20call/test-good.png)
(the return value is "1", means the system call succeeded)

or

gcc hello.c -o hello  (Compile the test source program)

./hello  (Output result)
![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/Test%20system%20call/gcc-hello-2.png)
(the return value is "1", means the system call succeeded)

dmesg  (View process information, the result is in the last line)
![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/Test%20system%20call/hello-world.png)
}
