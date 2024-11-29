---
layout: page
icon: fa-solid fa-list
title: Commands Cheatbook
type: cheatsheet
---

A bunch of commands I use to break stuff 💥👾

## Port Scanning

### Scan ports faster:

 <pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
rustscan -a 10.10.190.187 -- -A
  </pre>

## Steganography

### Extract hidden data from an image:

<pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
steghide extract -sf file-name.jpg
</pre>

## Network Discovery

### Discover devices on the local network:

<pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
arp-scan -l
</pre>

### Discover live hosts on the local network:

<pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
sudo netdiscover
</pre>

## Web Application Testing

### Scan a web server for vulnerabilities:

<pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
nikto -h http://ip_add
</pre>

## Brute Force Attacks

### Brute force SSH login:

<pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
hydra -L users:txt  -P /usr/share/wordlists/rockyou.txt ssh://ip_add
</pre>

### Brute force FTP login with a specific username:

<pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
hydra -l user -P passlist.txt ftp://192.168.0.1
</pre>

### Brute force IMAP login with a wordlist:

<pre style="background-color: #1e1e1e; color: #d4d4d4; padding: 15px; border-radius: 8px; font-size: 1rem; font-family: 'Courier New', monospace; white-space: pre-wrap; word-wrap: break-word; overflow-x: auto;">
hydra -L userlist.txt -p defaultpw imap://192.168.0.1/PLAIN
</pre>


