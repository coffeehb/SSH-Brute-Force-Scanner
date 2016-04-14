# SSH-Brute-Froce-Scanner
BSSHv2.4 is a great tool for scanning ssh2 connections by providing a list of IPs and passwords.

BSSHv2.4 is a great tool for scanning ssh2 connections by providing a list of IPs and passwords. It is fast, reliable and easy to use. It is written in C++, therefore it is compatible on a large scale of unix systems, both 32 and 64 bits.

Compatible on 32 and 64 bit sistem on a various systems
Fast and reliable
Easy to use
Using fork() hidden process (will appear as /sbin/init instead of bssh2.exe in `ps aux` command)
Making differance between linux sistems and NON-BASH systems
Detects honeypots [info here https://en.wikipedia.org/wiki/Honeypot_(computing)]
If an Linux system is encounters, retrives RAM and CPU data
Checks for updates before start
The script will run and eventually catch two type of ssh2 connections :

NOBASH (nobash.txt) -> systems that can’t support basic and common SSH2 commands, but can still be used as a sshtunnel (some of them)

LINUX (vuln.txt) -> systems that can support basic and common SSH2 commands, and there are two subtypes of LINUX :

a) :honeypot (those are not actually servers, just security nodes, see here more info https://en.wikipedia.org/wiki/Honeypot_(computing) )
b) :vuln (vulnerable systems)

This software is intended for testing only. Please use it at your own risk!

——————————————————————————
@SSH2 Bruteforce v2.3 @ 2015!
——————————————————————————–
MD5: 7531c6f496f4e4e2cb563ae2db4844c7
SHA1: d69d6e036a4648fabb6339d8be8568b3a3111b82
