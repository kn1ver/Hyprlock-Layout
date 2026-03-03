Variables you should to change for stable work:
- at .config/hyprlock/scripts/weather.sh: OpenWeatherMap API Key [You can get it on OpenWeatherMap](https://openweathermap.org/)
- at .config/hyprlock/scripts/lang_layout.sh: .keyboard[i] , where i - number of your keyboard from `hyprctl devices -j`
- at .config/hyprlock/layouts/mylayout/player.conf: monitors from `hyprctl monitors`
- at .config/hyprlock/layouts/mylayout/weather.conf: monitors from `hyprctl monitors`
- at .config/hyprlock/layouts/mylayout/powermenu.conf: keyboard name from `hyprctl devices -j`

You should also comment out the parts of the player.conf and weather.conf configs that are duplicated for a different monitor resolution.
