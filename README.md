# CachyOS Plymouth Theme with Tech A throbber

Forked from [CachyOS Plymouth Theme](https://github.com/CachyOS/cachyos-plymouth-theme)
Throbber from [Plymouth themes by](https://github.com/adi1090x/plymouth-themes?tab=readme-ov-file0) by [adi1090x](https://github.com/adi1090x)

Reduced animation frames to make it load quicker.

## Manual Installation

1. Clone repo
   
    `git clone https://github.com/Neptune3013/cachyos-plymouth-techA.git`
   

3. Copy into plymouth themes dir
   cd into src dir and run
   `sudo cp -r cachyos-bootanimation-TechA /usr/share/plymouth/themes/`
   
## Set the theme (Arch)

1. Set it
   `sudo plymouth-set-default-theme -R cachyos-bootanimation-TechA`
   

3. Test it
   '''
   sudo plymouthd ; sudo plymouth --show-splash ; sleep 5 ; sudo killall plymouthd
   '''
   
