---
layout: default
title: Login
parent: WEXAC
nav_order: 2
---
# Login
Read [WEXAC hands on workshop][WEXAC PDF] slide 16-27

{: .warning}
You need to be connected to the network (VPN or Ethernet) for the connection to WEXAC to work
## Windows
Slides 16-22
{: .note}
TBD
## MAC
Slide 27
{: .note}
TBD
## LINUX
Using ssh from the terminal  
```
ssh username@accessN.wexac.weizmann.ac.il
username - your weizmann username (used to login to the email)  
accessN - login nodes, 1-4 (access1, access2, etc.)  
  
ssh ukleiner@access3.wexac.weizmann.ac.il
```  
you can add an alias to your .bashrc   
``` 
# In ~/.bashrc
alias wexac='ssh username@access2.wexac.weizmann.ac.il 
# In terminal
. ~/.bashrc
```

---

[WEXAC PDF]: ../../assets/pdf/wexac_introduction.pdf
