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

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

<img width="1550" height="847" alt="image" src="https://github.com/user-attachments/assets/4d23da91-1469-4cb8-b528-5e79e6fda0f1" />


## filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

<img width="1385" height="829" alt="image" src="https://github.com/user-attachments/assets/f0f103a0-ffc8-496b-9b9f-c7a97ab1551a" />




## intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

<img width="1577" height="872" alt="image" src="https://github.com/user-attachments/assets/3475fa44-02aa-4545-ba13-aa24d4bcf33b" />


## inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

<img width="1558" height="829" alt="image" src="https://github.com/user-attachments/assets/0eac40f7-aec3-4aec-a54e-7f0d97c61739" />



## intitle: 
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
<img width="1513" height="834" alt="image" src="https://github.com/user-attachments/assets/99bfbfc4-9d23-4d78-a064-4759326f4574" />

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
<img width="1591" height="851" alt="image" src="https://github.com/user-attachments/assets/aa21e17e-0a8a-4fdd-a98a-d7c357b5ef89" />


## cache:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
<img width="1803" height="869" alt="image" src="https://github.com/user-attachments/assets/c63117e6-198d-477a-a026-231c3e027480" />

 
# DNS Enumeration


## DNS Recon

provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## OUTPUT:

<img width="746" height="603" alt="image" src="https://github.com/user-attachments/assets/bb21a594-6fae-4950-9a29-98392372574c" />





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

## Output:

<img width="733" height="543" alt="image" src="https://github.com/user-attachments/assets/7c1e5164-50a3-4edc-b3c2-f1d8fb7342f1" />


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
  
 ## Output:
 
  <img width="747" height="415" alt="image" src="https://github.com/user-attachments/assets/df055f43-0a50-48ec-ab9e-9e27218eef4d" />

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

<img width="680" height="142" alt="image" src="https://github.com/user-attachments/assets/bf2982f5-e7bb-4537-9a7d-bc5bfed15ad2" />

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
