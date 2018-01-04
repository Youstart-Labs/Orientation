# List of Require Developer Application

 * Mongo DB
 * Robomongo
 * Bower v1.8.x
 * jdk and Jre (Java v1.8.0)
 * Android Studio v2.3.3
 * Angular CLI
 * Ionic CLI v3.x
 * PostgreSQL DB
 * Pycharm (Python Django)
 * PGMyAdmin (If using postgres)
### Mongo DB

###### Windows
   *  Download [from](https://www.mongodb.com/download-center?jmp=nav#atlas) and Install
   *  Set path of Mongo DB for use at global in environment variable in winodws PATH(C:\Program Files\MongoDB\Server\3.4\bin) (if require)
   *  Create data/db Folder in C drive (If installer not created automatically)
    
###### Ubuntu
   *  sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv EA312927
   *  echo "deb http://repo.mongodb.org/apt/ubuntu xenial/mongodb-org/3.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.2.list
   *  sudo apt-get update
   *  sudo apt-get install -y mongodb-org
   *  sudo systemctl start mongod
   *  sudo systemctl status mongodb
   *  For more information 
      * [16.0.4](https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-16-04)


### Robomongo (User interface app for See mongo database data)

###### Windows
   *  Download [from](https://robomongo.org/download) and Install
   *  Connect Robomongo with server after start and check created database

###### Ubuntu
   *  download tar.gz file from Official robomongo website(choose version you need to install and get it's tar.gz download file url)

   *  wget https://download.robomongo.org/0.9.0/linux/robomongo-0.9.0-linux-x86_64-0786489.tar.gz
   *  tar -xvzf robomongo-0.9.0-linux-x86_64-0786489.tar.gz
   *  sudo mkdir /usr/local/bin/robomongo
   *  sudo mv  robomongo-0.9.0-linux-x86_64-0786489/* /usr/local/bin/robomongo
   *  /usr/local/bin/robomongo/bin
   *  cd /usr/local/bin/robomongo/bin
   *  sudo chmod +x robomongo ## run command only if robomongo isn't excutable file
   *  ./robomongo
   *  For more information 
      [Click Here](https://askubuntu.com/questions/739297/how-to-install-robomongo-on-ubuntu/781793)

###  Jdk and Jre (Java v1.8.0)

###### Windows
   *  For JDK Installation [Click here](https://www3.ntu.edu.sg/home/ehchua/programming/howto/JDK_Howto.html)
   *  Check these path set in Envi variable PATH
   *  Set Path environment variable (If installer not set automatically)
         *  C:\ProgramData\Oracle\Java\javapath
         *  C:\Program Files\Java\jdk1.8.0_111\bin (Install JDK vesrsion)

##### Ubuntu
   *  sudo apt-add-repository ppa:webupd8team/java
   *  sudo apt-get update
   *  sudo apt-get install oracle-java8-installer
   *  ensure your JAVA_HOME variable has been set to:
      *  export JAVA_HOME=/usr/lib/jvm/java-8-oracle
   *  For more information 
      [Click Here](https://www.youtube.com/watch?v=VrOhA-I3aFs)


### Android Studio v2.3.3

###### Windows
   *  Download [from](https://developer.android.com/studio/index.html/) and install
   *  Launch the .exe file you downloaded.
   *  Follow the setup wizard to install Android Studio and any necessary SDK tools.
   *  For more information 
      [Click Here](https://developer.android.com/studio/install.html)

###### Ubuntu
   *  Download [from](https://developer.android.com/studio/index.html/) and extract
   *  sudo mv [extract Path] /usr/local/
   *  cd /usr/local/android-studio/bin/
   *  ./studio.sh
   *  Follow the application instruction at finish
        

###  Bower v1.8.x
   *  npm install -g bower


###  Angular CLI
   *  npm install -g @angular/cli
   *  For more information 
      [Click Here](https://github.com/angular/angular-cli)


###  Ionic CLI
   *  npm install -g ionic@latest
   *  npm install -g cordova
   *  For more information 
      [Click Here](https://ionicframework.com/docs/cli/)        

###  PostgreSQL DB

###### Windows
   *  Download [from](https://www.postgresql.org/download/windows/) and Install
   *  set default user postgres password on run setup time

###### Ubuntu
*  sudo apt-get update
*  sudo apt-get install postgresql postgresql-contrib
*  service postgresql start (start, restart stop)
*  sudo su postgres
*  psql
*  man psql (For more information)
```
   postgres =#
```

In PostgreSQL window
*  \l :  use for See list of database 
*  \du   :  use   \du for user
*  ALTER USER postgres WITH PASSWORD 'test123'; : use change default password of default user
*  CREATE USER user_1 WITH PASSWORD 'test123';  : use create new user
*  ALTER USER user_1 WITH SUPERUSER;: Give super user permission
*  DROP USER user_1 WITH SUPERUSER; Drop created user
*  For more information 
   *  [Click here ](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04) or [youtube help](https://www.youtube.com/watch?v=-LwI4HMR_Eg)
* Install pgAdmin III for see database (Using Ubuntu software app)   