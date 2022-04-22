# forti-admin-baseline
config sys admin
edit admin
set trusthost1 192.168.1.0 255.255.255.0
set trusthost2 127.0.0.2 255.255.255.255
set trusthost3 127.0.0.3 255.255.255.255
set trusthost4 127.0.0.4 255.255.255.255
set trusthost5 127.0.0.5 255.255.255.255
set trusthost6 127.0.0.6 255.255.255.255
#set ssh-public-key1 "ssh-rsa KEY HERE"
next

edit "userid_here"
set trusthost1 192.168.1.0 255.255.255.0
set trusthost2 127.0.0.2 255.255.255.255
set trusthost3 127.0.0.3 255.255.255.255
set trusthost4 127.0.0.4 255.255.255.255
set trusthost5 127.0.0.5 255.255.255.255
set trusthost6 127.0.0.6 255.255.255.255
set accprofile "super_admin"
#set password "PASSWORD_HERE"
next
