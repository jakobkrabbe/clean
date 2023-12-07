# cleaning servers from files
```
sudo du -h /var/log
sudo ls -lh /var/log
```
# swapoff -a
```
https://www.tecmint.com/disable-swap-partition/
vertel@gluu20:/$ sudo swapoff -a 
vertel@gluu20:/$ sudo nano /etc/fstab 
vertel@gluu20:/$ sudo rm /swap.img 
```
