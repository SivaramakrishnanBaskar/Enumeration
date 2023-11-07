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

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:

![exp3 1(1)](https://github.com/22008686/Enumeration/assets/118916413/4f1b50ba-7822-4087-8a57-409d1f870398)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files. Following searches for pdf file in the domain yahoo.com

![exp3 2(2)](https://github.com/22008686/Enumeration/assets/118916413/bf56cb3c-1c9b-4c51-9eed-70d7b9989aee)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![exp3 3(3)](https://github.com/22008686/Enumeration/assets/118916413/06d5278f-a71e-4a01-81b0-d40aea54f1ea)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![exp3 4(4)](https://github.com/22008686/Enumeration/assets/118916413/5cf7cef7-8ada-446e-a850-b08e4dcdaf9f)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![exp3 5(5)](https://github.com/22008686/Enumeration/assets/118916413/049130f2-0b0d-4b83-b506-790dfcbd72d9)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

!![exp3 6(6)](https://github.com/22008686/Enumeration/assets/118916413/13d8e043-b28c-4256-a04d-3bb6e3cd7828)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![exp3 8(8)](https://github.com/22008686/Enumeration/assets/118916413/0feb2fcb-3182-405b-ab0b-3a58de1bf46b)

## DNS ENUMERATION:
## DNS RECON:

#DNS Enumeration

##DNS Recon provides the ability to perform: Check all NS records for zone transfers Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT) Perform common SRV Record Enumeration Top level domain expansion.

![EXP3 9(9)](https://github.com/22008686/Enumeration/assets/118916413/24525c50-4a16-4181-989d-fdbcf7fd5f25)

![EXP3 (10)](https://github.com/22008686/Enumeration/assets/118916413/29ea0c5c-163d-4939-b609-a235d87b320b)

## DNSENUM:

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

![EXP3 (11)](https://github.com/22008686/Enumeration/assets/118916413/079cd3b8-19c0-40be-b650-4b8ae31cb5bf)

## smtp-user-enum :

Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

![EXP3 (12)](https://github.com/22008686/Enumeration/assets/118916413/6d090b7d-ce76-44c0-8b88-4895da37db54)

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

![EXP3 (13)](https://github.com/22008686/Enumeration/assets/118916413/e2308f0e-c567-45b5-8695-2eda072d15cb)

select any username in the first column of the above file and check the same

![EXP3 (14](https://github.com/22008686/Enumeration/assets/118916413/01ccfd8c-1244-47d9-894c-36ba31b6f508)

# Telnet for smtp enumeration:

Telnet allows to connect to remote host based on the port no. For smtp port no is 25 telnet 25 to connect and issue appropriate commands

![EXP3 (15)](https://github.com/22008686/Enumeration/assets/118916413/5ec9ec89-44cf-4a2e-ad86-8d22ebaffdd2)

## nmap –script smtp-enum-users.nse:

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

![EXP3 (16)](https://github.com/22008686/Enumeration/assets/118916413/b3b4c2f0-df5a-4298-bbea-3b30ef95a20f)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

