# Web Application Security Testing Methodology/Checklist

### Information Gathering
+ Spiders, Robots and Crawlers
+ Search Engine Discovery/Reconnaissance
+ Full, Un-masked Account Numbers Displayed
+ Identify application entry points
+ Testing for Web Application Fingerprint
+ Internal IP Disclosure Pattern Found
+ Application Discovery
+ Analysis of Error Codes

### Configuration Management Testing
+ Testing for File Extensions Handling - File extensions handling
+ IIS localstart.asp Possible Brute Force
+ IIS "Persistent-Auth" enabled
+ Password fields with autocomplete enabled
+ Apache "Request Method" XSS
+ Apache server-status enabled
+ Apache server-info enabled
+ Apache server-info enabled
+ Old, backup and unreferenced files - Old, backup and unreferenced files
+ Possible Server Path Disclosure Pattern Found/ASP.NET Custom Error Path Disclosure
+ Infrastructure and Application Admin Interfaces - Access to Admin interfaces
+ Testing for HTTP Methods

### Authentication Testing
+ Credentials transport over an encrypted channel
+ Testing for user enumeration - User enumeration
+ Testing for Guessable (Dictionary) User Account - Guessable user account
+ Insecure Credential Storage on the Client
+ Missing "logout" function
+ HTTP Basic Authentication Enabled
+ Brute Force Testing - Credentials Brute forcing
+ Testing for bypassing authentication schema - Bypassing authentication schema
+ Testing for vulnerable remember password and pwd reset - Vulnerable remember password, weak pwd reset
+ Testing for Logout and Browser Cache Management - - Logout function not properly implemented, browser cache weakness
+ Testing for CAPTCHA - Weak Captcha implementation

### Session Management

+ Testing for Session Management Schema - Bypassing Session Management Schema, Weak Session Token
+ Unencrypted __VIEWSTATE Parameter
+ Session Hijacking
+ Unsigned __VIEWSTATE Parameter
+ Client-Side (JavaScript) Cookie References
+ Testing for Cookies attributes - Cookies are set not ‘HTTP Only’, ‘Secure’, and no time validity
+ Testing for Session Fixation - Session Fixation
+ Idle Session timeout too long
+ Concurrent Login with Single Account
+ Session Replay
+ Improper Session Termination
+ Testing for Exposed Session Variables - Exposed sensitive session variables
+ Testing for CSRF - CSRF

### Authorization Testing
+ Testing for Path Traversal - Path Traversal
+ Testing for bypassing authorization schema - Bypassing authorization schema
+ Testing for Privilege Escalation - Privilege Escalation

### Data Validation Testing
+ Testing for Reflected Cross Site Scripting - Reflected XSS
+ Testing for DOM based Cross Site Scripting - DOM XSS
+ Testing for Stored Cross Site Scripting - Stored XSS
+ Frame Injection
+ Cross Site Tracing (XST)
+ Link Injection
+ Cross site framing
+ Testing for Cross Site Flashing - Cross Site Flashing
+ SQL Injection - SQL Injection
+ LDAP Injection - LDAP Injection
+ ORM Injection - ORM Injection
+ Content Type Incorrectly Stated
+ UI Redress (Clickjacking)
+ XML Injection - XML Injection
+ XML eXternal Entity (XXE) attacks
+ SSI Injection - SSI Injection
+ XPath Injection - XPath Injection
+ IMAP/SMTP Injection - IMAP/SMTP Injection
+ Code Injection - Code Injection
+ OS Commanding - OS Commanding
+ Buffer overflow - Buffer overflow
+ Incubated vulnerability - Incubated vulnerability
+ Potential File Upload
+ Unvalidated Redirects and Forwards
+ Cross Origin Resource Sharing (CORS)
+ Testing for HTTP Smuglling

### Denial  of Service Testing
+ Testing for DoS Buffer Overflows - Buffer Overflows
+ User Specified Object Allocation - User Specified Object Allocation
+ Unvalidate Redirects and forwards
+ Denial of Service by XML Bomb
+ User Input as a Loop Counter - User Input as a Loop Counter
+ Writing User Provided Data to Disk - Writing User Provided Data to Disk
+ Failure to Release Resources - Failure to Release Resources
+ Storing too Much Data in Session - Storing too Much Data in Session

### Ajax Testing
+ AJAX Testing - AJAX weakness

### Weak password policy
+ Password policy Test

### SSL Testing
+ SSL Certificate Domain Name Mismatch
+ Weak SSL Ciphers supported or SSL Not Enforced
+ SSL compression supported
+ HTTP Strict Transport Security (HSTS)
+ Web Server accepts SSL 2.0 connections
+ SSL Renegotiation Enabled
+ SSL Certificate Not Signed by Trusted CA


























