# TouchScreen

 - http://www.waveshare.com/wiki/3.5inch_RPi_LCD_(A)
 - sudo apt-get install git
 - git clone https://github.com/goodtft/LCD-show.git
 - chmod -R 755 LCD-show
 - cd LCD-show/
 - sudo ./LCD35-show
 
 #Toggle
 
 - cd LCD-show/
 - ./LCD-hdmi
 - ./LCD35-show
 
 # Retropie
 
 - http://www.newsby2.com/2017/04/10/how-to-install-3-5-inch-tft-lcd-waveshare-screen-retropie/
 - curl -O https://raw.githubusercontent.com/adafruit/Raspberry-Pi-Installer-Scripts/master/pitft-fbcp.sh
 - sudo bash pitft-fbcp.sh 
 - sudo ~/RetroPie-Setup/retropie_setup.sh

 # Website
 
 - sudo nano /etc/X11/xorg.conf.d/99-calibration.confsu
 - Option "TransformationMatrix" "0 -1 1 1 0 0 0 0 1"
