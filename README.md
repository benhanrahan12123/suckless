Edit your .xinitrc and .bash_profile files in ~/ as necessary

# Example:

### .xinitrc
feh --no-fehbg --bg-fill '/home/ben1/Pictures/wallhaven-jxm1mw.jpg' &  
picom --backend glx --config ~/.config/picom/picom.conf &  
slstatus &  
exec dwm

### .bash_profile
startx
