if your new kernel version is higher than the old version then the ubuntu will automatically enter into the higher version kernel.

for my situation, my new kernel verison is 4.18.14 and my old kernel version is 5.3.0-46,
thus the ubuntu selected the higher level version.

Modify the configuration options of grub to display the menu bar for selecting the kernel version at boot.

The following is the way to enter the grub interface to select the kernel:
{
  gedit /etc/default/grub
  (Use gedit to open the configuration file，Only need to modify “GRUB_HIDDEN_TIMEOUT”. Just need to comment out this line,
   like this "#GRUB_HIDDEN_TIMEOUT=0")
   ![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/commend.png)
   
   Restart after successful setting。 You will see the following screen
   select the "*Advanced option for Ubuntu"
   ![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/p-2.png)
   select the "*Ubuntu, WITH lINUX 4.18.14"
   ![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/p-3.png)
   
   You should have entered the new kernel after above steps.
   open the terminal and use "uname -r" to check the version.
   ![image](https://github.com/Jeffrey-HJH/Linux/blob/master/Problem/check-version.png)
   
   
}
