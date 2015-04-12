Installation of raspbian:

https://www.raspberrypi.org/documentation/installation/installing-images/
https://www.raspberrypi.org/documentation/installation/installing-images/mac.md

IMG: http://downloads.raspberrypi.org/raspbian_latest
CMDs:
diskutil list
diskutil unmountDisk /dev/disk2
sudo dd bs=1m if=2015-02-16-raspbian-wheezy.img of=/dev/disk2

Check for IP: nmap -sP 192.168.1.0/24
ssh pi@192.168.1.127      //pwd:raspberry
