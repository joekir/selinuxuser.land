---
layout: default
title: Protecting Shellcode-Eater web application
parent: Workshops
---

![shellcode_eater](https://raw.githubusercontent.com/joekir/selinux-workshop/master/shellcode_eater/img/shellcode-eater.png)

This is a workshop I prepared for an information security conference in 2018.    

The goal of the workshop is to protect an extremely vulnerable web application called "**Shellcode Eater**".    
Shellcode Eater (as you can see here in [main.c](https://github.com/joekir/selinux-workshop/blob/master/shellcode_eater/src/main.c)) is a website that takes raw bytes and executes them directly, thereby simulating a buffer-overwrite and instruction-pointer execution.

However this workshop is not about vulnerabilities, it's actually about the power of SELinux to defend even the most vulnerable of websites!
The participants of the workshop crafted an SELinux policy to defend the application from being used in unintended ways!

Take a look [https://github.com/joekir/selinux-workshop](https://github.com/joekir/selinux-workshop) and let me know [@josephkirwin](https://twitter.com/josephkirwin) on twitter if you have issues or improvements to suggest.
