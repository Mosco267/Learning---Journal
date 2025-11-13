# Day 1 - Notes on cybersecurity & TryHackMe PreSecurity
**Date:** 2025-11-03
**Platform:** Youtube & TryHackMe - Module:Intoduction to Cyber Security

## What I Learned
- Cybersecurity is the practice of protecting computer network,programs,computer system and its component from unauthorize access.
- Hackers attacks both individual and company. some of the individual attacks are man in the middle attack, malware attack, phishing attack. and some company attack include distributed denial of service(DDoS),DNS hijacking, and also SQL injection(SQLi)

- There are three type of hackers: Black hat hacker, Grey hat hacker, and White hat hacker(Ethical hacker).
- hacking is the exploitation of vulnerable computer network to obtaing infomation and credentials.
- "TryHackMe Pre-Security Completed"
- i setup start machine and downloaded openvpn and also learn to link my tryhackme account to kali linux.
  
 # Day 2 - Basic Computer & Network Terms
 **Date:** 2025-11-04
 **Platform:** Cloudflare & TryHackMe - Module:Network Fundamentals

 ## What I Learned (DAY 2)
 - IP Address(internet Protocol) are unique identifier assign to a device or domain that connents t the internet
 - There are two type of IP Address which are: IPV4(Internet protocol version 4) and IPV6(Internet protocol version 6)
 - Example of IPV4 are IP Address divided into 4 octets and number ranges from 0 to 255 example are this 10.139.210.098
 - Example of IPV6 Address are long sequence of number and alphabet usually 8 octets example are 1a23.r4w5.55h7.90gf.5hy8.k0u9.0so6.22va
 - DNS(Domain Name System) is what convert human-friendly domain names to IP address that computer use
 - HTTP(Hypertext transfer protocol) is the protocol for transferring web pages. HTTPS adds encryption for security
 - firewall controls and filters incoming/outgoing network traffic to protect system
 - there are either public or private IP

 # Day 3 - Learning Linux Commands & Explore TryHackMe "Linus Fundamentals" rooms(Parts 1-3)
 **Date:** 2025-11-06
 **Platform:** YouTube & TryHackMe

 ## What I Learned (DAY 3)
 - I learnt some basic linux commands which are:
 - cd - change directory
 - pwd - print working directory(shows part to any folder/file)
 - ls - listing(list all folders)
 - cat - concatenate(use in showing the content inside a file)
 - cd ..(use for going back after entering a folder)
 - find (use for locating files)
 - grep
 - echo(to rewrite what you wrote)
 - ip addr(to show ip address)
 - &(this command allow you to run operative in the background of your termial)
 - &&(this command allow you to run two command. the first command first, before the second command.if the first command is unable to run, the second command would not work.)
 - \>(this command help you to redirect a command into somewhere)
 - \>>(this command works like the > command but it appends the output rather than replacing it, meaning nothing is over written)
 - man(manual)
 - su(to switch user)
 - -a(all)
 - touch(to create a file)
 - mkdir-make directory(to creat a folder)
 - rm-remove(to delete a file)
 - rm -R(to delete a folder)
 - mv-move(to move a file/folder and also rename them)
 - cp-copy(to copy file)
 - file(to know the kind of file)

 # Day 4 - Learning Networking and How The Internet Works
 **Date:** 2025-11-11
 **Platform:** YouTube & Chatgpt

 ## What I Learned (DAY 4)
 - TCP/IP(Trasmission control protocol)/(Internet protocol)
 - ARP(Address resolution protocol)
 - DNS(Domain name system)
 - ISP(Internet service provider)
 - DHCP(Dynamic host configuration protocol)
 - NAT(Network address translation)
 - LAN(Local area network) example your home router
 - WAN(wide area network) example your ISP
 - How the internet work when i insert google.com on my browser and when i am connected to an home router that 4 other devices are connected to and now NAT works with TCP.
 - Ports are like door or channels in the computer that where network data goes in and out
 - port numbers are numbericical identifier in a computer that tell the computer what process or program to handle a network data
 - port numbers are from 0 to 65,535 and are divided into three which are listed below:
   1. well-known ports: this are ports for system service and the ranges from 0 - 1,023. example include; SSH, DNS, HTTP, etc.
   2. registered ports: this ports are registered ports and they ranges from 1,024 - 49,151. example include: applications, game, etc.
   3. dynamic or private ports: this ports are temporary port in computer for outgoing connections. this ports rangers from 49,152 to 65,535.
 - some common well known ports are listed below
  | port number | protocol | service/use |
  |--------------|----------|--------------|
  | 20/21 | FTP | file transfer protocol |
  | 22 | SSH | secure shell(remote logins) |
  | 23 | telnet | remote terminal(insecure) |
  | 25 | SMTH | sending emails |
  | 53 | DNS | domain name system(resolving dormain names to ip)
  | 80 | HTTP | website(insecure) |
  | 110 | POP3 | receiving emails |
  | 143 | IMAP | receiving emails(modern) |
  | 443 | HTTPs | website(secure) |
  | 3389 | RDP | remote desktop protocol(windows remote access) |
    
   
   
   
   
  
 
