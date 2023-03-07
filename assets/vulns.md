# Resources-for-Beginner-Bug-Bounty-Hunters

## Vulnerabilities 💉
This page is created to help hackers understand a specific vulnerability type in details. 

- If you would like to get some hands on experience by hacking more in detailed labs, please read the [labs](https://github.com/nahamsec/Resources-for-Beginner-Bug-Bounty-Hunters/assets/labs.md) page
- If you would like to read blog posts and see example vulnerability, please read the [blog posts](https://github.com/nahamsec/Resources-for-Beginner-Bug-Bounty-Hunters/assets/blogsposts.md) page

### Online Resources & Frameworks
- [Owasp Top 10](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project)
	- [TryHackMe's OWASP Top 10 Room](https://tryhackme.com/room/owasptop10)
	- [OWASP top 10 by Snyk](https://learn.snyk.io/learning-paths/owasp-top-10/javascript/)
- [OWASP Testing Guide v4](https://www.owasp.org/index.php/OWASP_Testing_Project)
- [Bug Bounty Cheat Sheets](https://github.com/EdOverflow/bugbounty-cheatsheet) - by EdOverflow
- [WebSecurity Academy by PortSwigger](https://portswigger.net/web-security/)
---

As we start to build this repository, we'll be adding more vulnerability types and resources for each one. 

## Cross-Site Scripting (XSS)
XSS is a great place to start as it's one of the most popular and easiest vulnerabilities to find in a web application.
### Reading Material
- [WebSec Academy - Cross-Site Scripting](https://portswigger.net/web-security/cross-site-scripting)
- [OWASP XSS](https://www.owasp.org/index.php/Cross-site_Scripting_(XSS))
- [XSS Filter Evasion Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/XSS_Filter_Evasion_Cheat_Sheet.html)
- [Cross-site scripting - Executing untrusted JavaScript in a trusted context](https://learn.snyk.io/lessons/xss/javascript/)
- [A comprehensive tutorial on cross-site scripting](https://excess-xss.com)
- [The 7 main XSS cases everyone should know](https://brutelogic.com.br/blog/the-7-main-xss-cases-everyone-should-know/) - [brutelogic](https://brutelogic.com.br/blog/about/)
### Video Content 
- [Cross-Site Scripting (XSS) Explained](https://www.youtube.com/watch?v=EoaDgUgS6QA) - by PwnFunction
- [Finding Your First Bug: Cross Site Scripting (XSS)](https://www.youtube.com/watch?v=IWbmP0Z-yQg) - by InsiderPhD
### Labs
- [WebSec Academy - Labs](https://portswigger.net/web-security/all-labs#cross-site-scripting)
- [xssLABS](https://www.xsslabs.com/)
- [Codelatte](https://codelatte.id/labs/xss/)
- [Google XSS Game](https://xss-game.appspot.com/)
- [Pwnfunction XSS](https://xss.pwnfunction.com/)

## Cross-Site Request Forgery (CSRF)
### Reading Material
- [WebSec Academy - CSRF](https://portswigger.net/web-security/csrf)
- [CSRF-Basics](https://princetechhavenz.wordpress.com/2019/12/11/csrf-basics/) - by Princethilak
- [Cross Site Request Forgery (CSRF) by Snyk](https://snyk.io/learn/csrf-cross-site-request-forgery/)
### Videos
- [Cross-Site Request Forgery Attack](https://www.youtube.com/watch?v=eWEgUcHPle0) - by PwnFunction
- [Finding Your First Bug: Cross-Site Request Forgery](https://www.youtube.com/watch?v=ULvf6N8AL2A) - by Insider PhD
- [Cross Site Request Forgery - Computerphile](https://www.youtube.com/watch?v=vRBihr41JTo)
### Labs
- [WebSec Academy - CSRF Labs]https://portswigger.net/web-security/all-labs)

## Insecure Direct Object Reference (IDOR)
### Reading Material
- [WebSec Academy - Insecure direct object references (IDOR) By PortSwigger](https://portswigger.net/web-security/access-control/idor)
- [Insecure Direct Object Reference (IDOR) by Intigriti](https://blog.intigriti.com/hackademy/idor/)
- [IDOR tutorial hands-on – OWASP Top 10 training](https://thehackerish.com/idor-tutorial-hands-on-owasp-top-10-training/)
### Videos
- [Insecure Direct Object Reference Vulnerability](https://www.youtube.com/watch?v=rloqMGcPMkI) - by PwnFunction
- [Finding Your First Bug: Manual IDOR Hunting](https://www.youtube.com/watch?v=gINAtzdccts) - by Insider PhD
- [Burp Suite tutorial: IDOR vulnerability automation using Autorize and AutoRepeater (bug bounty)](https://www.youtube.com/watch?v=3K1-a7dnA60) - by STÖK & Fisher
### Labs
- (WebSec Academy - IDOR Lab)[https://portswigger.net/web-security/access-control/lab-insecure-direct-object-references]
- (IDOR on TryHackMe)[https://tryhackme.com/room/idor]
- (Corridor on TryHackMe)[https://tryhackme.com/room/corridor]

## Server-Side Request Forgery
### Reading Material
- [WebSec Academy - Server-Side Request Forgery](https://portswigger.net/web-security/ssrf)
- [SSRF by OWASP](https://owasp.org/www-community/attacks/Server_Side_Request_Forgery)
- [What is server-side request forgery (SSRF)?](https://www.acunetix.com/blog/articles/server-side-request-forgery-vulnerability/)
- [Server-side request forgery - Unintended access to internal resources via exploited serve](https://learn.snyk.io/lessons/ssrf-server-side-request-forgery/javascript/)
- [SSRF vulnerabilities and where to find them](https://labs.detectify.com/2022/09/23/ssrf-vulns-and-where-to-find-them/)
### Videos
- (Find and Exploit Server-Side Request Forgery (SSRF))[https://www.youtube.com/watch?v=eVI0Ny5cZ2c]
- (Server-Side Request Forgery (SSRF) | Complete Guide)[https://www.youtube.com/watch?v=ih5R_c16bKc&t=1s]
- [SSRF in 100 seconds](https://www.youtube.com/watch?v=3dKavgfL2pA)
- [How To Search For SSRF!](https://www.youtube.com/watch?v=Ku6CK3Aes8Y)
- [How to exploit a blind SSRF?](https://www.youtube.com/watch?v=o6AJH9PFEd4)

### Labs
- [WebSec Academy - Server-Side Request Forgery Labs](https://portswigger.net/web-security/all-labs#server-side-request-forgery-ssrf)
- [WebSec Academy - Blind SSRF vulnerabilities](https://portswigger.net/web-security/ssrf/blind)
- [Server-Side Request Forgery (SSRF) vulnerable Lab](https://github.com/incredibleindishell/SSRF_Vulnerable_Lab)
- [Server-Side Request Forgery on TryHackMe](https://tryhackme.com/room/seasurfer)
## XML External Entities (XXE)
### Reading Material
- [WebSec Academy - XML External Entity (XXE) injection](https://portswigger.net/web-security/xxe)
- [XML External Entity (XXE) Processing by OWASP](https://owasp.org/www-community/vulnerabilities/XML_External_Entity_(XXE)_Processing)
- [How to Find XXE Bugs: Severe, Missed and Misunderstood by Luke Stephens](https://www.bugcrowd.com/blog/how-to-find-xxe-bugs/)
### Videos
- [XML External Entities ft. JohnHammond](https://www.youtube.com/watch?v=gjm6VHZa_8s) - by PwnFunction
- [How to search for XXE!](https://www.youtube.com/watch?v=0DQnWalxYb4)
- [How to run an XXE injection via an SVG Image Upload!](https://www.youtube.com/watch?v=lbLV0jISMjY)
### Labs
- [WebSec Academy - XML External Entity (XXE) Labs](https://portswigger.net/web-security/all-labs#xml-external-entity-xxe-injection)
- [XXE Lab (On GitHub)](https://github.com/jbarone/xxelab)

---
back to [Intro Page](/README.md)
