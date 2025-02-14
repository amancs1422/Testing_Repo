```
 lsblk
```
```
 df -h
```
```
vi test.txt
```
```
cp test.txt test1.txt
```
```
rm test.txt test1.txt test2.txt test3.txt test4.txt 
```
```
lsblk
```
```
mount /dev/xvdf1 /root/newvolume 
```
```
sudo lsblk –output NAME,TYPE,SIZE,FSTYPE,MOUNTPOINT,LABEL
```
```
mount /dev/xvdf1 /root/newvolume -t xfs 
```
```
dmesg | tail 
```
```
sudo mount -o nouuid /dev/xvdf1 /mnt/
```
```
cd /mnt/home/ec2-user/.
```
```
ls 
```
