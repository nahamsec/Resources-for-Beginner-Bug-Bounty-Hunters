# Resources-for-Beginner-Bug-Bounty-Hunters

## Basics 🤓

### Table of Contents
1. [Stanford CS 253 Web Security](#Stanford-CS-253-Web-Security)
2. [HTTP basics](#HTTP-basics)
3. [Networking basics](#Networking-basics)
4. [Programming Basics](#Programming-Basics)
5. [Automation](#Automation)
6. [Linux basics](#Linux-Basics)
7. [Web Server Basics](#Web-Server-Basics)
8. [Computing Fundamentals](#Computing-Fundamentals)
9. [Hacking Basics](#Hacking-Basics)

### Stanford CS 253 Web Security
- [Stanford CS 253 Web Security](https://web.stanford.edu/class/cs253/) - by [@feross](https://twitter.com/feross)
   - "This course is a comprehensive overview of web security. The goal is to build an understanding of the most common web attacks and their countermeasures. Given the pervasive insecurity of the modern web landscape, there is a pressing need for programmers and system designers to improve their understanding of web security issues."

### HTTP basics
In order to be able to learn what and how an application works, you need to be able to understand how you are communicating with it. This section is dedicated to all the resources to understand the HTTP basics.
- [All in one resource](https://www.hacker101.com/sessions/web_in_depth)
	- HTTP basics
   - Cookie security
   - HTML parsing
   - MIME sniffing
   - Encoding sniffing
   - Same-Origin Policy
   - CSRF (Cross-Site Request Forgery)
- [Request form](https://www.tutorialspoint.com/http/http_requests.htm)
- [Response form](https://www.tutorialspoint.com/http/http_responses.htm)
- [Response codes](https://www.tutorialspoint.com/http/http_status_codes.htm)
- [URL Encoding](https://www.tutorialspoint.com/http/http_url_encoding.htm)


### Networking basics
Recon is a common terminology used in bug bounties. It’s great if you are already using tools to scan a range of IPs for open ports or find subdomain, however, you should first understand why these things matter and how they work.
- [Terminology](https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols)
- [What is an IP?](https://commotionwireless.net/docs/cck/networking/learn-networking-basics/)
- [What are ports?](https://www.utilizewindows.com/list-of-common-network-port-numbers/)
- [What is DNS?](https://code.tutsplus.com/tutorials/an-introduction-to-learning-and-using-dns-records--cms-24704)
- [Intermediate Security Testing with Kali Linux 2](http://www.penguintutor.com/linux/basic-network-reference)
- [Network Fundamentals](https://www.youtube.com/playlist?list=PLDQaRcbiSnqF5U8ffMgZzS7fq1rHUI3Q8), A 19 part Video Series about Networking well explained for Beginners


### Programming Basics
Being a great programmer is not a requirement to be a successful hacker. However, having the ability to make an educated guess, may increase your chances of successfully identifying and exploiting an issue. In a number of cases, you may need to automate your work or know more than just the “basics” in order to escalate a bug with a medium severity to high/critical.
- HTML: HTML is very easy to learn and there are a ton of free resources for it. If you are interested in learning about XSS this should be your first step. If you prefer an interactive tool to learn about JavaScript, I highly recommend [Codecademy](http://ssqt.co/mQfH8zl) or [W3Schools](https://www.w3schools.com/html/)!
- JavaScript: Once you have familiarized yourself with HTML, you should understand JavaScript since you will be using it to exploit XSS vulnerabilities. The usage of JavaScript isn’t just limited to when you are exploring XSS, so it’s a very handy programming language to know.
If you prefer an interactive tool to learn about JavaScript, I highly recommend [CodeCademy](http://ssqt.co/mQfH8zl)!
- SQL: You may have guessed It already, but you won’t be able to exploit complex SQL injection vulnerabilities before having any SQL knowledge.
As always, if you prefer an interactive course, feel free to use [CodeCademy](http://ssqt.co/mQfH8zl)!
https://www.codecademy.com/learn/learn-sql
http://www.sqlcourse.com/

### Automation
You are welcome to skip this section if you think you’ll never need any automation or in depth web application knowledge. However I think learning bash in addition to one the following four languages may help you work smarter rather than harder.
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

### Web Server Basics
If you are looking into getting started with Bug Bounties with a focus on web, I highly recommend learning the nuts and bolts of what make a website work.

- [Installing Apache, MySQL, PHP on Windows 10](https://codebriefly.com/how-to-setup-apache-php-mysql-on-windows-10/)
- [Installing Apache, MySQL, PHP on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04)
- [Setting Up Your Ubuntu Box for Pentest and Bug Bounty Automation](https://www.youtube.com/watch?v=YhUiAH5SIqk)

After creating your own web server, I highly recommend installing a CMS (like Wordpress or drupal) on your localhost to understand how it all works.

### Linux Basics
- [Install WSL on Windows 10](https://ubuntu.com/wsl)
- [Basics Linux Commands](https://www.hostinger.com/tutorials/linux-commands)
- [How to use curl](https://flaviocopes.com/http-curl/)
- [Loops](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO-7.html)
- [xargs](https://www.cyberciti.biz/faq/linux-unix-bsd-xargs-construct-argument-lists-utility/)

### Computing Fundamentals
- [Hopper's Roppers Computing Fundamentals](https://www.hoppersroppers.org/course.html)
	- This free course teaches the absolute basics of Linux, hardware, networking, operating systems, and scripting. Designed to get  a complete beginner over the first big learning hurdles and so they can move on to anything else and succeed.
- [Exeter Q-Step Resources](https://exeter-qstep-resources.github.io/)
   - Here, you will find a range of teaching materials that have been developed by members of the Q-Step Centre. If you have any questions, please contact l.brace@exeter.ac.uk or qstep@exeter.ac.uk. Details of Q-Step workshops and events can be found at https://socialsciences.exeter.ac.uk/q-step/events.

### Bug Bounty Basics
- [Bug bounty reports that stand out, how to write one?](https://thehackerish.com/bug-bounty-reports-that-stand-out-how-to-write-one/)
- [Bug Bounty Report Templates by @ZephrFish](https://github.com/ZephrFish/BugBountyTemplates/blob/master/Blank.md)
- [Hacker101- Writing Good Reports](https://www.youtube.com/watch?v=z60CFFFyZWE)
- [List of Bug Bounty Platforms](https://github.com/EdOverflow/bugbounty-cheatsheet/blob/master/cheatsheets/bugbountyplatforms.md)
- [Bug Bounty Cheatsheet](https://m0chan.github.io/2019/12/17/Bug-Bounty-Cheetsheet.html)
- [HOW TO GET STARTED IN BUG BOUNTY](https://www.youtube.com/watch?v=CU9Iafc-Igs)

---
back to [Intro Page](/README.md)
