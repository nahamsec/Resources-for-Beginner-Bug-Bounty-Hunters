# Resources-for-Beginner-Bug-Bounty-Hunters

## Table of Contents
1. [HTTP basics](#HTTP-basics)
2. [Networking basics](#Networking-basics)
3. [Programming Basics](#Programming-Basics)
4. [Automation](#Automation)

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
- [Network Fundamentals](https://www.youtube.com/playlist?list=PLDQaRcbiSnqF5U8ffMgZzS7fq1rHUI3Q8), A 19 part Video Series about Networking well explained for Beginners


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

## Automation 
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


---
back to [Intro Page](/README.md)