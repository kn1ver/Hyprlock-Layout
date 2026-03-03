### My layout preview
![Screenshot](https://github.com/kn1ver/Hyprlock-Layout/blob/05b7f366f006bc7120b432faec7cda1de18de524/screenshot.png)

### Installation and settings
##### For install just copy .config folder and past it to /home
```
git clone https://github.com/kn1ver/Hyprlock-Layout.git
cd Hyprlock-Layout
cp -r .config/ ~/
```

##### Variables you should to change for stable work:
- Make sure that the variables you need are assigned in the devices section of the hyprlock.conf file.
  You can check the names of your monitors with the ```hyprctl monitors``` command;
  to check the name of your keyboard, use ```hyprctl devices -j```
- You should also comment out the parts of the player.conf and weather.conf configs that are duplicated for a different monitor resolution.
