# Discord-Webhook-DDoS-Detection V2

This is the second version of the (D)dos Alert [Shell FIle](https://github.com/KimYoJong/DDoS-Detection-DiscordWebhook).

All in one file

# Screenshots

i got none =(


## Editing

Edit [attacklog.sh](https://github.com/KimYoJong/Discord-Webhook-DDoS-Detection-V2/blob/main/attacklog.sh)


## Setup

mkdir tcpdump

iptables -A FORWARD -i tun0 -o eth0 -j ACCEPT

sudo apt-get update && sudo apt-get upgrade -y

sudo apt-get install tcpdump -y

sudo apt-get install dos2unix -y

sudo apt-get install curl -y

sudo apt-get install screen -y

chmod +x attacklog.sh

dos2unix attacklog.sh

screeb bash attacklog.sh

## Contact

For help, add me on disord DD is back#0091
