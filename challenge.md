
# Security Detective



## Question 1

Answer: I am ayeshaaafifa. My home folder is /home/ayeshaaafifa.

Commands: whoami, pwd



## Question 2

Answer: The server name is ubuntu and it runs Ubuntu 26.04.1 LTS.

Commands: hostname, cat /etc/os-release | head -2



## Question 3

Answer: The server has 3.3Gi of RAM and 4.4G of free disk space.

Commands: free -h, df -h /



## Question 4

Answer: root and ayeshaaafifa can log in with /bin/bash.

Commands: grep bash /etc/passwd



## Question 5

Answer: 260 processes are running (the line count of ps aux).

Commands: ps aux | wc -l



## Question 6

Answer: lab5user was created at 08:13:28 and deleted at 08:52:54 on 2026-10-16.

Commands: sudo grep -E "new user|delete user|userdel|removed" /var/log/auth.log

