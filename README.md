# pypicamera
a python script for a timelapse video - capturing JPEG stills every N sec
(using Raspberry Pi camera module) https://projects.raspberrypi.org/en/projects/getting-started-with-picamera

to start automatically every (re)boot, ssh into RPi and make a symlink into /etc/systemd:

    sudo ln -s ~/pypicamera.service /etc/systemd/system/pypicamera.service

crysman (copyleft) 2018-10
