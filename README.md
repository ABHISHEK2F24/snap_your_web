<img src="snap/gui/favicon.png" align="right" />
# snap_your_web 
  > project to create a desktop app in linux over LXD using snapcraft
 
 ## Requirements
 - [Snapcraft](https://snapcraft.io/) Snaps are quick to install, easy to create, safe to run, and they update automatically and transactionally so your app is always fresh and never broken.
 - Ubunutu 16.04 or Higher
 
 ## Softwares to install 
  - NodeJS ``` sudo apt get install nodejs```
  - curl   ``` curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash - ```
  - build-essential   ``` sudo apt install curl build-essential ```
  - libgconfig2-4  ```sudo apt install curl libgconf2-4```
  - electron  ``` npm install electron --save-dev --save-exact ```
  - electron-builder   ```npm install electron-builder --save-dev ```
  - snapcraft ``` sudo snap install snapcraft --classic --candidate ```
  - lxd ``` sudo snap install lxd ```
 
## How to Use
 After install all above required packages hit command this will create your .snap package
    ``` snapcraft cleanbuild ```
    
 And to install package on your system just enter following command
    ``` snap install --dangerous AppName_0.1_amd64.snap ```
 
 After successful installation you can run your software by name of your app   
     
 
  
  
 
 
