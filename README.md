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
Built full chain exploits for modules that did not cover a full chian exploit.  
Automated HSQLDB exploit path from module 9.  


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
	<ul><li>Version:</li>
	<li>Creds:</li> 
	<li>Stacked queries:</li>
	<li>UDF:</li> 
	<li>Copy to:</li>
	<li>Execute shell commands:</li>
	<li>User/password tables:</li>
	<li>Logging:</li></ul>
Authentication method:
	<ul><li>Hashing/salted or in clear:</li>
	<li>Session cookies/tokens:</li>
	<li>Password resets:</li>
	<li>How are users created:</li>
	<li>Difference between admin and non-admin:</li>
	<li>Predictable token generation:</li>
	<li>Type Juggling:</li>
	<li>SQLi in login methods:</li>
	<li>Cookies encoded or serialized:</li>
	<li>Difference between authenticated and unauthenticated pages:</li>
	<li>Anything interesting when accessing nonexistent page:</li></ul>
SQLi in code:  
	<ul><li>User controlled parameters:</li>
	<li>Sanitization:</li> 
	<li>Escapable quotes:</li>
	<li>Enumeration or run code:</li></ul>
File uploads:  
	<ul><li>Blacklists:</li>
	<li>Mime type:</li>
	<li>Where are files stored:</li></ul>
Serialization:  
	<ul><li>Anything serialized or deserialized after authentication:</li>
	<li>Cookies:</li>
	<li>Files:</li>
	<li>JSON:</li>
	<li>Pickle:</li>
	<li>Base64 encoded:</li></ul>
Code injection:  
	<ul><li>User controlled parameters:</li>
	<li>Ability to inject PHP, JS, etc:</li></ul>
XXE:  
	<ul><li>Is XML being used:</li>
	<li>User controlled parameters:</li>
	<li>Local entities:</li>
	<li>External Entities:</li>
	<li>Disclose known files (/etc/passwd, C:\windows\win.ini):</li>
	<li>RCE capable:</li></ul>
SSTI:  
	<ul><li>Template version:</li>
	<li>Test {{7\*7}}, = 7\*7</li>
	<li>Blacklists:</li>
	<li>Run code:</li></ul>
XSS:  
	<ul><li>Injectable fields:</li>
	<li>Alert box:</li>
	<li>Steal cookie:</li>
	<li>CSRF:</li></ul>

Vulnerabilities discovered:  
	<ul><li>Type:</li>
	<li>PoC:</li></ul>
Reverse Shell:  
	<ul><li>Bash:</li>
	<li>nodeJS:</li>
	<li>PHP:</li>
	<li>Powershell:</li>
	<li>Msfvenom:</li></ul>
