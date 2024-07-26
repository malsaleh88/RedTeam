# Network Scan Report for IP: 10.12.1.36

## Open Ports
- **TCP Ports**: 28 open
- **UDP Ports**: 'nmap -sU 10.12.1.36`.

## Service Versions
- **FTP**: `vsftpd 2.3.4` (Port 21/tcp)
- **SSH**: `OpenSSH 4.7p1 Debian 8ubuntu1` (Port 22/tcp)
- **Apache**: `Apache httpd 2.2.8 ((Ubuntu) DAV/2)` (Port 80/tcp)

## Anonymous FTP Access
- **Command**: `nmap -p 21 --script ftp-anon 10.12.1.36`
- **Result**: Anonymous FTP login allowed (FTP code 230)

## SYN Scan
- **Command**: `sudo nmap -sS 10.12.1.36`
- **Result**: Lists 28 open TCP ports including FTP, SSH, Telnet, SMTP, HTTP, and more.

## Firewall Bypass Scan
- **Command**: `sudo nmap -sS -f 10.12.1.36`
- **Result**: All 1000 scanned ports are in ignored states, likely due to a firewall.

## Default NSE Script Scan
- **Command**: `sudo nmap --script default 10.12.1.36`

## Port 8180 Service
- **Service**: Apache-Coyote/1.1

## MySQL Salt
- **Command**: `nmap -p 3306 --script mysql-info 10.12.1.36`
- **Salt**: `E$%*E\}$8+mf9)a,WSw}`

## Domain Information
- **Command**: `nmap -p 445 --script smb-os-discovery 10.12.1.36`
- **Domain Name**: `localdomain`
- **Fully Qualified Domain Name (FQDN)**: `metasploitable.localdomain`
- **Operating System Version**: Unix (Samba 3.0.20-Debian)
- **Samba Version**: Samba 3.0.20-Debian
- **Box Name**: `metasploitable`

## Subnet Scan
- **Command**: `nmap -sn 10.12.1.0/24`
- **Number of IP Addresses Responding**: 6

## Top Ports Scan
- **Command**: `nmap --top-ports 10 10.12.1.0/24`
- **Result**: Lists top 10 ports for each responsive IP.

