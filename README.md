# hypr.danna
[![swappy-20241101-151144.png](https://i.postimg.cc/MGw6906G/swappy-20241101-151144.png)](https://postimg.cc/JsTCnkBw)
## Information

### Welcome! These are my dotfiles <33
This is from the Danna repository. I am going to give you instructions and the necessary dependencies for my theme. ^^

### ‼️ Important !!
- Not works in Nvdia (well, i don't try it xd).
- The fonts will be installed in another steps.
- Change the name of your monitor un the hyprland configs.

### 🍧 Information

-  **OS** Arch Linux
-  **SH** zsh 5.9
-  **TM** kitty 0.35.2
-  **WM** Hyprland (Wayland)

## Steps for install

🔧 Script
```sh
git clone https://github.com/danxnya/hypr.pro.git && cd hypr.pro/
chmod +x setup.sh
./setup.sh
```


```sh
mkdir ~/fonts/
cd fonts/ && unzip fonts.zip
```
### Install necessary fonts on ~/fonts and reboot.
[Fonts here](https://mega.nz/file/GxFVSLLY#etuNc6QRrEl6wgl_ZatvomojDhkBTFPqlKS7ELk7KAM)

```sh
sudo cp -r ~/fonts/* /usr/share/fonts/*
```
Install your favorite desktop manager, I use `emptty`.
```sh
sudo pacman -S emptty
systemctl enable emptty.service
```

Now, only wait and ENJOY. ><


👤 Author
danxnya
