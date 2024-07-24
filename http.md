
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
 Nikto v2.5.0
---------------------------------------------------------------------------
+ Target IP:          10.12.1.40
+ Target Hostname:    10.12.1.40
+ Target Port:        80
+ Start Time:         2024-07-24 15:07:27 (GMT2)
---------------------------------------------------------------------------
+ Server: Apache/2.2.8 (Ubuntu) DAV/2
+ /: Retrieved x-powered-by header: PHP/5.2.4-2ubuntu5.10.
+ /: The anti-clickjacking X-Frame-Options header is not present. See: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options
+ /: The X-Content-Type-Options header is not set. This could allow the user agent to render the content of the site in a different fashion to the MIME type. See: https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/
+ /index: Uncommon header 'tcn' found, with contents: list.
+ /index: Apache mod_negotiation is enabled with MultiViews, which allows attackers to easily brute force file names. The following alternatives for 'index' were found: index.php. See: http://www.wisec.it/sectou.php?id=4698ebdc59d15,https://exchange.xforce.ibmcloud.com/vulnerabilities/8275
+ Apache/2.2.8 appears to be outdated (current is at least Apache/2.4.54). Apache 2.2.34 is the EOL for the 2.x branch.
+ /: Web Server returns a valid response with junk HTTP methods which may cause false positives.
+ /: HTTP TRACE method is active which suggests the host is vulnerable to XST. See: https://owasp.org/www-community/attacks/Cross_Site_Tracing
+ ERROR: Error limit (20) reached for host, giving up. Last error: 
+ Scan terminated: 0 error(s) and 8 item(s) reported on remote host
+ End Time:           2024-07-24 15:11:37 (GMT2) (250 seconds)
---------------------------------------------------------------------------
+ 1 host(s) testedAn 


informative file in php seems to be available, what is its name?
The informative file available on the server is named phpinfo.php




What application has a name that starts with T and ends with Y?
Your response

What curl command can you use to see the server version?
Your response

What tool for enumerating files does it do recursively? (By default)
Your response

What other administration application is currently also on port 80?
Your response

