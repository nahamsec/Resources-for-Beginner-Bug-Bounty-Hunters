# Resources-for-Beginner-Bug-Bounty-Hunters

## Tools 🧰

Here you can find links to a bunch of useful tools for Bug Bounty Hunting.

## Table of Contents
1. [Proxy & Network Sniffer](#Proxy-&-Network-Sniffer)
2. [Burp Extensions](#Burp-Extensions)
3. [Recon, OSINT & Discovery](#Recon,-OSINT-&-Discovery)
4. [Exploitation](#Exploitation)
5. [Scanners](#Scanners)
6. [Mobile Hacking](#Mobile-Hacking)
7. [Notes & Organization](#Notes-&-Organization)
8. [Others](#Others)

### Proxy & Network Sniffer
| Name 	| Description 	| Written in   | Created by   |
|------	|-------------	|------------  |------------- |
|[Burp Suite](https://portswigger.net/burp)|A Proxy to intercept and manipulate Web Traffic (free & paid version). [Here](/assets/setup.md#setup) you can find Tips & Tricks to get started with Burp.|Java|Port Swigger|
|[OWASP Zap Proxy](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)|A Proxy to intercept and manipulate Web Traffic (free).|Java|OWASP
|[Caido](https://caido.io/)|A lightweight web security auditing toolkit.|Web|Caido|
|[Wireshark](https://www.wireshark.org)|Wireshark is a network protocol analyzer that lets you capture and read network packets.|C, C++|The Wireshark team|

### Burp Extension
| Name 	| Description 	| Written in   |
|------	|-------------	|------------  |
|[Logger++](https://portswigger.net/bappstore/470b7057b86f41c396a97903377f3d81)|"This extension can be used to log the requests and responses made by all Burp tools, and display them in a sortable table. It can also save the logged data in CSV format."|Java|
|[AuthMatrix](https://portswigger.net/bappstore/30d8ee9f40c041b0bfec67441aad158e)|"AuthMatrix is an extension to Burp Suite that provides a simple way to test authorization in web applications and web services. With AuthMatrix, testers focus on thoroughly defining tables of users, roles, and requests for their specific target application upfront. These tables are displayed through the UI in a similar format to that of an access control matrix commonly built in various threat modeling methodologies."|Python (Needs Jython version 2.7.0 or later)|
|[Autorize](https://portswigger.net/bappstore/f9bbac8c4acf4aefa4d7dc92a991af2f)|"Autorize is an extension aimed at helping the penetration tester to detect authorization vulnerabilities..."|Python (Needs Jython)|
|[Autorize](https://portswigger.net/bappstore/f9bbac8c4acf4aefa4d7dc92a991af2f)|"Autorize is an extension aimed at helping the penetration tester to detect authorization vulnerabilities..."|Python (Needs Jython)|
|[Burp Bounty](https://portswigger.net/bappstore/618f0b2489564607825e93eeed8b9e0a)|"Burp Bounty helps Burp Suite Professional users to quickly and easily build their own scan checks for use with Burp Scanner"||
|[Param Miner](https://portswigger.net/bappstore/17d2949a985c4b7ca092728dba871943)|"Built to identify hidden, unlinked parameters, Param Miner is very useful when hunting for web cache poisoning vulnerabilities"||

### Asset Discovery
| Name 	| Description 	    
|------	|-------------    	
|[Amass](https://github.com/OWASP/Amass)|Uses a variety of different techniques to gather subdomains and can build a network map of the target. Very good export options.|
|[BuiltWith](https://builtwith.com)|A very handy Browser Extension (for Chrome, Firefox) that checks for more than 18,000 types of internet technologies. Gives you a very quick glance on what a Web Application is built.|
|[subfinder](https://github.com/projectdiscovery/subfinder)|subfinder is a subdomain discovery tool that discovers valid subdomains for websites by using passive online sources. It has a simple modular architecture and is optimized for speed. subfinder is built for doing one thing only - passive subdomain enumeration, and it does that very well.|
|[dnsgen]()|generates a combination of domain names from the provided input.|

### Fuzzing
| Name 	| Description 	    | 
|------	|-------------    	| 
|[FFuF](https://github.com/ffuf/ffuf)|A very fast Fuzzing Tool to brute force directories or other parameters. Highly configurable.|
|[dirsearch](https://github.com/maurosoria/dirsearch)|dirsearch is a simple command-line tool designed to brute force directories and files in websites|
|[FeroxBuster](https://github.com/epi052/feroxbuster)|A simple, fast, recursive content discovery tool written in Rust|


### Content Discovery
| Name 	| Description 	    | 
|------	|-------------    	| 
|[meg](https://github.com/tomnomnom/meg)|meg is a tool for fetching lots of URLs but still being 'nice' to servers. It can be used to fetch many paths for many hosts; fetching one path for all hosts before moving on to the next path and repeating.|
|[httpx](https://github.com/projectdiscovery/httpx)|A fast and multi-purpose HTTP toolkit that allows running multiple probes.|
|[hakrawler](https://github.com/hakluke/hakrawler)|hakrawler is a Go web crawler designed for easy, quick discovery of endpoints and assets within a web application. It can be used to discover Forms, Endpoints, Subdomains, Related documents and JS Files|
|[nuclei](https://github.com/projectdiscovery/nuclei)|"Nuclei is a fast tool for configurable targeted scanning based on templates offering massive extensibility and ease of use."|
|[waybackurls](https://github.com/tomnomnom/waybackurls)|Fetch all the URLs that the Wayback Machine knows about for a domain|

### Recon Framework
| Name 	| Description 	    | 
|------	|-------------    	| 
|[meg](https://github.com/six2dez/reconftw)| Automates the entire process of reconnaissance for you. It outperforms the work of subdomain enumeration along with various vulnerability checks and obtaining maximum information about your target.|
|[sn1per](https://github.com/1N3/Sn1per)|Discover hidden assets and vulnerabilities in your environment.|
|[Spiderfoot](https://github.com/smicallef/spiderfoot)| An open source intelligence (OSINT) automation tool. It integrates with just about every data source available and utilises a range of methods for data analysis, making that data easy to navigate.|
|[reNgine](https://github.com/yogeshojha/rengine)| reNgine is a web application reconnaissance suite with a focus on a highly configurable streamlined recon process.|
|[AutoRecon](https://github.com/Tib3rius/AutoRecon)| AutoRecon is a multi-threaded network reconnaissance tool which performs automated enumeration of services. It is intended as a time-saving tool for use in CTFs and other penetration testing environments (e.g. OSCP).|
|[Osmedeus](https://github.com/j3ssie/osmedeus)| A Workflow Engine for Offensive Security. It was designed to build a foundation with the capability and flexibility that allows you to build your own reconnaissance system and run it on a large number of targets.|

#### OSINT Search Engines
| Name 	| Description 	    | Created by   |
|------	|-------------    	|------------- |
|[hunter.io](https://www.hunter.io)|Email Enumeration for big corps|[Hunter Team](https://hunter.io/about)|
|[intelx.io](https://intelx.io/)|Swiss army Knife of OSINT|[Intelligence X](https://twitter.com/_IntelligenceX)|
|[Shodan](https://www.shodan.io/)|Search engine that lets you find systems connected to the internet with a variety of filters|John Matherly|
|[Censys](https://censys.io)|"Censys is a public search engine that enables researchers to quickly ask questions about the hosts and networks that compose the Internet."|[Censys](https://censys.io/company)|
|[crt.sh](https://crt.sh)|SSL certificate search tool|[Sectigo](https://sectigo.com/)|
|[Virus Total](https://www.virustotal.com)|WHOIS, DNS, and subdomain recon|[Virus Total Team](https://support.virustotal.com/hc/en-us/categories/360000160117-About-us)|
|[ZoomEye](https://www.zoomeye.org/)|Search engine for specific network components|[Team from Knownsec](https://www.knownsec.com/)|
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
|[KeyHacks](https://github.com/streaak/keyhacks)|Keyhacks is a repository which shows quick ways in which API keys leaked by a bug bounty program can be checked to see if they're valid.|/|streaak|
|[Nmap command helper](https://competent-goldberg-e5eefe.netlify.app/)|A tool that helps you with nmap commands. Has a build in training feature to help memorizing them.||0x0n0x|

### Mobile Hacking
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|Frida||||
|[jadx](https://github.com/skylot/jadx)|Dex to Java decompiler|Java|skylot|
|[Ghidra](https://ghidra-sre.org/)|"A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate in support of the Cybersecurity mission"|Java|NSA|
|[dex2jar](https://github.com/pxb1988/dex2jar)|Useful to convert dex files into jar to decompile the application.|Java, Smali|Bob Pan|
|[andriller](https://github.com/den4uk/andriller)|Andriller - is software utility with a collection of forensic tools for smartphones. It performs read-only, forensically sound, non-destructive acquisition from Android devices. [andriller.com](https://www.andriller.com/)|Python|[Denis Sazonov](https://github.com/den4uk)|
|[Mobile Security Framework (MobSF)](https://github.com/MobSF/Mobile-Security-Framework-MobSF/)|Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis. MobSF support mobile app binaries (APK, IPA & APPX) along with zipped source code and provides REST APIs for seamless integration with your CI/CD or DevSecOps pipeline.The Dynamic Analyzer helps you to perform runtime security assessment and interactive instrumented testing.|Python|MobSF Team|
|[objection](https://github.com/sensepost/objection)|"objection is a runtime mobile exploration toolkit, powered by Frida, built to help you assess the security posture of your mobile applications, without needing a jailbreak."|Python & TypeScript|[sensepost](https://github.com/sensepost)|
|[RMS - Runtime Mobile Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security)|Runtime Mobile Security (RMS) is a powerful web interface that helps you to manipulate Android Java Classes and Methods at Runtime|Python|[@mobilesecurity_](https://twitter.com/mobilesecurity_)|

### Notes & Organization
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|[Reconness](https://github.com/reconness/reconness)|"ReconNess helps you to run and keep all your #recon in the same place allowing you to focus only on the potentially vulnerable targets without distraction and without required a lot of bash skill or programing skill in general."|C#|[Reconness](https://github.com/reconness)|
|[Updog](https://github.com/sc0tfree/updog)|"Updog is a replacement for Python's SimpleHTTPServer. It allows uploading and downloading via HTTP/S, can set ad hoc SSL certificates and use HTTP basic auth."|Python|[sc0tfree](https://github.com/sc0tfree)|
|[Notion](https://notion.so)|"Write, plan, collaborate, and get organized — all in one tool."||Notion Labs|
|[Joplin](https://joplinapp.org/)|"Joplin is a free, open source note taking and to-do application, which can handle a large number of notes organised into notebooks. The notes are searchable, can be copied, tagged and modified either from the applications directly or from your own text editor. The notes are in Markdown format."|JavaScript|Laurent Cozic|
|[Xmind](https://www.xmind.net/)|XMind, a full-featured mind mapping and brainstorming tool, designed to generate ideas, inspire creativity, brings productivity in a remote WFH team.|/|XMind Ltd.|
|[Axiom](https://github.com/pry0cc/axiom)|Project Axiom is a set of utilities for managing a small dynamic infrastructure setup for bug bounty and pentesting.|Bash|[@pry0cc](https://twitter.com/pry0cc)|
|[PenTest.ws](https://pentest.ws/features)|PenTest.WS is a penetration testing web application for organizing hosts, services, vulnerabilities and credentials during a penetration test. A reporting module is available for documenting and delivering a full penetration test.||PenTest.ws|

### Others
| Name 	| Description 	    | Written in    | Created by   |
|------	|-------------    	| ------------  |------------- |
|[SecLists](https://github.com/danielmiessler/SecLists)|A huge collection of word lists for hacking.||Daniel Miessler|
|[AssetNote's Wordlists](https://wordlists.assetnote.io/)| Collection of wordlists created by AssetNote.|AssetNote.io|
|[Recon Pi](https://github.com/x1mdev/ReconPi)|A lightweight recon tool that performs extensive reconnaissance with the latest tools using a Raspberry Pi.||[@x1m_martijn](https://twitter.com/x1m_martijn)|
|[CyberChef](https://gchq.github.io/CyberChef/)|Awesome Tool for de-/encoding stuff. Try it out!|JavaScript|[gchq](https://github.com/gchq)|
|[webhook.site](https://webhook.site)|Webhook.site allows you to easily test, inspect, forward and create Custom Actions for any incoming HTTP request or e-mail.||[fredsted](https://github.com/fredsted)|
|[requestcatcher](https://requestcatcher.com/)|Request Catcher will create a subdomain on which you can test an application. All requests sent to any path on the subdomain are forwarded to your browser in real time.|||
|[canarytokens](https://canarytokens.org/)|[Description](https://blog.thinkst.com/p/canarytokensorg-quick-free-detection.html)||[Thinkst Canary](canary.tools)|

---
back to [Intro Page](/README.md)
