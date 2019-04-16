he starts with passive recon

goes through the website to gather info

using DHCP

using kali

making sure kali is running

ip address 192.168.110.140

kqli ip address 192.168.110.132 uses nmap

netmask 255.255.255.0

using grep to go through the curcuit boards

command- sudogrep -R "DHCP" \var\log\*

ruled out him and the DHCP server

opens zenmap and uses intense scan 

operating system is openbsd

name of the machine- the necromancer 

1 port open - port 666 it is a udp port run by doom 

nc -u 192.168.110.140 666

open wireshark to see what is going on in the network

sample the network to see what kind of traffic is going on 

src port 4444

he found the flag - format flag

uses wireshark to look at packets between the 2 machines 

probe, penetrate, profit

recon, gain access, get data, 

