CoffeeBean Dynamic Wallpapers by robcox
________________________________________

To install, copy files to the system backgrounds folder using root privileges

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


Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in
 
 
Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/coffeebean
 
 - sudo rm -r /usr/share/gnome-background-properties/coffeebean-backgrounds.xml
 
 Enjoy!!
 
