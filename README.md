# Methodology

## Web Application Security Testing Methodology/Checklist

Category	Test Name	Vulnerability
Information Gathering	Spiders, Robots and Crawlers	N.A.
	Search Engine Discovery/Reconnaissance	N.A.
	Full, Un-masked Account Numbers Displayed	Full, Un-masked Account Numbers Displayed
	Identify application entry points	N.A.
	Testing for Web Application Fingerprint	N.A.
	Internal IP Disclosure Pattern Found	Internal IP Disclosure Pattern Found
	Application Discovery	N.A.
	Analysis of Error Codes	Information Disclosure
Configuration Management Testing	Testing for File Extensions Handling - File extensions handling	File extensions handling
	IIS localstart.asp Possible Brute Force	IIS localstart.asp Possible Brute Force
	IIS "Persistent-Auth" enabled	IIS "Persistent-Auth" enabled
	Password fields with autocomplete enabled	Password fields with autocomplete enabled
	Apache "Request Method" XSS	Apache "Request Method" XSS
	Apache server-status enabled	Apache server-status enabled
	Apache server-info enabled	Apache server-info enabled
	Apache server-info enabled	Microsoft ASP.NET Debugging Enabled
	Old, backup and unreferenced files - Old, backup and unreferenced files	Old, backup and unreferenced files
	Possible Server Path Disclosure Pattern Found/ASP.NET Custom Error Path Disclosure	Possible Server Path Disclosure Pattern Found/ASP.NET Custom Error Path Disclosure
	Infrastructure and Application Admin Interfaces - Access to Admin interfaces	Access to Admin interfaces
	Testing for HTTP Methods	HTTP Methods enabled
Authentication Testing	Credentials transport over an encrypted channel	Credentials transport over an encrypted channel
	Testing for user enumeration - User enumeration	User enumeration
	Testing for Guessable (Dictionary) User Account - Guessable user account	Guessable user account
	Insecure Credential Storage on the Client	Insecure Credential Storage on the Client
	Missing "logout" function	Missing "logout" function
	HTTP Basic Authentication Enabled	HTTP Basic Authentication Enabled
	Brute Force Testing - Credentials Brute forcing	Credentials Brute forcing
	Testing for bypassing authentication schema - Bypassing authentication schema	Bypassing authentication schema
	Testing for vulnerable remember password and pwd reset - Vulnerable remember password, weak pwd reset	Vulnerable remember password, weak pwd reset
	Testing for Logout and Browser Cache Management - - Logout function not properly implemented, browser cache weakness	Logout function not properly implemented, browser cache weakness
	Testing for CAPTCHA - Weak Captcha implementation	Weak Captcha implementation
Session Management	Testing for Session Management Schema - Bypassing Session Management Schema, Weak Session Token	Bypassing Session Management Schema, Weak Session Token
	Unencrypted __VIEWSTATE Parameter	Unencrypted __VIEWSTATE Parameter
	Session Hijacking	Session Hijacking
	Unsigned __VIEWSTATE Parameter	Unsigned __VIEWSTATE Parameter
	Client-Side (JavaScript) Cookie References	Client-Side (JavaScript) Cookie References
	Testing for Cookies attributes - Cookies are set not ‘HTTP Only’, ‘Secure’, and no time validity	Cookies are set not ‘HTTP Only’, ‘Secure’, and no time validity
	Testing for Session Fixation - Session Fixation	Session Fixation
	Idle Session timeout too long	Idle Session timeout too long
	Concurrent Login with Single Account	Concurrent Login with Single Account
	Session Replay	Session Replay
	Improper Session Termination	Improper Session Termination
	Testing for Exposed Session Variables - Exposed sensitive session variables	Exposed sensitive session variables
	Testing for CSRF - CSRF	CSRF
Authorization Testing	Testing for Path Traversal - Path Traversal	Path Traversal
	Testing for bypassing authorization schema - Bypassing authorization schema	Bypassing authorization schema
	Testing for Privilege Escalation - Privilege Escalation	Privilege Escalation
Data Validation Testing	Testing for Reflected Cross Site Scripting - Reflected XSS	Reflected XSS
	Testing for DOM based Cross Site Scripting - DOM XSS	DOM XSS
	Testing for Stored Cross Site Scripting - Stored XSS	Stored XSS
	Frame Injection	Frame Injection
	Cross Site Tracing (XST)	TRACE simply returns any string that is sent to the web server.
	Link Injection	Link Injection
	Cross site framing	Cross site framing
	Testing for Cross Site Flashing - Cross Site Flashing	Cross Site Flashing
	SQL Injection - SQL Injection	SQL Injection 
	LDAP Injection - LDAP Injection	LDAP Injection
	ORM Injection - ORM Injection	ORM Injection
	Content Type Incorrectly Stated	Content Type Incorrectly Stated
	UI Redress (Clickjacking)	UI Redress (Clickjacking)
	XML Injection - XML Injection	XML Injection
	XML eXternal Entity (XXE) attacks	XXE attacks
	SSI Injection - SSI Injection	SSI Injection
	XPath Injection - XPath Injection	XPath Injection
	IMAP/SMTP Injection - IMAP/SMTP Injection	IMAP/SMTP Injection
	Code Injection - Code Injection	Code Injection
	OS Commanding - OS Commanding	OS Commanding
	Buffer overflow - Buffer overflow	Buffer overflow
	Incubated vulnerability - Incubated vulnerability	Incubated vulnerability
	Potential File Upload	Vulnerable File Upload
	Unvalidated Redirects and Forwards	Unvalidated Redirects and Forwards
	Cross Origin Resource Sharing (CORS)	OVERLY PERMISSIVE CROSSDOMAIN POLICY
	Testing for HTTP Smuglling	HTTP Smugling
Denial of Service Testing	Testing for DoS Buffer Overflows - Buffer Overflows	Buffer Overflows
	User Specified Object Allocation - User Specified Object Allocation	User Specified Object Allocation
	Unvalidate Redirects and forwards	Unvalidate Redirects and forwards
	Denial of Service by XML Bomb	Denial of Service by XML Bomb
	User Input as a Loop Counter - User Input as a Loop Counter	User Input as a Loop Counter
	Writing User Provided Data to Disk - Writing User Provided Data to Disk	Writing User Provided Data to Disk
	Failure to Release Resources - Failure to Release Resources	Failure to Release Resources
	Storing too Much Data in Session - Storing too Much Data in Session	Storing too Much Data in Session
Ajax Testing	AJAX Testing - AJAX weakness	AJAX weakness
Weak password policy	Password Policy Test	Weak password policy
SSL Testing	SSL Certificate Domain Name Mismatch	SSL Certificate Domain Name Mismatch
	"Weak SSL Ciphers supported
or
SSL Not Enforced"	"Weak SSL Ciphers supported
or
SSL Not Enforced"
	SSL compression supported	CRIME (Compression Ratio Info-leak Made Easy)
	HTTP Strict Transport Security (HSTS)	Missing HTTP Strict Transport Security (HSTS) header
	"Web Server accepts SSL 2.0 connections
"	"Web Server accepts SSL 2.0 connections
"
	SSL Renegotiation Enabled	SSL Renegotiation Enabled
	SSL Certificate Not Signed by Trusted CA	SSL Certificate Not Signed by Trusted CA

