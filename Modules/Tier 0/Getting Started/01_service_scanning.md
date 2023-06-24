# Service Scanning

## NMAP

nmap target

### Most Important Parameters

-sC Use nmap scripts

-sV version scan

-p- All TCP ports

-p8080 port 8080

___


## SMB

smbclient \\\\target

### Parameters

-L list of available shares

-N suppresses pswd prompt

smbclient \\\\target\\dirs

smbclient -U username \\\\target\\dirs