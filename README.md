# CoffeeBean
Dynamic Background for gnome desktop

![coffeebean3](https://github.com/user-attachments/assets/a44e9835-fa6e-4817-b8c0-60c48ff063e3)

CoffeeBean-Day

# Description
A super mellow Dynamic Background theme for gnome desktop.

The background transitions from light to dark according to the time of day.

Morning -> Day -> Evening -> Night -> Repeat.

The Dynamic Background can be installed directly into the system backgrounds folder.

Then you can enable using the gnome Settings -> Backgrounds section of your distribution. 

![coffeebean1](https://github.com/user-attachments/assets/984ef6d8-242b-4fc0-bdf3-2dc7c79a3c77)

CoffeeBean-Night

# Installation
Download CoffeeBean Dynamic Background here: <a href="https://www.gnome-look.org/p/2313312/">https://www.gnome-look.org/p/2313312/</a>

To install, copy files to the system backgrounds folder using root privileges.

 - Extract CoffeeBean.tar.xz to Downloads folder
 
 - Right-click CoffeeBean folder and select "open in terminal"
 
 
Copy theme folders to backgrounds and change permissions to root
 
 - sudo cp -r coffeebean /usr/share/backgrounds/
 
 - sudo chown -R root:root coffeebean
 
 - sudo chmod -R 755 coffeebean
 
 
Copy coffeebean-wallpapers.xml to gnome-background-properties and change permissions

 - sudo cp coffeebean-wallpapers.xml /usr/share/gnome-background-properties/
 
 - sudo chown -R root:root coffeebean-wallpapers.xml
 
 - sudo chmod -R 755 coffeebean-wallpapers.xml 

 
To set new wallpaper, use Settings -> Background or right-click desktop "Change Background..."


# Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in


# Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/coffeebean
  
 - sudo rm -r /usr/share/gnome-background-properties/inkspot-backgrounds.xml

# Extras

Looks great with CoffeeBreak Theme:

CoffeeBreak Theme here: <a href="https://github.com/therobcox/CoffeeBreak">https://github.com/therobcox/CoffeeBreak</a>

CoffeeBreak Icon Theme here: <a href="https://github.com/therobcox/CoffeeBreak-Icons">https://github.com/therobcox/CoffeeBreak-Icons</a>


