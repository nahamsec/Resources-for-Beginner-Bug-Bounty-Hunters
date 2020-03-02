# Resources-for-Beginner-Bug-Bounty-Hunters

## Tools 🧰

Here you can find links to a bunch of useful tools for Bug Bounty Hunting.

## Table of Contents
1. [Proxy & Network Sniffer](#Proxy-&-Network-Sniffer)
2. [Recon, OSINT & Discovery](#Recon,-OSINT-&-Discovery)
3. [Exploitation](#Exploitation)
4. [Scanners](#Scanners)
5. [Mobile Hacking](#Mobile-Hacking)
6. [Others](#Others)

### Proxy & Network Sniffer
| Name 	| Description 	| Written in   | Created by   |
|------	|-------------	|------------  |------------- |
|[Burp Suite](https://portswigger.net/burp)|A Proxy to intercept and manipulate Web Traffic (free & paid version). [Here](/assets/setup.md#setup) you can find Tips & Tricks to get started with Burp.|Java|Port Swigger|
|[OWASP Zap Proxy](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)|A Proxy to intercept and manipulate Web Traffic (free).|Java|OWASP|
|[Wireshark](https://www.wireshark.org)|Wireshark is a network protocol analyzer that lets you capture and read network packets.|C, C++|The Wireshark team|

### Recon, OSINT & Discovery
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|[FFuF](https://github.com/ffuf/ffuf)|A very fast Fuzzing Tool to brute force directories or other parameters. Highly configurable.|Go||
|[Sublist3r](https://github.com/aboul3la/Sublist3r)|Sublist3r enumerates subdomains using many search engines such as Google, Yahoo, Bing, Baidu and Ask. Sublist3r also enumerates subdomains using Netcraft, Virustotal, ThreatCrowd, DNSdumpster and ReverseDNS.|Python|Ahmed Aboul-Ela|
|[dirsearch](https://github.com/maurosoria/dirsearch)|dirsearch is a simple command-line tool designed to brute force directories and files in websites.|Python|Mauro Soria|
|[Amass](https://github.com/OWASP/Amass)|Uses a variety of different techniques to gather subdomains and can build a network map of the target. Very good export options.|Go|OWASP|
|[BuiltWith](https://builtwith.com)|A very handy Browser Extension (for Chrome, Firefox) that checks for more than 18,000 types of internet technologies. Gives you a very quick glance on what a Web Application is built.||BuiltWith®|
|[findomain](https://github.com/Edu4rdSHL/findomain)|Very fast cross-platform subdomain enumerator|Rust|[Eduard Tolosa](https://github.com/Edu4rdSHL)|
|[waybackurls](https://github.com/tomnomnom/waybackurls)|Fetch all the URLs that the Wayback Machine knows about for a domain|Go|[Tom Hudson](https://github.com/tomnomnom)|
|[meg](https://github.com/tomnomnom/meg)|meg is a tool for fetching lots of URLs but still being 'nice' to servers. It can be used to fetch many paths for many hosts; fetching one path for all hosts before moving on to the next path and repeating.|Go|[Tom Hudson](https://github.com/tomnomnom)|
|[httprobe](https://github.com/tomnomnom/httprobe)|Take a list of domains and probe for working http and https servers.|Go|[Tom Hudson](https://github.com/tomnomnom)|
|[Osmedeus](https://github.com/j3ssie/Osmedeus)|Fully automated offensive security framework for reconnaissance and vulnerability scanning|Python|[j3ssie](https://github.com/j3ssie)|
|[hakrawler](https://github.com/hakluke/hakrawler)|hakrawler is a Go web crawler designed for easy, quick discovery of endpoints and assets within a web application. It can be used to discover Forms, Endpoints, Subdomains, Related documents and JS Files|Go|[@hakluke](https://twitter.com/hakluke)|
|[Reconness](https://github.com/reconness)|A Web App Tool to Run and Keep all your #recon in the same place.|C#|[@reconness](https://twitter.com/reconness)|
|[Kockpy](https://github.com/guelfoweb/knock)|A python tool designed to enumerate subdomains on a target domain through a wordlist|Python|[@guelforweb](http://twitter.com/guelfoweb)|


#### OSINT Webpages
| Name 	| Description 	    | Created by   |
|------	|-------------    	|------------- |
|[hunter.io](https://www.hunter.io)|Email Enumeration for big corps|[Hunter Team](https://hunter.io/about)|
|[intelx.io](https://intelx.io/)|Swiss army Knife of OSINT|[Intelligence X](https://twitter.com/_IntelligenceX)|
|[Shodan](https://www.shodan.io/)|Search engine that lets you find systems connected to the internet with a variety of filters|John Matherly|
|[Censys](https://censys.io)|"Censys is a public search engine that enables researchers to quickly ask questions about the hosts and networks that compose the Internet."|[Censys](https://censys.io/company)|
|[Lookyloo](https://lookyloo.circl.lu/scrape)|Lookyloo is a web interface allowing to scrape a website and then displays a tree of domains calling each other. [Github Page of the Project](https://github.com/CIRCL/lookyloo) |[CIRCL](https://circl.lu/)|
|[Spyse.com](https://spyse.com/)|New Search Engine made for pentesters and cyber security specialists|[Spyse Team](https://spyse.com/about)|
|[crt.sh](https://crt.sh)|SSL certificate search tool|[Sectigo](https://sectigo.com/)|
|[Virus Total](https://www.virustotal.com)|WHOIS, DNS, and subdomain recon|[Virus Total Team](https://support.virustotal.com/hc/en-us/categories/360000160117-About-us)|
|[ZoomEye](https://www.zoomeye.org/)|Search engine for specific network components|[Team from Knownsec](https://www.knownsec.com/)|
|[We Leak Info](https://weleakinfo.com/)|Databreach Search Engine|[We Leak Info](https://twitter.com/weleakinfo)|
|[NerdyData](https://nerdydata.com/)|Search Engine for Source Code|[NerdyData](https://www.crunchbase.com/organization/nerdydata)|
|[Crunchbase](https://www.crunchbase.com/)|For finding Information about Businesses and their acquisitions|[TechCrunch](https://techcrunch.com)|
|[Searchcode](https://searchcode.com/)|Helping you find real world examples of functions, API's and libraries over 90 languages across multiple sources|[searchcode](https://searchcode.com/about/#team)|







### Exploitation
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|[sqlmap](http://sqlmap.org/)|sqlmap is an open-source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.|Python|sqlmapproject |
### Scanners
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|[Nmap](https://nmap.org)|A well known and powerful Tool for port scanning. Nmap provides the possibility to use scripts to further customize its functionality. |C, C++, Python, Lua|Gordon Lyon|
|[Masscan](https://github.com/robertdavidgraham/masscan)|This is an Internet-scale port scanner. It can scan the entire Internet in under 6 minutes, transmitting 10 million packets per second, from a single machine.|C|Robert David Graham|
### Mobile Hacking
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|Frida||||
|[dex2jar](https://github.com/pxb1988/dex2jar)|Useful to convert dex files into jar to decompile the application.|Java, Smali|Bob Pan|
|[andriller](https://github.com/den4uk/andriller)|Andriller - is software utility with a collection of forensic tools for smartphones. It performs read-only, forensically sound, non-destructive acquisition from Android devices. [andriller.com](https://www.andriller.com/)|Python|[Denis Sazonov](https://github.com/den4uk)|
|[Mobile Security Framework (MobSF)](https://github.com/MobSF/Mobile-Security-Framework-MobSF/)|Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis. MobSF support mobile app binaries (APK, IPA & APPX) along with zipped source code and provides REST APIs for seamless integration with your CI/CD or DevSecOps pipeline.The Dynamic Analyzer helps you to perform runtime security assessment and interactive instrumented testing.|Python|MobSF Team|

### Others
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|[SecLists](https://github.com/danielmiessler/SecLists)|A huge collection of word lists for hacking.||Daniel Miessler|
|[Recon Pi](https://github.com/x1mdev/ReconPi)|A lightweight recon tool that performs extensive reconnaissance with the latest tools using a Raspberry Pi.||[@x1m_martijn](https://twitter.com/x1m_martijn)|

---
back to [Intro Page](/README.md)