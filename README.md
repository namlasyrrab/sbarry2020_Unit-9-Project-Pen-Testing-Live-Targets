# sbarry2020_Unit-9-Project-Pen-Testing-Live-Targets
Unit 9 Project: Pen Testing Live Targets
# Pen Testing Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: __________________

Description:

<img src="blue-vuln1.gif">


## Green

Vulnerability #1: Script Injection XXS

Description: A attacker can use the feedback form to inject a script, by simply using ```<script> "Salman has inserted a script" </script>```, once an admin clicks on the feedback form the script will be activated.

<img src="green_exploit.gif">

Vulnerability #2: User Enumaration

Description: When the user name is correct the "log in is unsucessfull" messege is bolded and when the user doesnt exist it is plain text, the creator of the site forgot to use the same fomrat for both possibilities

<img src="green_exploit2_user_e.gif ">


## Red

Vulnerability #1: __________________

Description:

<img src="red-vuln1.gif">


## Notes

Describe any challenges encountered while doing the work
