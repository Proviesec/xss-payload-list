# xss-payload-list
[![License](https://img.shields.io/badge/license-MIT-_red.svg)](https://opensource.org/licenses/MIT)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/Proviesec/xss-payload-list/issues)
<img src="https://img.shields.io/github/stars/Proviesec/xss-payload-list?style=social"> <img src="https://img.shields.io/github/forks/Proviesec/xss-payload-list?style=social">
<a href="https://proviesec.org/">
    <img src="https://avatars.githubusercontent.com/u/92156402?s=400&u=7fe0dbb9085a37818ee8c2b061432a9a69cbff42&v=4" alt="Proviesec logo" title="Proviesec" align="right" height="60" />
</a>
[![Twitter](https://img.shields.io/twitter/follow/proviesec?label=Follow)](https://twitter.com/proviesec)
<a href="https://www.buymeacoffee.com/proviesec" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

# Introduction 

:star: Star us on GitHub — it motivates a lot! :star:

If you have any XSS payload, just create a PullRequest. 

# Write-Ups / Tutorials
https://portswigger.net/web-security/cross-site-scripting/cheat-sheet
https://medium.com/p/92ac1180e0d0
https://book.hacktricks.xyz/pentesting-web/xss-cross-site-scripting

# My love polyglot
```
jaVasCript:/*--></title></style></textarea></script></xmp><svg/onload='+/"/+/onmouseover=1/+/[*/[]/+alert(1)//'>
"'alert(1)
```


# Todos 

- [ ] XSS payloads for url fields
- [x] XSS payloads for onfocus
- [x] XSS payloads for title
- [x] XSS payloads without alert
- [ ] XSS payloads for base64
- [ ] XSS payloads without script tag
- [ ] XSS payloads for javascript fields
- [ ] XSS payloads for number fields
- [ ] XSS payloads for a href
- [x] XSS payloads for markdown 
- [ ] XSS for anker 
- [ ] XSS for open-redirect
- [ ] cloudflare bypass 



# File Descriptions


- XSS-polyglot.txt
A JavaScript Polyglot is a Cross Site Scripting (XSS) vector that is executable within various injection contexts in its raw form, or a piece of code that can be executed in multiple contexts in the application.

# Rules

Rules To Find XSS

1: injecting haramless HTML
<a>,<u>

2: injecting HTML Entities

&lt;b&gt;
\u003b\u00

3 :injecting Script Tag
    
4: Testing For Recursive Filters
    
5: injecting Anchor Tag
    
6: Testing For Event Handlers
    
7: Input Less Common Event Handlers
    
8: Testing With SRC Attrubute
    
9: Testing With Action Attrubute
    
10: Injecting HTML 5 Based Payload

    

## Reports 

- https://hackerone.com/reports/1342009 
- https://hackerone.com/reports/1416672 
- https://hackerone.com/reports/1527284 
- https://hackerone.com/reports/1683129 
- https://hackerone.com/reports/834071 

# Disclaimer: DONT BE A JERK! 
Needless to mention, please use this tool very very carefully. The authors won't be responsible for any consequences.
 
