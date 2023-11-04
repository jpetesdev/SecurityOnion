# SecurityOnion
Home SecurityOnion IDS/IPS 
Documenation: https://docs.securityonion.net/en/2.4/


What is SecurityOnion?

Security Onion is a host and network based intrustion detection/prevention solution that includes log management and analysis. 
It can either be a physical device in your network or it can be a virtual machine. 

How does Security Onion work (in a nutshell)?

The SO must be able to collect your network traffic via a SPAN or Mirror port on a switch. 
That traffic is ingested by your SO and you can then use the built in dashboard, events, and Kibana platform to investigate.

**********************
What will you learn?
**********************
1. Network Topologies
2. Intrusion Detection / Intrustion Prevention
3. Log analysis (Elastic Stack)

*****************************************************
What do you need to get started with Security Onion?
*****************************************************
1. A home internet connection. (This should be a given, but leaven no stone unturned)
2. A managed switch.
   I'm a CISCO Stan so I have a used Cisco Catalyst 2960 with 52 ports.
   You can by a used one for less than $50 off of eBay. Just make sure you also get a console cable for first time setup.
   If you don't have a networking background with CISCO, you can get any other kind of managed switch and use the web GUI like a noob.
   One of the switch interfaces must be set as a SPAN/Mirror port so that it can collect the live traffic.

3. Hardware for the Security Onion itself.
   This can be virtualized, however, that is not how I completed my project. I repurposed an old PC.
   Hardware Requirements: https://docs.securityonion.net/en/2.4/hardware.html
   The critical thing is that your device needs to have two NICs: One for your standard network connection and the other as a log collection

4. USB for Security Onion Image
   SO Image: https://github.com/Security-Onion-Solutions/securityonion/blob/2.4/main/DOWNLOAD_AND_VERIFY_ISO.md
   You will make a bootable flash with the ISO just like any other OS you are trying to boot.

5. Ethernet Cables



