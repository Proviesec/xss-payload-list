# xss-payload-list

<a href="https://proviesec.org/">
    <img src="https://avatars.githubusercontent.com/u/92156402?s=400&u=7fe0dbb9085a37818ee8c2b061432a9a69cbff42&v=4" alt="Proviesec logo" title="Proviesec" align="right" height="60" />
</a>
<a href="https://www.buymeacoffee.com/proviesec" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

# Introduction 

:star: Star us on GitHub — it motivates a lot! :star:

If you have any XSS payload, just create a PullRequest. 


# Write-Ups 
https://medium.com/p/92ac1180e0d0

# Todos 

- [ ] XSS payloads for url fields
- [ ] XSS payloads for number fields
- [ ] XSS payloads for a href

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
    
7 : Input Less Common Event Handlers
    
8: Testing With SRC Attrubute
    
9: Testing With Action Attrubute
    
10: Injecting HTML 5 Based Payload
    

# Reports 

- https://hackerone.com/reports/1342009 
- https://hackerone.com/reports/1416672 
