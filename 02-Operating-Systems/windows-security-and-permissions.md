\# Windows Security and Permissions



This document covers core Windows security concepts related to user accounts,

permissions, and access control. These fundamentals are critical for

understanding endpoint security and Blue Team operations.



---



\## User Accounts in Windows



Windows uses user accounts to control access to system resources.



\### Types of Accounts

\- \*\*Standard User\*\*

&nbsp; - Limited permissions

&nbsp; - Cannot make system-wide changes

\- \*\*Administrator\*\*

&nbsp; - Full system access

&nbsp; - Can install software and change security settings

\- \*\*Built-in Administrator\*\*

&nbsp; - Disabled by default

&nbsp; - Targeted by attackers if enabled



Principle of Least Privilege should always be applied.



---



\## Authentication vs Authorization



\- \*\*Authentication\*\*: Verifying who the user is

&nbsp; - Username and password

&nbsp; - PIN

&nbsp; - Biometrics

\- \*\*Authorization\*\*: Determining what the user is allowed to do

&nbsp; - File access

&nbsp; - Application access

&nbsp; - System changes



A user can be authenticated but not authorized.



---



\## NTFS Permissions



NTFS permissions control access to files and folders.



\### Common Permissions

\- Read

\- Write

\- Modify

\- Full Control



Permissions are inherited by default but can be explicitly set.



Misconfigured NTFS permissions are a common security risk.



---



\## User Account Control (UAC)



UAC helps prevent unauthorized system changes by prompting for approval

when administrative actions are attempted.



\- Reduces malware impact

\- Prevents silent privilege escalation

\- Should not be disabled in secure environments



---



\## Local vs Microsoft Accounts



\- \*\*Local Account\*\*

&nbsp; - Exists only on one machine

&nbsp; - No cloud integration

\- \*\*Microsoft Account\*\*

&nbsp; - Syncs settings across devices

&nbsp; - Can introduce account takeover risk if compromised



Enterprise environments typically use centralized identity solutions.



---



\## Security Relevance for Blue Team



Understanding Windows permissions helps defenders:

\- Detect privilege escalation

\- Investigate unauthorized access

\- Identify misconfigured systems

\- Respond to compromised accounts



Endpoint security starts with correct permissions.



