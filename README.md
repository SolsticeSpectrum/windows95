<h1 align="center">windows95 dotfiles</h1>

![img](https://i.imgur.com/ooiHDCj.png)

![img](https://i.imgur.com/2VFPXAC.png)

![img](https://i.imgur.com/OnVnHiz.png)

![img](https://i.imgur.com/rK4y623.png)

![img](https://i.imgur.com/3NLk9Ea.png)


# Guide (XFCE)

## theme

Install [Chicago95](https://github.com/grassmunk/Chicago95) theme and follow the instructions [here](https://github.com/grassmunk/Chicago95/blob/master/INSTALL.md)  

Follow all instructions, including system wide installs, qt5, fonts etc.  

During the auto install, make sure to check `zsh` checkbox for that MS DOS feeling  

I included fonts here at `./fonts/truetype/ms_sans_serif` folder so at [ MS Sans Serif font ] section, you don't need to generate them with fontforge  
just use those ones  

Use my 99-ms-sans-serif-bold.conf from `.config/fontconfig/conf.d` folder to fix rendering of those fonts  

## palemoon  

Download palemoon theme [here](https://addons.palemoon.org/addon/moonscape/)  
Download palemoon icon pack [here](https://github.com/FranklinDM/Moonscape-IconPack/releases)  

Just click on `moonscape-ip-1-00.xpi` and palemoon will automatically recognize the file as addon  

Reorganize the toolbar using customize option as you please  

You can get the homepage I use in this repo and set it as default page in palemoon using url like this  
`file:///home/$USER/homepage/homepage.html`  

## audacious  

For that winamp experience, download audacious  
Put winamp.wsz from .local/share/audacious/Skins to same folder in your home folder  
Set it as theme in audacious settingss  
