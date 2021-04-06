# Raspberry-Pi
Notes for managing and operating Raspberry Pi

### Installation on Mac OS X
Download [Raspbian OS](https://www.raspberrypi.org/downloads/raspbian/) and unzip the `.img` file.  
Download [balenaEtcher](https://www.balena.io/etcher/) for Mac OS X and install it.  
Use balenaEtcher to write the `.img` file to the SD card.
  
Documentation on https://www.raspberrypi.org/documentation/installation/installing-images/mac.md  
  
### First steps with Raspberry Pi
Log in (if you chosen desktop version, wait a minute or two to boot in the graphic screen).  
Set up TimeZone, Language and Keyboard.  
Change user password.  
Set up network.  
After reboot run `sudo raspi-config` from the terminal.  
Do the necessary configuration and reboot.  
Run `sudo apt-get update && sudo apt-get dist-upgrade -y` and reboot.  
Start working and have fun!
  
### Issues
Issue with numpy and pandas libraries
```> sudo apt-get install libatlas-base-dev```  
Source: https://github.com/numpy/numpy/issues/14772  