# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:
To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:
Install kali linux either in partition or virtual box or in live mode

### Step 2:
Investigate on the various Google hacking keywords and enumeration tools as follows:

### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

Site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/be46fcbb-b338-4e9f-8a46-5c273fadda29)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files. Following searches for pdf file in the domain yahoo.com

## OUTPUT
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/6ed35bba-12a1-4b69-8e90-d9e515067fd1)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

## OUTPUT
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/90af166e-c113-41b5-b6d1-c1b46615bd1b)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.


## OUTPUT
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/52e55e7b-1143-4fd5-a8a2-708d70b8e56a)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.


## OUTPUT
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/1c387450-2fc8-44d2-b76f-fdb5a83446d7)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

## OUTPUT 
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/905c090f-7fee-40fd-b596-199642d44010)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.


## OUTPUT 
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/bf6a0fcd-4708-4e80-91b6-0763a7fe406d)
 
# DNS Enumeration

## DNS Recon

provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/5d6e501a-1f44-40f7-bccf-af6f61ad15ae)

![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/f4ac434f-1fc5-4872-9788-525cdad43ef0)

## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

## OUTPUT
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/645c8d19-9f20-492f-abca-ac430d13ff7c)

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/9c3d7d99-d923-436a-9331-f0b57156770e)

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/ed3cac03-93fa-4844-bbaa-bf2fe5e88c3c)

select any username in the first column of the above file and check the same
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/8fcfb41c-c63c-4d7d-9a78-0a1843d3fb4b)

## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
 
![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/de7bcedb-b93b-4268-8bcb-e3437b39db2f)

## nmap –script smtp-enum-users.nse <hostname>
The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

![image](https://github.com/SivaramakrishnanBaskar/Enumeration/assets/119476322/189c972b-c65f-4664-8bb1-ead0043e613b)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
