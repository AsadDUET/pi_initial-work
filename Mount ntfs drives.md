### list of available device
sudo blkid 

find the UUID ( UUID="7AE29E7FE29E3F77") 

### create mounting folder
sudo mkdir /home/pi/Desktop/ThisPC/movie

sudo nano /etc/fstab

### write: 

UUID=AE0664D80664A357 /home/pi/Desktop/ThisPC/movie ntfs auto,rw,defaults 1 1

save and exit
do the same for all drives.


### if does not give write permission

ntfsfix 'drive name'


