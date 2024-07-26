
──(moha㉿kali)-[~]
└─$ nmap -p- 10.12.1.36

Starting Nmap 7.94SVN ( https://nmap.org ) at 2024-07-26 12:22 CEST
Nmap scan report for 10.12.1.36
Host is up (0.055s latency).
Not shown: 65507 closed tcp ports (conn-refused)
PORT      STATE SERVICE
21/tcp    open  ftp
22/tcp    open  ssh
23/tcp    open  telnet
25/tcp    open  smtp
53/tcp    open  domain
80/tcp    open  http
111/tcp   open  rpcbind
139/tcp   open  netbios-ssn
445/tcp   open  microsoft-ds
512/tcp   open  exec
513/tcp   open  login
514/tcp   open  shell
1099/tcp  open  rmiregistry
1524/tcp  open  ingreslock
2049/tcp  open  nfs
2121/tcp  open  ccproxy-ftp
3306/tcp  open  mysql
3632/tcp  open  distccd
5432/tcp  open  postgresql
6667/tcp  open  irc
6697/tcp  open  ircs-u
8009/tcp  open  ajp13
8180/tcp  open  unknown
8787/tcp  open  msgsrvr
45517/tcp open  unknown
51437/tcp open  unknown
57490/tcp open  unknown
57949/tcp open  unknown

Nmap done: 1 IP address (1 host up) scanned in 12.60 seconds
