# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```
Developed by:Mahisha S
Register no:212222040095
```
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

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion








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


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 
  
  

# nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
## site:
![Screenshot 2025-03-14 133834](https://github.com/user-attachments/assets/9022d1b6-c168-4096-8bdd-c5451454b95f)



## filetype:
![Screenshot 2025-03-14 133910](https://github.com/user-attachments/assets/246aff14-f450-4c23-b923-1ee14e68eb14)





## intext:
![Screenshot 2025-03-14 134000](https://github.com/user-attachments/assets/bb77e073-7920-4359-aa3f-ca091f90c51c)





## inurl:

![Screenshot 2025-03-14 092829](https://github.com/user-attachments/assets/6afa5203-b6c8-47a3-bf9d-fbce5335b000)


## intitle:
![Screenshot 2025-03-14 093043](https://github.com/user-attachments/assets/2afe834b-af95-4f53-b057-38fcec9f5356)




## link:
![Screenshot 2025-03-14 134029](https://github.com/user-attachments/assets/a3fcc714-3b7f-417b-98e9-8572ce41d8a2)





## cache:

![{CE751739-2C28-4363-9D75-926D8EA4F27E}](https://github.com/user-attachments/assets/900e84da-7343-448e-a6ca-dc44ed9a6e2e)


## DNS Enumeration:
## DNS Recon:
![Screenshot 2025-03-14 141927](https://github.com/user-attachments/assets/e156c225-eb82-4e7f-bdb2-96f676e8e682)


## dnsenum:

![Screenshot 2025-03-14 221210](https://github.com/user-attachments/assets/b0977f5f-d412-4243-bdf5-d2e9c2df4145)


![Screenshot 2025-03-14 221651](https://github.com/user-attachments/assets/34307e76-e1bd-431e-9fc7-236cfc1e3876)




## smtp-user-enum:

![Screenshot 2025-03-14 221850](https://github.com/user-attachments/assets/498428b2-8796-448e-9db5-cd68a36fb46b)

![Screenshot 2025-03-14 222118](https://github.com/user-attachments/assets/8e03be64-b85f-44c5-94db-3714b66828d1)

## telnet:
![Screenshot 2025-03-14 222519](https://github.com/user-attachments/assets/e28dd1c8-0479-4841-94a1-76e77fbbfc27)



## nmap –script smtp-enum-users.nse :

![Screenshot 2025-03-14 222659](https://github.com/user-attachments/assets/9e0ed808-9055-43b0-8273-ff30b4b5cac2)




## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

