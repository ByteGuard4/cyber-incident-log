\# Incident 001 - Brute Force Login Attempt



\## Incident Information



Incident ID: INC-001

Severity: Medium

Incident Type: Brute Force Attack

Target: Linux Server

Service: Secure Shell

Source IP: 192.168.1.100



\## Description



Multiple failed login attempts were detected against

the Secure Shell service of the Linux server.



The attacker attempted to authenticate using several

different usernames before successfully logging in

with the admin account.



\## Evidence



Failed login attempts:

\- root

\- admin

\- user



Successful login:

\- admin



Privilege escalation:

\- admin accessed root privileges using sudo



\## Analyst Assessment



The activity is suspicious and may indicate a

brute force attack followed by unauthorized access

and privilege escalation.



\## Recommended Action



1\. Investigate the source IP address.

2\. Review the admin account activity.

3\. Check Secure Shell authentication logs.

4\. Verify whether the admin account was compromised.

5\. Review commands executed with root privileges.

