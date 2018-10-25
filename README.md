# archi3xfcehybrid
This is an i3wm + Xfce4 panel on Arch Setup. 
This is in testing

# Steps to install:
## Step # 1 prerequisite apps
  Use pacman -S to install the following packages:
  i3-gaps dmenu i3lock feh conky compton unclutter lxappearance menulibre i3status volumeicon thunar pavucontrol xautolock

  Ex: $ sudo pacman -S i3-gaps dmenu i3lock feh conky compton unclutter lxappearance menulibre i3status volumeicon thunar   pavucontrol xautolock

  Use AUR to install j4-dmenu-desktop
  Ex: $ trizen -S j4-dmenu-desktop
  
  ## Step # 2 Move Config Files
  
    In Home folder CTRL + H to unhide files
    Navigate to .config > i3
    Paste .config file downloaded in i3 folder
    Paste compton.conf file downloaded in i3 folder
    
    Navigate to .config
    locate xfce4 folder
    paste downloaded xfce4 folder here in place
 
 ## Step #3 Wallpaper
 Move the downloaded wallpaper to your pictures folder
 Validate path is correct for feh in i3 .config file
 
## Step # 4 Enjoy
    Logout of current DE
    Login to i3
    
    
    


