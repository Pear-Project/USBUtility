# USB Utility app for pearOS
This app is made to format USBs and SD Cards :) in pearOS and NiceC0re based OS

## Screenshots :)
![Nice Screenshot](Screenshots/usbutility.png)


## Dependencies

   - install gambas3 package
   ```sh
   $ sudo apt-get install gambas3 -y
   ```

## Installation steps
 - From Source:

   - clone the project
   ```sh
   git clone https://github.com/alxb421/USBUtility
   ```
   - Open gambas3 application (from terminal `$ gambas3`, or from application dashboard, search for gambas3)
   - Click `Open`
   - Navigate to cloned folder, and open the project
   - Click on `Project` > `Make` > `executable`
   - copy the new executable in the `/usr/bin` folder of your Linux machine
   ```sh
   $ sudo mv <path to your generated .gambas file> /usr/bin/usbutil
   ```
   - Enjoy :p

 - From Package:
   - Download the .deb package from `Releases` tab here, in GitHub
   - Install using gdebi/ dpkg
   ```sh
   $ sudo dpkg -i <path to downloaded deb file, or drag and drop>
   ```
   
   ## Usage
   - From Terminal:
     - Open a terminal and type `usbutil`
   - From Application Daskboard:
     - Search for `USB Utility` in the Applications Dashboard
