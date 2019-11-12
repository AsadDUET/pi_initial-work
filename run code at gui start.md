# How to Run Python code at desktop startup in terminal

## Step 1:

### In terminal
sudo nano /home/pi/.bashrc

### Go to the last line of the script and add:

echo Running at boot 

sudo python /home/pi/sample.py

## Step 2:

sudo nano /etc/xdg/lxsession/LXDE-pi/autostart

add 

@lxterminal 

before

@xscreensaver -no-splash
