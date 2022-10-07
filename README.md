# cPanel-IP-whitelister
cPanel plugin for cPanel users to whitelist their own IP's


Installation:

1) Download all files to /root directory (wget https://github.com/gerhardniemand/cPanel-IP-whitelister/archive/master.zip)
2) unzip master && cd cPanel-IP-whitelister-master
3) run #> chmod +x ip_whitelist && ./ip_whitelist init


Whitelisting, and removing from the whitelist, is dependent on how your company handles this regularly, the whitelisting function in this script adds to the cphulk whitelis, and the remove whitelist function does nothing, you can add your own scripts in there if you wish to use ipsets/iptables.
