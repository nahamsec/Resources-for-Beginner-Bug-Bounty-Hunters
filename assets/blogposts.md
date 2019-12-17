# Resources-for-Beginner-Bug-Bounty-Hunters

## Blog posts
A collection of Blog Posts ordered by Vulnerability Types
- [XSS](#XSS)
    - [DOM XSS](#DOM-XSS)
    - [Sored XSS](#Stored-XSS)
    - [CSP Bypass](#CSP-Bypass)
- [SSRF](#SSRF)
- [Vulnerability Scanning](#Vulnerability-Scanning)
- [Token / Authentication](#Token-/-Authentication)
- [SQL Injection](#SQL-Injection)
- [Mobile](#Mobile)
    - [iOS](#iOS)
    - [Android](#Android)
- [HTTP Desync](#HTTP-Desync)
- [File Upload](#File-Upload)
- [Automation](#Automation)
- [Misc](#Misc)
## XSS
You can find a ton of awesome XSS reports by searching through the HackerOne Hacktivity Page (https://hackerone.com/hacktivity?querystring=XSS). Here are some more complex and some of my favorite XSS related blog posts:

- [XSS on Google Search - Sanitizing HTML in The Client?](https://www.youtube.com/watch?v=lG7U3fuNw3A) - by LiveOverflow
    - [The Fix](https://github.com/google/closure-library/commit/c79ab48e8e962fee57e68739c00e16b9934c0ffa)

### DOM XSS
- https://hackerone.com/reports/297968
- https://hackerone.com/reports/168165
- https://www.rafaybaloch.com/2017/06/a-tale-of-dom-based-xss-in-paypal.html
### Stored XSS
- https://blog.bentkowski.info/2018/09/another-xss-in-google-colaboratory.html
- https://medium.com/@Alra3ees/google-adwords-3133-7-stored-xss-27bb083b8d27
- https://opnsec.com/2018/03/stored-xss-on-facebook/
- https://klikki.fi/adv/yahoo.html
- https://klikki.fi/adv/yahoo2.html
- https://hackerone.com/reports/422043
- https://sites.google.com/site/bughunteruniversity/best-reports/account-recovery-xss
### CSP Bypass
- https://blog.bentkowski.info/2018/06/xss-in-google-colaboratory-csp-bypass.html

## SSRF
- [DEF CON 27 Conference - Ben Sadeghipour - Owning The Clout Through Server Side Request Forgery](https://www.youtube.com/watch?v=o-tL9ULF0KI)<br>- Nahamsec & daeken | DEFCON 2019
- [Piercing The Veil: Server Side Request Forgery Attacks On Internal Networks](https://peertube.opencloud.lu/videos/watch/40f39bfe-6d3c-40f5-bcab-43f20944ca6a)<br>- Alyssa Herrera | Hack.lu 2019
- [Vimeo upload function SSRF](https://medium.com/@dPhoeniixx/vimeo-upload-function-ssrf-7466d8630437) - by Sayed Abdelhafiz


## Vulnerability Scanning
- [NMAP For Vulnerability Discovery](https://www.peerlyst.com/posts/nmap-for-vulnerability-discovery-sachin-wagh) - by Sachin Wagh

## Token / Authentication
- [Abusing feature to steal your tokens](https://medium.com/@rootxharsh_90844/abusing-feature-to-steal-your-tokens-f15f78cebf74) - by Harsh Jaiswal
- [How I was able to bypass OTP code requirement in Razer [The story of a critical bug]](https://medium.com/bugbountywriteup/how-i-was-able-to-bypass-otp-token-requirement-in-razer-the-story-of-a-critical-bug-fc63a94ad572?) - by Ananda Dhakal


## SQL Injection
- [Time-Based Blind SQL Injection In GraphQL](https://medium.com/bugbountywriteup/time-based-blind-sql-injection-in-graphql-39a25a1dfb3c) - Divyanshu Shukla
- [SQL Injection Extracts Starbucks Enterprise Accounting, Financial, Payroll Database](https://hackerone.com/reports/531051) - by spaceraccoon

## Mobile
### iOS
- [From checkra1n to Frida: iOS App Pentesting Quickstart on iOS 13](https://spaceraccoon.dev/from-checkra1n-to-frida-ios-app-pentesting-quickstart-on-ios-13) - by spaceraccoon
## Android
- [A deep dive into reversing Android pre-Installed apps](https://github.com/maddiestone/ConPresentations/blob/master/Blackhat2019.SecuringTheSystem.pdf) and the [BlackHat Talk](https://www.youtube.com/watch?v=U6qTcpCfuFc) - by Maddie Stone

## HTTP Desync
- [HTTP Desync Attacks: Request Smuggling Reborn](https://portswigger.net/research/http-desync-attacks-request-smuggling-reborn) in combination with this [report](https://hackerone.com/reports/510152) - by James Kettle
- [HTTP Request Smuggling on vpn.lob.com](https://hackerone.com/reports/694604) - by 0X0 (painreigns)

## File Upload
- [Webshell via File Upload on ecjobs.starbucks.com.cn](https://hackerone.com/reports/506646) - by johnstone

## Automation
- [Fasten your Recon process using Shell Scripting](https://medium.com/bugbountywriteup/fasten-your-recon-process-using-shell-scripting-359800905d2a) - by Mohd Shibli
- [Beginner’s Guide to recon automation](https://medium.com/bugbountywriteup/beginners-guide-to-recon-automation-f95b317c6dbb) - by Ashish Jha
- [Burp Suite tutorial: IDOR vulnerability automation using Autorize and AutoRepeater (bug bounty)](https://www.youtube.com/watch?v=3K1-a7dnA60) - by STÖK & Fisher

## Misc
- [Writing a Simple Buffer Overflow Exploit](https://www.youtube.com/watch?v=oS2O75H57qU) - by LiveOverflow

---
back to [Intro Page](/README.md)