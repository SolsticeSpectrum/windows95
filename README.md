<h1 align="center">windows95 dotfiles</h1>

![img](https://i.imgur.com/yUFo2wk.png)

![img](https://i.imgur.com/Zv6shCh.png)

![img](https://i.imgur.com/OBS2HJ2.png)



# Guide (XFCE)

## theme

Install [Chicago95](https://github.com/grassmunk/Chicago95) theme and follow the instructions [here](https://github.com/grassmunk/Chicago95/blob/master/INSTALL.md)  

Follow all instructions, including system wide installs, qt5, fonts etc.  

During the auto install, make sure to check `zsh` checkbox for that MS DOS feeling  

I included fonts here at `./fonts/truetype/ms_sans_serif` folder so at [ MS Sans Serif font ] section, you don't need to generate them with fontforge  
just copy them from fonts folder here  

Use my 99-ms-sans-serif-bold.conf from `.config/fontconfig/conf.d` folder to fix rendering of those fonts  

## palemoon  

Download plaemoon theme [here](https://addons.palemoon.org/addon/moonscape/)  
Download palemoon icon pack [here](https://github.com/FranklinDM/Moonscape-IconPack/releases)  

Just click on `moonscape-ip-1-00.xpi` and palemoon will automatically recognize the file as addon  

Reorganize the toolbar using customize option as you please  

You can get the homepage I use in this repo and set it as default page in palemoon using url like this  
`file:///home/ruda0/homepage/homepage.html`  
