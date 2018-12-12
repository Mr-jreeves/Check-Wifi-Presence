# Check-Wifi-Presence
Python Script to monitor arp for a set of IP addresses and send changes to Smartthings

Once you have installed and configured the script for the IP addresses you want to monitor, you can add a line to your /etc/rc.local to start this script and keep it up permenantly.

Assuming you have the script in your home directory:
nohup python /home/pi/scan_wifi.py &

Depending on your router configuration, your IP addresses might change from time to time, so you may want to hard-code the IP addresses for each phone device.

A standard raspberry install will probably not contain all the imports that you need. You can google how to install those :-)

