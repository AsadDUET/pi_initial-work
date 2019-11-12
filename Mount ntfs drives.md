### list of available device
sudo blkid 

find the UUID ( UUID="7AE29E7FE29E3F77") 

### crete mounting folder
sudo mkdir /mnt/personal

sudo nano /etc/fstab

write: 

UUID="7AE29E7FE29E3F77" /mnt/personal ntfs rw 1 1


save and exit
do the same for all drives.


### if does not give write permission

ntfsfix 'drive name'


