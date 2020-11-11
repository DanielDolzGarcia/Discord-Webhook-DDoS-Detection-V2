# Discord-Webhook-DDoS-Detection V2
﻿# (D)Dos Alert Script

This is the second version of the (D)dos Alert [Shell FIle](https://github.com/KimYoJong/DDoS-Detection-DiscordWebhook).



# Screenshots
![](https://i.vexy.pro/wgBnbh.png)

A example of the Alert Script once a DDoS attack is registered.

![enter image description here](https://i.vexy.pro/EvWnb5.png)

A example of a attack stopped / mitigated


## Installation

This works on all Ubuntu and Debain versions

iptables -A FORWARD -i tun0 -o eth0 -j ACCEPT

sudo apt-get install tcpdump

sudo apt-get install dos2unix

sudo apt-get install curl

sudo apt-get install screen

chmod 777 *

screen

dos2unix attacklog.sh

bash attacklog.sh
