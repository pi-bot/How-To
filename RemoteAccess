#Remote Access

There are many ways to connect remoely to a Raspberry Pi
- Serial:  Two pins **RX** and **TX** from the GPIO give a console output through a basic serial interface. 
- SSH: A secure shell terminal session can be set up via ethernet or wireless.
- VNC:  A virtual Network connection can be used to give a Raspberry Pi remote Desktop other ethernet or wireless.
- Bluetooth:


##Tight VNC

```
sudo apt-get install  tightvncserver
```

After installed it can be launched with:

```
vncserver :0 -geometry 1920x1080 -depth 24
```
This will start a session. If it asks for a password I put "raspberry" 


###TO connect from mac:

To make it persistent
```
cd /home/pi/.config
mkdir /home/pi/.config/autostart
Sudo nano /home/pi/.config/autostart/tightvnc.desktop
```

Then add this in the file
```
[Desktop Entry]
Type=Application
Name=TightVNC
Exec=vncserver :1
StartupNotify=false
```
Then
```
Sudo reboot
```
That should do it!
