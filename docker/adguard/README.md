### Installation
1. Remove stub listener on linux host
sudo nano /etc/systemd/resolved.conf
#uncomment DNSStubListener=yes & set the value to 'no'
sudo systemctl restart systemd-resolved

