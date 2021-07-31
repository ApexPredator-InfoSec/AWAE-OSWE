# AWAE-OSWE
Review of AWAE.OSWE

The Offensive Security Advanced Web Attacks and Exploitation Course (AWAE) teaches students how to analyze web application source code to find vulnerabilities and to chain vulnerabilities together to bypass authentication and gain Remote Code Execution on target systems.

Topics include:
  1. Cross Site Scripting (XSS)
  2. Cross Site Request Forgery (CSRF)
  3. SQL Injection (SQLi)
  4. Blind Boolean Bassed SQLi
  5. Blind Time Based SQLi
  6. Insecure file uploads
  7. Server Side Template Injection (SSTI)
  8. XML External Entities (XXE)
  9. Insecure Deserialization
  10. OS Command Injection

Students learn how to find these vulnerabilities in web application source code and write custom exploits targeting the vulenrabilties. The course is well written and will teach a student with basic python skills and no web development experience everything they need to know to pass the exam.

Exam prep - 

I passed the exam on the 2nd attempt. However, I was more than prepared enough for the first attempt. I just had a bad couple of days and didn't put enough effort in to the exploitation to be successful. The methods I used to prepare were:


Started 90 lab access course  
Completed all modules and exercise to include all Extra Miles exercies.  
Completed the 3 unguided lab machines.  
Completed SourceCode1 from vulnhub https://www.vulnhub.com/entry/securecode-1,651/ (my solution can be found https://github.com/ApexPredator-InfoSec/securecode1/)  
Went thru all modules and exercies a 2nd time.  
Improved exercise exploits and Extra Mile solutions.  


2nd attempt prep  
Extended lab time 30 days.  
Ran thru 3 unguided lab machines again.  
Searched for additonal vulnerabilities in the 3 lab machines.  
Improved exploits for 3 lab machines.  
Found additonal vulnerabilities in ATutor not covered in course modules or Extra Miles and coded exploits for them.  
Completed order and tudo challenges from bmdyy's github https://github.com/bmdyy/ (my solutions can be found https://github.com/ApexPredator-InfoSec/).



I built a notes template to help keep track of findings on the exam machines that I used on both attempts. Feel free to use it if you feel it will help.

Machine Name:  
IP Add:  
Machine OS:  
Open Ports:  
Programming Language:  
Web root:  
Web config files:  
Web logs:  
Admin interface:  
Websockets:  
Dirb/gobuster results:  
Nikto results:  
Database:  
	• Version:  
	• Creds:  
	• Stacked queries:  
	• UDF:  
	• Copy to:  
	• Execute shell commands:  
	• User/password tables:  
	• Logging:  
Authentication method:  
	• Hashing/salted or in clear:  
	• Session cookies/tokens:  
	• Password resets:  
	• How are users created:  
	• Difference between admin and non-admin:  
	• Predictable token generation:  
	• Type Juggling:  
	• SQLi in login methods:  
	• Cookies encoded or serialized:  
	• Difference between authenticated and unauthenticated pages:  
	• Anything interesting when accessing nonexistent page:  
SQLi in code:  
	• User controlled parameters:  
	• Sanitization:  
	• Escapable quotes:  
	• Enumeration or run code:  
File uploads:  
	• Blacklists:  
	• Mime type:  
	• Where are files stored:  
Serialization:  
	• Anything serialized or deserialized after authentication:  
	• Cookies:  
	• Files:  
	• JSON:  
	• Pickle:  
	• Base64 encoded:  
Code injection:  
	• User controlled parameters:  
	• Ability to inject PHP, JS, etc:  
XXE:  
	• Is XML being used:  
	• User controlled parameters:  
	• Local entities:  
	• External Entities:  
	• Disclose known files (/etc/passwd, C:\windows\win.ini):  
	• RCE capable:  
SSTI:  
	• Template version:  
	• Test {{7*7}}, = 7*7  
	• Blacklists:  
	• Run code:  
XSS:  
	• Injectable fields:  
	• Alert box:  
	• Steal cookie:  
	• CSRF:  

Vulnerabilities discovered:  
	• Type:  
	• PoC:  
Reverse Shell:  
	• Bash:  
	• nodeJS:  
	• PHP:  
	• Powershell:  
	• Msfvenom:  

