
How many files could you find on port 80?


Total Discovered Files/Directories:
Directories: /cgi-bin/, /dav/, /test/, /twiki/
Files: /backup, /index, /index.php, /phpMyAdmin, /phpinfo, /phpinfo.php, /server-status


What is the version of apache?
What is the version of php ?


──(moha㉿kali)-[~]
└─$ curl -I 10.12.1.40
HTTP/1.1 200 OK
Date: Wed, 24 Jul 2024 12:19:19 GMT
Server: Apache/2.2.8 (Ubuntu) DAV/2
X-Powered-By: PHP/5.2.4-2ubuntu5.10
Content-Type: text/html


What server extension is installed?

DAV/2

What is the name of the file in testoutput?

.hta                [33m (Status: 403)[0m [Size: 287]
/.htaccess           [33m (Status: 403)[0m [Size: 292]
/.htpasswd           [33m (Status: 403)[0m [Size: 292]
/backup              [32m (Status: 200)[0m [Size: 51]
/cgi-bin/            [33m (Status: 403)[0m [Size: 291]
/dav                 [36m (Status: 301)[0m [Size: 311][34m [--> http://10.12.1.40/dav/][0m
/index               [32m (Status: 200)[0m [Size: 891]
/index.php           [32m (Status: 200)[0m [Size: 891]
/phpMyAdmin          [36m (Status: 301)[0m [Size: 318][34m [--> http://10.12.1.40/phpMyAdmin/][0m
/phpinfo.php         [32m (Status: 200)[0m [Size: 47972]
/phpinfo             [32m (Status: 200)[0m [Size: 47960]
/server-status       [33m (Status: 403)[0m [Size: 296]
/test                [36m (Status: 301)[0m [Size: 312][34m [--> http://10.12.1.40/test/][0m
/twiki               [36m (Status: 301)[0m [Size: 313][34m [--> http://10.12.1.40/twiki/][0m



Do a scan with Nikto on port 80.
Your response
An informative file in php seems to be available, what is its name?

What application has a name that starts with T and ends with Y?
Your response

What curl command can you use to see the server version?
Your response

What tool for enumerating files does it do recursively? (By default)
Your response

What other administration application is currently also on port 80?
Your response

