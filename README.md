# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:

Following Categories of pen test tools are identified for information gathering: Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![1](https://github.com/Migaleyy/InformationGathering/assets/118262199/f8b790e9-27a2-472d-8dee-e81a8e8bc462)

## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```
## Output:
![2](https://github.com/Migaleyy/InformationGathering/assets/118262199/8d6406a9-aa8c-4ed0-b1ee-5d00e0176094)

## Finding Hosting Company

get further detail by using ip2location.com website.

## Output:
![3](https://github.com/Migaleyy/InformationGathering/assets/118262199/4ee0d3d6-1c63-41dc-b4a7-105303c25b58)

## History of the website:
## Output:
https://web.archive.org/
![4](https://github.com/Migaleyy/InformationGathering/assets/118262199/0f208d06-c6ca-4ffe-86d0-6b736a9044cb)
```
nc 172.17.52.118 80
```
![5](https://github.com/Migaleyy/InformationGathering/assets/118262199/b548b92a-799f-4fc2-b047-3cdc6b11cf9c)
## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org

## Output:
![6](https://github.com/Migaleyy/InformationGathering/assets/118262199/8233e7f2-319a-44b2-8907-2616336b772d)
Whatweb:

```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![7](https://github.com/Migaleyy/InformationGathering/assets/118262199/67d10ffe-7a46-4da2-a7c7-3d33d1a0cdf7)

## httprint:

```
hhttprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![9](https://github.com/Migaleyy/InformationGathering/assets/118262199/1e26e0cf-7b3b-433c-aabe-c3cdc16ad838)

## Tracing the Location
## TCP Traceroute:

```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![10](https://github.com/Migaleyy/InformationGathering/assets/118262199/0daeafc4-acde-4437-8563-a7bfed250c15)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![12](https://github.com/Migaleyy/InformationGathering/assets/118262199/c2711c2d-0d46-4a51-a03e-f3986d945424)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
