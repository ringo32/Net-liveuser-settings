#!/bin/bash
sudo cp -praf /usr/share/calamares/settings.conf_online /usr/share/calamares/settings.conf
sudo cp -praf /usr/share/calamares/modules/packages.conf_online /usr/share/calamares/modules/packages.conf
sudo cp -praf /usr/share/calamares/modules/welcome.conf_online /usr/share/calamares/modules/welcome.conf
lxterminal -e sudo /usr/bin/calamares -d > /home/liveuser/endeavour-install.log
cat /home/liveuser/endeavour-install.log | curl -F 'f:1=<-' ix.io
