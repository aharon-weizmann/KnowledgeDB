---
layout: default
title: Connect to file system
parent: WEXAC
nav_order: 3
---
# Connect to file system
Read [WEXAC hands on workshop][WEXAC PDF] slide 16-27

{: .warning}
You need to be connected to the network (VPN or Ethernet) for the connection to WEXAC to work  
## Windows
Slides 21-22
{: .note}
## MAC
Slides 26-27
{: .note}
## LINUX
Slides 23-25  
{: .note}

If you don't see the left panel press F9  
If wismain doesn't work try WISMAIN  

Another option is to mount WEXAC to the file system and add a shortcut in _nautilus_  
1. Begin by creating the mount location (e.g. _/mnt/wexac_)  
2. use the following command   
```sudo mount -t cifs //data.wexac.weizmann.ac.il/ginossar /mnt/wexac -0 username=USER, domwin=WISMAIN```  
    1. Don't forget to change **USER** to your username  
    2. The command will prompt for your local password (for sudo) and then for your Weizmann login passowrd (for connecting to WEXAC).  
    3. I'm mapping our labs folder to mnt/wexac to avoid searching for it in the file navigator.
3. You can generate an alias (_fswex_ in this case) 
```alias fswex=sudo mount -t cifs //data.wexac.weizmann.ac.il/ginossar /mnt/wexac -0 username=USER, domwin=WISMAIN```

---

[WEXAC PDF]: ../../assets/pdf/wexac_introduction.pdf
