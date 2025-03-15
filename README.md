# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

## AIM:

To use Google for gathering information and perform enumeration of targets

### STEPS:

#### Step 1:

Install kali linux either in partition or virtual box or in live mode

#### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


#### Step 3:
Open terminal and try execute some kali linux commands

### Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

#### site:
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain youtube.com




![image](https://github.com/user-attachments/assets/45371d57-0dc9-4d72-a47c-081bfa57b873)



#### filetype: 
![image](https://github.com/user-attachments/assets/6feb956c-78ab-4279-b601-39f4b649c00c)

This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

#### intext:
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![image](https://github.com/user-attachments/assets/6fe45767-8af8-4d86-a10b-59ddbec1b784)


#### inurl:
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![image](https://github.com/user-attachments/assets/575944d6-323a-4bd4-b5de-dd2424531e9b)

#### intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![image](https://github.com/user-attachments/assets/e96078df-0b82-4211-8295-0210a05356f6)



#### link:
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![image](https://github.com/user-attachments/assets/72f0f53d-90de-4ca3-a194-b5c747a26986)
#### cache:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![image](https://github.com/user-attachments/assets/aed15010-a748-42df-96a8-dba0f27d158f)

 
### DNS Enumeration


#### DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
#### OUTPUT:
![image](https://github.com/user-attachments/assets/a10e892b-b6c5-49a5-8bf8-35c2f2de937a)

#### dnsenum
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
![image](https://github.com/user-attachments/assets/4a927ba4-24fb-4ea3-98ef-addd715e7ba5)
![image](https://github.com/user-attachments/assets/52fb665c-0285-4e82-9261-34b84bd135fd)
![image](https://github.com/user-attachments/assets/c5faf32d-15de-4165-a8f8-209be6d5707f)


#### smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
![image](https://github.com/user-attachments/assets/b2157a0f-a9e7-4295-8bbe-deec68260195)


#### Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
#### Output
  
![image](https://github.com/user-attachments/assets/5773d4ee-3a8f-4956-b736-ac21811bfb63)

#### nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


#### OUTPUT:
 
![image](https://github.com/user-attachments/assets/b8fc4ea1-5ff2-40d7-98fe-244f0a1184b9)
 

### RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

