# List of Required Application

#### Common Application List
 * Git (Windows 10: 2.15.x and Ubuntu 16.0.4: 2.7.4)
 * GITLAB/GITHUB (Account)
 * User Interface Git Application
 * Node (Current Stable 8.9.3)
 * Python v3.x
 * Visual Studio Code (For Java script)
 * PuTTy and Putty Gen (Only for windows)
 * POSTMAN
 * Slack (Optional if not use web app)
 * Trello Application (Optional not if use web app)
 * FileZila

### Git (Windows 10: 2.15.x and Ubuntu 16.0.4: 2.7.4)

###### Windows
* GO to https://git-scm.com/downloads
* Download and Install

###### Ubuntu
* sudo apt-get install git
* Set global username and email for Git configure
   *  git config --global user.name "John Appleseed" (set global user name)
   *  git config --global user.email "email@example.com" (set global user name)



### User Interface Git Application

###### Windows (Source Tree)
   * Download https://www.sourcetreeapp.com/ and install
   
###### Ubuntu (GitKraken)
   * wget https://release.gitkraken.com/linux/gitkraken-amd64.deb
   * sudo dpkg -i --force-depends gitkraken-amd64.deb
   * sudo apt-get install -f
   * rm -f gitkraken-amd64.deb


### Node (Current Stable 8.9.3)

###### Windows
   *  Download [from](https://nodejs.org/en/download/) and Install
   *  node --version

###### Ubuntu
   *  sudo apt-get update
   *  sudo apt-get install nodejs
   *  sudo apt-get install npm
   *   nvm alias default 8.9.3 (set default Node version if require)
   *  For more information 
    * [14.0.4](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-an-ubuntu-14-04-server)
    * [16.0.4](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04)
    
###  Python 3

###### Windows
   *  Download [from](https://www.python.org/downloads/) and Install
   *  Set PYTHONPATH for python and pip in environment variable (If installer not set automatically)

###### Ubuntu
Step 1 — Setting Up Python 3
*  sudo apt-get update
*  sudo apt-get -y upgrade
*  python3 -V (For check python version)
```   
   Output
   Python 3.5.2
```
*  sudo apt-get install -y python3-venv

Step 2 — Setting Up a Virtual Environment
*  sudo apt-get install -y python3-venv
*  For more information 
      [Click Here](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-programming-environment-on-an-ubuntu-16-04-server)
        
###  PuTTy and PuTTy Gen (Only for windows)
###### Windows
*  Download [from](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) and Install
###### Ubuntu
*  Run commned
   *  ssh -i PEM_LOCATION_PATH SERVER_USER_NAME@SERVER_ADDRESS
      
