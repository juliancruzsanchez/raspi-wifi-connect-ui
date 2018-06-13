# Resin WiFi Connect | UI Theme
Made by Julian Sanchez

### What is it?
It is an improved Resin WiFi Connect UI, initially used to quickly update the files on the pi

### Installation
```fish
cd /usr/local/share/wifi-connect/ui
mv index.html index.html.old
rm -rf raspi-wifi-connect-ui
git clone https://github.com/juliancruzsanchez/raspi-wifi-connect-ui.git
mv -f raspi-wifi-connect-ui/* ./
rm -rf raspi-wifi-connect-ui
 
```
