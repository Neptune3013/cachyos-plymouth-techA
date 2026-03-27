# CachyOS Plymouth Theme with Tech A throbber

Forked from [CachyOS Plymouth Theme](https://github.com/CachyOS/cachyos-plymouth-theme) and the [Tech A](https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/78.gif)
Throbber from [Plymouth themes by](https://github.com/adi1090x/plymouth-themes?tab=readme-ov-file0) by [adi1090x](https://github.com/adi1090x)

Reduced animation frames to make it load quicker.

## Preview
https://github.com/user-attachments/assets/20d0fe4e-2a54-4399-8c8f-9aafe431ef3e



## Manual Installation

1. Clone repo
   
    ```
   git clone https://github.com/Neptune3013/cachyos-plymouth-techA.git
    ```
   

3. Copy into plymouth themes dir
   

   ```
   cd cachyos-plymouth-techA/src
   ```
   ```
   sudo cp -r cachyos-bootanimation-TechA /usr/share/plymouth/themes/
   ```
   
   
## Set the theme (Arch)

1. Set it
   ```
   sudo plymouth-set-default-theme -R cachyos-bootanimation-TechA
   ```
   

3. Test it
   ```
   sudo plymouthd ; sudo plymouth --show-splash ; sleep 5 ; sudo killall plymouthd
   ```
   
