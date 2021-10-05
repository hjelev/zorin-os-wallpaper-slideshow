# Zorin OS Wallpaper Slideshow
Bash script to create a wallpaper slideshow for GNOME

I made this script to create a desktop wallpaper slideshow without Shotwell as this method was not working in Zorin OS.

To use the script update the DIR variable to point to your photos and then schedule it with a cron job

The cron job below will change your wallpaper every 10 minutes.

`*/10 * * * * /bin/bash /home/masoko/scripts/change_wallpaper.sh`
