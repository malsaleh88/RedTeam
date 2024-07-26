# Port 80 Analysis for IP: 10.12.1.40

## Discovered Files and Directories
- **Directories**: 
  - `/cgi-bin/`
  - `/dav/`
  - `/test/`
  - `/twiki/`
- **Files**:
  - `/backup`
  - `/index`
  - `/index.php`
  - `/phpMyAdmin`
  - `/phpinfo`
  - `/phpinfo.php`
  - `/server-status`

## Versions
- **Apache Version**: `2.2.8 (Ubuntu)` (Found in HTTP headers)
- **PHP Version**: `5.2.4-2ubuntu5.10` (Found in HTTP headers)

## Server Extension
- **Extension Installed**: `DAV/2`

## File in `testoutput`
- **Informative File**: `phpinfo.php`

## Nikto Scan Results
- **Server**: `Apache/2.2.8 (Ubuntu) DAV/2`
- **X-Powered-By Header**: `PHP/5.2.4-2ubuntu5.10`
- **Notable Findings**:
  - Missing `X-Frame-Options` header.
  - Missing `X-Content-Type-Options` header.
  - Apache `mod_negotiation` with `MultiViews` enabled.
  - Outdated Apache version (current is at least Apache/2.4.54).
  - HTTP TRACE method is active, which may suggest vulnerability to XST.
- **Scan Duration**: 250 seconds

## Informative File Name
- **Informative File**: `phpinfo.php`

## Application Name Starting with T and Ending with Y
- **Answer**: `Twiki`

## Curl Command to See Server Version
- **Command**: `curl -I 10.12.1.40`

## Tool for Recursively Enumerating Files (By Default)
- **Tool**: `dirb`

## Additional Administration Application on Port 80
- **Application**: `phpMyAdmin`
