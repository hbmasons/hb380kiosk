#Quick Reference for Future Maintenance:

##Add/Remove Images:

Just upload to GitHub https://github.com/hbmasons/hb380kiosk/images folder - automatic update

##Change Screen Orientation:

Edit /home/kiosk/start-kiosk.sh and change ROTATION="right" (left|right|normal)

##Change Slideshow URL (root/sudo required):

bash /home/kiosk/update-kiosk-url.sh

##Maintenance Mode (root/sudo required):

Enable: bash /home/kiosk/enable-maintenance.sh
Disable: bash /home/kiosk/disable-maintenance.sh

##Change Slide Duration:

Edit index.html on GitHub, change SLIDE_DURATION = 10000 (milliseconds)
