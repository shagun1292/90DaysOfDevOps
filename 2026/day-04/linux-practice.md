Run and record output for at least 6 commands
Include 2 process commands (ps, top, pgrep, etc.) 
ps or ps -ef - list all the current proccess 
ps-a list all the active running process. 
top -  will display all the proccesses with the complete details but its not interactive
htop display all the proccesses in an interative way such as horizontally and vertically. 
ps aux | grep nginx/ssh - it will only show the nginx proccess (| symbol stands for or)
pgrep - will provide the list of pids associated with the process, 
pgrep -u root nginx (it will give you the pid of the root user only)

Include 2 service commands (systemctl status, systemctl list-units, etc.)
System ctl is a system controller and its being used to control the state of the systemd(init process) and service manager. 
systemctl start nginx
systemctl stop nginx
systemctl status nginx


Include 2 log commands (journalctl -u <service>, tail -n 50, etc.)
journalctl -u nginx

Pick one service on your system (example: ssh, cron, docker) and inspect it
Keep it simple and actionable
