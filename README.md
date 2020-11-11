# Discord-Webhook-DDoS-Detection V2

This is the second version of the (D)dos Alert [Shell FIle](https://github.com/KimYoJong/DDoS-Detection-DiscordWebhook).

All in one file

# Screenshots
![](https://i.vexy.pro/wgBnbh.png)

A example of the Alert Script once a DDoS attack is registered.

![enter image description here](https://i.vexy.pro/EvWnb5.png)

A example of a attack stopped / mitigated

## Editing

Edit [attacklog.sh](https://github.com/KimYoJong/Discord-Webhook-DDoS-Detection-V2/blob/main/attacklog.sh)


## Setup

mkdir tcpdump

iptables -A FORWARD -i tun0 -o eth0 -j ACCEPT

sudo apt-get update && sudo apt-get upgrade

sudo apt-get install tcpdump

sudo apt-get install dos2unix

sudo apt-get install curl

sudo apt-get install screen

chmod 777 *

screen

dos2unix attacklog.sh

bash attacklog.sh

## Contact

For help, Contact me on [Twitter](https://twitter.com/Dogeiana) or join my [Discord](https://discord.com/invite/4DSSbzS)
