# Hackintosh
A repository containing the files of my Hackintosh USB.   
Currently running on macOS Big Sur 11.2 (updated through App Store)

## Laptop Specifications
- **Laptop Model**: Dell Inspiron 5567  
- **CPU Model**: Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz  
- **iGPU**: Intel Coproration HD Graphics 620 (rev 02)  
- **dGPU**: AMD Radeon R7 M440/M445  
- **Mouse**: I2C  
- **Keyboard**: PS2
- **Audio Codec**: ALC3246 Analog (ALC256) 
- **WLAN Chipset**: Intel Corporation Wireless 3165  
- **Ethernet Chipset**: Realtek RTL810xE PCI Express Fast Ethernet controller  
- **SATA Controller**: Intel Corporation Sunrise Point-LP SATA Controller [AHCI mode]  

## Working:
- HDMI
- Battery readouts
- Headphone audio output and input (wired and bluetooth headphones)
- Keyboard and Trackpad (with gestures)
- External USB Keyboard and Wireless Mice
- App Store
- Time machine backup
- WiFi
- Bluetooth

## Not working:
- iMessage and FaceTime

## Bugs:
- Sometimes on different desktops, a black bar appears on the top right, although it goes away if you Ctrl-Up and Ctrl-Down a couple times.  
![The black bar](https://github.com/anandrajaram21/hackintosh/blob/bigsur/screenshots/black-bar.png)

## Additional Information
- I got the headphone output and input to work with https://github.com/hackintosh-stuff/ComboJack. It works flawlessly, and full credits go to the guys behind this. 
- This EFI MUST NOT BE USED AS A DROP IN SUBSTITUTE FOR YOUR OWN LAPTOP, EVEN IF IT IS THE SAME MODEL. You MUST LEARN what makes your hack work. THIS EFI SHOULD ONLY BE USED AS A LAST RESORT. IF ANYTHING GOES WRONG WITH YOUR COMPUTER, I AM IN NO WAY RESPONSIBLE FOR THE DAMAGE CAUSED. 
