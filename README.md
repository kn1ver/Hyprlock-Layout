### My layout prewivew
![Screenshot](https://github.com/kn1ver/Hyprlock-Layout/blob/05b7f366f006bc7120b432faec7cda1de18de524/screenshot.png)

### Installation and settings
##### For install just copy .config folder and past it to /home
```
git clone https://github.com/kn1ver/Hyprlock-Layout.git
cd Hyprlock-Layout
cp -r .config/ ~/
```

##### Variables you should to change for stable work:
- at .config/hyprlock/scripts/weather.sh: OpenWeatherMap API Key [You can get it on OpenWeatherMap](https://openweathermap.org/)
- at .config/hyprlock/scripts/lang_layout.sh: .keyboard[i] , where i - number of your keyboard from `hyprctl devices -j`
- at .config/hyprlock/layouts/mylayout/player.conf: monitors from `hyprctl monitors`
- at .config/hyprlock/layouts/mylayout/weather.conf: monitors from `hyprctl monitors`
- at .config/hyprlock/layouts/mylayout/powermenu.conf: keyboard name from `hyprctl devices -j`

You should also comment out the parts of the player.conf and weather.conf configs that are duplicated for a different monitor resolution.
