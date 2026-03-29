# purple-plymouth-theme
Cute LUKS UI with eyes + Gengar animation
![](./preview.gif)

## Installation ##
```
cd /usr/share/plymouth/themes/
```
```
sudo git clone https://github.com/mrbff/purple-plymouth-theme.git gengar
```
```
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/gengar/gengar.plymouth 666
```
```
sudo update-initramfs -u
```

