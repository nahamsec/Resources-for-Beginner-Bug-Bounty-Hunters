# Resources-for-Beginner-Bug-Bounty-Hunters

## Basics 🤓
Before diving into bug bounty hunting, it is critical to have a solid understanding of how the internet and computer networks work. Understanding key concepts such as Transmission Control Protocol (TCP), a fundamental protocol used for transmitting data over the internet and other networks, is essential. Also, it is critical to understand networking concepts such as IP addresses, subnetting, and routing, which are all critical components of how devices communicate on a network. Another crucial concept to grasp is Domain Name System (DNS), which is in charge of converting human-readable domain names (such as google.com) into machine-readable IP addresses.

Understanding these concepts will provide a solid foundation for your bug bounty hunting journey, allowing you to better understand and navigate the various systems and networks you will encounter.

### Table of Contents
1. [HTTP basics](#HTTP-basics)
2. [Networking basics](#Networking-basics)
3. [Programming Basics](#Programming-Basics)
4. [Automation](#Automation)
5. [Linux basics](#Linux-Basics)
6. [Web Server Basics](#Web-Server-Basics)
7. [Computing Fundamentals](#Computing-Fundamentals)
8. [Hacking Basics](#Hacking-Basics)

### HTTP basics
In order to be able to learn what and how an application works, you need to be able to understand how you are communicating with it. This section is dedicated to all the resources to understand the HTTP basics.
- [All in one resource](https://www.hacker101.com/sessions/web_in_depth)
	- HTTP basics
   - Cookie security
   - HTML parsing
   - MIME sniffing
   - Encoding sniffing
   - Same-Origin Policy
- [Request form](https://www.tutorialspoint.com/http/http_requests.htm)
- [Response form](https://www.tutorialspoint.com/http/http_responses.htm)
- [Response codes](https://www.tutorialspoint.com/http/http_status_codes.htm)
- [URL Encoding](https://www.tutorialspoint.com/http/http_url_encoding.htm)


#### HTTP Basics Video Resources 
- [HTTP Crash Course & Exploration](https://www.youtube.com/watch?v=iYM2zFP3Zn0)
- [Same Origin Policy](https://www.youtube.com/watch?v=bSJm8-zJTzQ)

### Networking basics
Recon is a common terminology used in bug bounties. It’s great if you are already using tools to scan a range of IPs for open ports or find subdomain, however, you should first understand why these things matter and how they work.
- [Terminology](https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols)
- [What is an IP?](https://commotionwireless.net/docs/cck/networking/learn-networking-basics/)
- [What are ports?](https://www.utilizewindows.com/list-of-common-network-port-numbers/)
- [What is DNS?](https://code.tutsplus.com/tutorials/an-introduction-to-learning-and-using-dns-records--cms-24704)

#### Networking Basics Video Resources
-[Network Fundamentals](https://www.youtube.com/playlist?list=PLDQaRcbiSnqF5U8ffMgZzS7fq1rHUI3Q8), A 19 part Video Series about Networking well explained for Beginners
- [IP Addressing and IP Subnetting for the CCNA Exam by David Bombal] (https://youtube.com/watch?v=E-J8EPUvc8E)
- [What is DNS by David Bombal](https://www.youtube.com/watch?v=dl-C6cBoRg4)
- [CCNA 200-301 Complete Course](https://www.youtube.com/watch?v=H8W9oMNSuwo)
- [Free CCNA 200-301 Course: Network Fundamentals by David Bombal](https://www.udemy.com/course/free-ccna-200-301-network-fundamentals/)

### Programming Basics
Being a great programmer is not a requirement to be a successful hacker. However, having the ability to make an educated guess, may increase your chances of successfully identifying and exploiting an issue. In a number of cases, you may need to automate your work or know more than just the “basics” in order to escalate a bug with a medium severity to high/critical.
- HTML: HTML is very easy to learn and there are a ton of free resources for it. If you are interested in learning about XSS this should be your first step. If you prefer an interactive tool to learn about JavaScript, I highly recommend [Codecademy](http://ssqt.co/mQfH8zl) or [W3Schools](https://www.w3schools.com/html/)!
- JavaScript: Once you have familiarized yourself with HTML, you should understand JavaScript since you will be using it to exploit XSS vulnerabilities. The usage of JavaScript isn’t just limited to when you are exploring XSS, so it’s a very handy programming language to know.
If you prefer an interactive tool to learn about JavaScript, I highly recommend [CodeCademy](http://ssqt.co/mQfH8zl)!
- SQL: You may have guessed It already, but you won’t be able to exploit complex SQL injection vulnerabilities before having any SQL knowledge.
As always, if you prefer an interactive course, feel free to use [CodeCademy](http://ssqt.co/mQfH8zl)!
https://www.codecademy.com/learn/learn-sql
http://www.sqlcourse.com/

### Programming Basics Video Resources
- [HTML Basics In 10 Minutes] (https://www.youtube.com/watch?v=MDLn5-zSQQI)
- [JavaScript Tutorial for Beginners: Learn JavaScript in 1 Hour] (https://www.youtube.com/watch?v=W6NZfCO5SIk)
- [Learn SQL in 1 Hour - SQL Basics for Beginners] (https://www.youtube.com/watch?v=9Pzj7Aj25lw)

### Automation
You may skip this section if you believe you will never need automation or in-depth web application knowledge. However, I believe that learning bash in addition to one of the four languages listed below will allow you to work smarter rather than harder.

- Bash
   - https://www.learnshell.org/
   - https://explainshell.com/
- Ruby
   - https://www.learnrubyonline.org/
- Python
   - https://docs.python.org/3/tutorial/
- Go(lang)
   - https://golang.org
- Additional Resources:
   - https://www.codecademy.com/learn/paths/web-development
   - https://docs.python.org/3/tutorial/
   - http://www.sqlcourse.com/
   - https://en.wikibooks.org/wiki/Programming_Fundamentals/Advanced_Flowcharting
- PHP
  - https://php.net

#### Automation Video Resources
- [Beginner's Guide to the Bash Terminal](https://www.youtube.com/watch?v=oxuRxtrO2Ag)
- [Python for Beginners - Learn Python in 1 Hour] (https://www.youtube.com/watch?v=kqtD5dpn9C8)


### Web Server Basics
If you are looking into getting started with Bug Bounties with a focus on web, I highly recommend learning the nuts and bolts of what make a website work.

- [Installing Apache, MySQL, PHP on Windows 10](https://codebriefly.com/how-to-setup-apache-php-mysql-on-windows-10/)
- [Installing Apache, MySQL, PHP on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04)
- [Setting Up Your Ubuntu Box for Pentest and Bug Bounty Automation](https://www.youtube.com/watch?v=YhUiAH5SIqk)

After creating your own web server, I highly recommend installing a CMS (like Wordpress or drupal) on your localhost to understand how it all works.

#### Web Server Basics Videos
- [Python for Beginners - Learn Python in 1 Hour] (https://www.youtube.com/watch?v=kqtD5dpn9C8)
- [How to Install XAMPP Server on Windows 10](https://www.youtube.com/watch?v=-f8N4FEQWyY)

### Linux Basics
- [Install WSL on Windows 10](https://ubuntu.com/wsl)
- [Basics Linux Commands](https://www.hostinger.com/tutorials/linux-commands)
- [How to use curl](https://flaviocopes.com/http-curl/)
- [Loops](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO-7.html)
- [xargs](https://www.cyberciti.biz/faq/linux-unix-bsd-xargs-construct-argument-lists-utility/)

#### Linux Basics Videos
- [How to Install Ubuntu on Windows 10 (WSL)] (https://www.youtube.com/watch?v=X-DHaQLrBi8)
- [Linux Essentials: Curl Fundamentals](https://www.youtube.com/watch?v=Xy7fDxz39FM)
- [Xargs Should Be In Your Command Line Toolbag](https://www.youtube.com/watch?v=rp7jLi_kgPg)
- [Shell Scripting - For Loops](https://www.youtube.com/watch?v=T7hVOiTsSUU)

### Bug Bounty Basics
- [Hacker101's Getting Started](https://www.hacker101.com/start-here)
- [Bug bounty reports that stand out, how to write one?](https://thehackerish.com/bug-bounty-reports-that-stand-out-how-to-write-one/)
- [Bug Bounty Report Templates by @ZephrFish](https://github.com/ZephrFish/BugBountyTemplates/blob/master/Blank.md)
- [List of Bug Bounty Platforms](https://github.com/EdOverflow/bugbounty-cheatsheet/blob/master/cheatsheets/bugbountyplatforms.md)
- [Bug Bounty Cheatsheet](https://m0chan.github.io/2019/12/17/Bug-Bounty-Cheetsheet.html)

#### Bug Bounty Basics Videos
- [HOW TO GET STARTED IN BUG BOUNTY](https://www.youtube.com/watch?v=CU9Iafc-Igs)
- [Hacker101- Writing Good Reports](https://www.youtube.com/watch?v=z60CFFFyZWE)
- [Putting Your Mind to It: Bug Bounties for 12 Months - @zseano] (https://www.youtube.com/watch?v=-PkK9DP5nec)
- [How to Get Into Bug Bounty by Katie Paxton-Fear @InsiderPhD] (https://www.youtube.com/watch?v=19gIJ7gLbXI)


---
back to [Intro Page](/README.md)
