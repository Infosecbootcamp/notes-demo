Make sure you have Templater installed and have the /templates folder set in settings.


Under the /templates folder create a note for all your commands:
```
gobuster dir -u http://<% tp.frontmatter["Target IP"] %> -w /usr/share/wordlists/dirb/common.txt
```
Under the HTB/OSCP/ETC Folder create a note for your box to complete:

At the very top of the page
```
---
Target IP :
---
```
Then simply run the template on your new note!
