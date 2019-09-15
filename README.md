# Resources-for-Beginner-Bug-Bounty-Hunters

## Intro

There are a number of new hackers joining the community on a regular basis and this raises the question of "How do I get started and what are some good resources?" and we hope to help with those questions using this repository. 
As a hacker, there a ton of techniques, terminologies, and topics you need to familiarize yourself with to understand how an application works. Cody Brocious [(@daeken)](http://twitter.com/daeken) and I put these resources together in order to help new hackers with resources to learn the basics of Web Application Security. 

We understand that there are more resources other than the ones we have listed and we hope to cover more resources in the near future!

## HTTP basics
In order to be able to learn what and how an application works, you need to be able to understand how you are communicating with it. This section is dedicated to all the resources to understand the HTTP basics.
- All in one resource: https://www.hacker101.com/sessions/web_in_depth 
	HTTP basics 
            Cookie security 
            HTML parsing 
            MIME sniffing 
            Encoding sniffing 
            Same-Origin Policy 
            CSRF (Cross-Site Request Forgery)
- Request form
https://www.tutorialspoint.com/http/http_requests.htm 
- Response form 
https://www.tutorialspoint.com/http/http_responses.htm 
- Response codes 
https://www.tutorialspoint.com/http/http_status_codes.htm 
- URL Encoding
https://www.tutorialspoint.com/http/http_url_encoding.htm 
- Status Codes
https://www.tutorialspoint.com/http/http_status_codes.htm 


## Networking basics
Recon is a common terminology used in bug bounties. It’s great if you are already using tools to scan a range of IPs for open ports or find subdomain, however, you should first understand why these things matter and how they work.
- Terminology
https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols 
- What is an IP?
https://commotionwireless.net/docs/cck/networking/learn-networking-basics/ 
- What are ports?
https://www.utilizewindows.com/list-of-common-network-port-numbers/
- What is DNS?
https://code.tutsplus.com/tutorials/an-introduction-to-learning-and-using-dns-records--cms-24704
- Intermediate Security Testing with Kali Linux 2
http://www.penguintutor.com/linux/basic-network-reference


## Programming Basics
Being a great programmer is not a requirement to be a successful hacker. However, having the ability to make an educated guess, may increase your chances of successfully identifying and exploiting an issue. In a number of cases, you may need to automate your work or know more than just the “basics” in order to escalate a bug with a medium severity to high/critical. 

- HTML: HTML is very easy to learn and there are a ton of free resources for it. If you are interested in learning about XSS this should be your first step.
If you prefer an interactive tool to learn about Javascript, I highly recommend Codecademy!
https://www.codecademy.com/learn/learn-html
https://www.w3schools.com/html/

- JavaScript: Once you have familiarized yourself with HTML, you should understand Javascript since you will be using it to exploit XSS vulnerabilities. The usage of Javascript isn’t just limited to when you are exploring XSS, so it’s a very handy programming language to know.
If you prefer an interactive tool to learn about Javascript, I highly recommend Codecademy! https://www.codecademy.com/learn/introduction-to-javascript 

- SQL: You may have guessed It already, but you won’t be able to exploit complex SQL injection vulnerabilities before having any SQL knowledge. 
As always, if you prefer an interactive course, feel free to use Codecademy! 
https://www.codecademy.com/learn/learn-sql
http://www.sqlcourse.com/ 

### Automation 
You are welcome to skip this section if you think you’ll never need any automation or in depth web application knowledge. However I think learning bash in addition to one the following four languages may help you work smarter rather than harder.
- Bash
https://www.learnshell.org/ 
- Ruby
https://www.learnrubyonline.org/
- Python
https://docs.python.org/3/tutorial/
- Additional Resources:
   - https://www.codecademy.com/learn/paths/web-development
   - https://docs.python.org/3/tutorial/
   - http://www.sqlcourse.com/
   - https://en.wikibooks.org/wiki/Programming_Fundamentals/Advanced_Flowcharting

## Misc
- Setting up your own web server on a VPS
https://www.linux.com/learn/easy-lamp-server-installation
- Setting up virtualbox + linux
https://linuxconfig.org/how-to-install-kali-linux-on-virtualbox
- Basics of UNIX
https://lifehacker.com/5633909/who-needs-a-mouse-learn-to-use-the-command-line-for-almost-anything
- Setting up Burp
https://www.hacker101.com/playlists/burp_suite
- Previously Disclosed Vulnerabilities 
https://hackerone.com/hacktivity

## Vulnerability Types
Need a description here 

### Cross-Site Scripting XSS
As we start to build this repository, we'll be adding more vulnerability types and resources for each one. XSS is a great place to start as it's one of the most popular and easiest vulnerabilities to find in a web application. 


- Hacker101
https://www.hacker101.com/sessions/xss
- OWASP 
https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)
- A comprehensive tutorial on cross-site scripting
https://excess-xss.com
- Google Application Security (XSS Guide)
https://www.google.com/intl/am_AD/about/appsecurity/learning/xss/




#### Hands on material 
- XSS-Game
https://xss-game.appspot.com 
- Hacker101
https://hacker101.com
- PentesterLab
https://pentesterlab.com
- HackEdu
https://hackedu.io
- DWVA
http://www.dvwa.co.uk
- Google Gruyere
https://google-gruyere.appspot.com/
- Web Security Academy by PortSwigger. 
https://portswigger.net/web-security

#### Blog posts
You can find a ton of awesome XSS reports by searching through the HackerOne Hacktivity Page (https://hackerone.com/hacktivity?querystring=XSS). Here are some more complex and some of my favorite XSS related blog posts:

##### DOM XSS
https://hackerone.com/reports/297968
https://hackerone.com/reports/168165
https://www.rafaybaloch.com/2017/06/a-tale-of-dom-based-xss-in-paypal.html
##### Stored XSS
https://blog.bentkowski.info/2018/09/another-xss-in-google-colaboratory.html
https://medium.com/@Alra3ees/google-adwords-3133-7-stored-xss-27bb083b8d27
https://opnsec.com/2018/03/stored-xss-on-facebook/
https://klikki.fi/adv/yahoo.html
https://klikki.fi/adv/yahoo2.html
https://hackerone.com/reports/422043
https://sites.google.com/site/bughunteruniversity/best-reports/account-recovery-xss
##### CSP Bypass
https://blog.bentkowski.info/2018/06/xss-in-google-colaboratory-csp-bypass.html


