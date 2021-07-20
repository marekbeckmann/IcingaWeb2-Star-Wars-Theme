# IcingaWeb2-Star-Wars-Theme

## 1. How to install

### 1.1 Download the theme
```
git clone https://github.com/marekbeckmann/IcingaWeb2-Star-Wars-Theme /usr/share/icingaweb2/modules/starwars-dark
```
### 1.2 Download Images (optional)
```
wget https://www.pngkit.com/png/full/75-757133_logo-star-wars-star-wars-logo-black-and.png -O /usr/share/icingaweb2/modules/starwars-dark/public/img/icon.png
wget https://wallpapercave.com/wp/wp7419777.jpg -O /usr/share/icingaweb2/modules/starwars-dark/public/img/wallpaper.jpg
```
### 1.3 Enable the theme
```
icingacli module enable starwars-dark
```
### 1.4 Set as global default theme 

Edit `/etc/icingaweb2/config.ini` and at the end add the following: 
```
[themes]
disabled = "0"
default = "starwars-dark/starwars"
```
### 1.5 Restart Icinga
```
systemctl restart icinga2
```

**Enjoy**
