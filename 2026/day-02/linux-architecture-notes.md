Core Components of Linux:

Linux works on the ASK principle where a stands for application, s for shell and k for kernel. The main component of linux is kernel that talks to the hardware. 
Lets first understand the architecture of linux. 
User opens the application and application could be paint, notepad etc. Then Shell is nothing else but an interactive way to talk to the kernel. 
Terminal is a tool and shell(black screen) that as a user we will interact with the kernel(linux kernel) through commands. 
Kernel - heart/ core component of the linux in which the computer program has been written that only machine can understand. 

How basically process are created and managed?
so in linux - everything is a process even copying the file from one location to another is also a process. 
Whenever we turn off the system - BIOS(binary input output system) or motherboard that supplies the power that loads the hardware and then GRUB also knows as
grand unified boot loader - its a gatekeeper between the os and hardware and then linux kernel loaded. 

then finally we can see the main screen which is ubuntu loading screen and from here it started the process known as INIT and the process id is 1.

systemctl is a controller basically that helps a user to tun the process/application and every process has a process id. 

ex- systemctl start docker
systemctl stop docker
systemctl status docker 

- What systemd does and why it matters
Systemd will start the process which is a known as init where d stands for daemon(anything that run in the background). Without this, we cannot
work on the machine. 

- Explain **process states** (running, sleeping, zombie, etc.)
ex- systemctl start docker
systemctl stop docker
systemctl status docker 
- List **5 commands** you would use daily

ls, ls-l, cat filename, man anylinuxcommand, vim filename
