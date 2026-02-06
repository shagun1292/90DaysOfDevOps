
- Process management
systemctl start process, systemctl stop process, systemctl status process

ps 	list all the processes
ps - a	list the active processes
top	display sorted info about the processes
ps ax	showed all the running proccesses
ps aux | grep ping	showed all the running proccess with the ping command only. | is only or
kill pid	kill a process using process id
htop	display sorted info about the running processes with the visual highlights.
	
- File system
change the file permission -> chmod filename
change ownership but group same -> chown filename
change group -> chgrp groupname


- Networking troubleshooting

- Include **at least 20 commands** with one‑line usage notes
ps 	list all the processes
ps - a	list the active processes
top	display sorted info about the processes
ps ax	showed all the running proccesses
ps aux | grep ping	showed all the running proccess with the ping command only. | is only or
kill pid	kill a process using process id
htop	display sorted info about the running processes with the visual highlights.
pwd	print working directory
cd	change directory
ls	list all the directories/file
ls -l	display detail
man pwd	it will show the manual of the pwd command about how we can use it and what to use with this command. man represent manual
uname -r	tells thelinux system
mkdir directory_name	it will create directory
touch filename.extension	it will creat a file
cat filename	to view the file content
cp source destination 	copy file/directory from source to destination
mv source destination 	move and rename file/directory from source to destination
rm source destination 	remove file/directory from source to destination
free	to check the disk usage
ip addr 
	it will display the ip address of the machine
ip -d addr	detail display
vim filename	edit the filename
- Add **3 networking commands** (`ping`, `ip addr`, `dig`, `curl`, etc.)

ifconfig -> display all network interfaces with IP addresses
ifconfig -a -> display all the netwrok with Ip address including down. 
netstat -> Displays all active connections and listening ports.
dig domain -> display the domain information
curl link -> display the html content of the given link
ping google.com -> ping the google server to check the status. 


