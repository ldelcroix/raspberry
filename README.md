# raspberry

https://www.raspberrypi.org/documentation/installation/installing-images/linux.md

```
df -h
# plug
df -h
umount /dev/mmcblk0p1
sudo dd bs=4M if=raspbian-jessie.img of=/dev/mmcblk0
sync
```

#network
remove eth0 from /etc/network/interfaces to enable dhcp
