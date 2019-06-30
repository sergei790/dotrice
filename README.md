# dotrice
My i3 desktop rice


You need install :
sudo pacman -S i3-gaps i3blocks dmenu termite thunar thunar-volman thunar-archive-plugin xarchiver xdg-user-dirs ttf-fontawesome feh vagy nitrogen


Second need polyba here : 
yay polybar arcolinux-polybar-config-git 

#Sound

sudo pacman -S pulseaudio --noconfirm --needed 

sudo pacman -S pulseaudio-alsa --noconfirm --needed 

sudo pacman -S pavucontrol --noconfirm --needed

sudo pacman -S alsa-utils alsa-plugins alsa-lib alsa-firmware --noconfirm --needed 

sudo pacman -S gstreamer --noconfirm --needed 

sudo pacman -S gst-plugins-good gst-plugins-bad gst-plugins-base gst-plugins-ugly --noconfirm --needed 

sudo pacman -S volumeicon --noconfirm --needed 

sudo pacman -S playerctl --noconfirm --needed


#take print screen write i3 config
# screenshot bindsym Print exec scrot '%Y-%m-%d-%H-%M-%S_$wx$h.png' -e 'mv $f ~/Pictures/Screenshotz/'
