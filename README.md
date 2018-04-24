# Armv7_Cortex-A53
Trench Captive Portal For Armv7 Architecture and Cortex-A53 CPU
Dependencies
---->1) openSSL 1.1.0e or above
---->2) CC=arm-linux-gcc
---->3) Modify with the location of openSSL include and lib path in src/Makefile.am
---->4) ./configure
---->5) make CC=<arm-linux-gcc path>/arm-linux-gcc clan all
---->6) make dist

Trench is Captive portal which requires Two interface 1) WiFi lan interface which Trench will 
        control the ip assignment to its captive portal subscriber and 2) WAN interface for Internet Acces.
Trench creates the tunnet between WiFi and WAN and redirect incoming internet request to UAM for authorization. The Authorization 
would be based on any of the following.
1)Social Media
  1) G-Mail loging
  2) Facebook
  3) Twitter
  
2)Self Registration of User
3) Aadhaar (UID) Registration
