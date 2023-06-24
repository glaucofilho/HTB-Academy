# Web Enumeration

## Gobuster

gobuster dir -u http://10.129.42.254/ -w /usr/share/dirb/wordlists/common.txt

git clone https://github.com/danielmiessler/SecLists

gobuster dns -d inlanefreight.com -w /usr/share/SecLists/Discovery/DNS/namelist.txt


## Banner Grabbing

curl -IL https://www.inlanefreight.com

## Whatweb

