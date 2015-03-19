=============Node===================
# sudo apt-get update
# sudo apt-get install nodejs
# sudo apt-get install npm

# sudo npm install -g  express

# express --ejs .
if nodejs don't work on Ubuntu the install 
# sudo apt-get install nodejs-legacy
# sudo npm install 


Change files 
# sudo npm install passport --save
# sudo npm install passport-local --save
# sudo npm install bcrypt-nodejs --save
# sudo npm install express-session --save
==================Install MongoDB==========================
1. Add this line to your /etc/apt/sources.list 
deb http://downloads-distro.mongodb.org/repo/ubuntu-upstart dist 10gen 

2. Add the public gpg key: 
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv 7F0CEB10 

3. Update aptitude repos 
sudo aptitude update 

4. Get mongodb 
sudo apt-get install mongodb-10gen 

====================if starting mongodb is a problem =====================
 /etc/init.d/mongod status
or

 sudo service mongod status
2.If it's not started repair it like this:

sudo rm /var/lib/mongodb/mongod.lock
mongod --repair
sudo service mongodb start
===============================================================

create database directory 
# cd /
# sudo mkdir data
# cd data
# sudo mkdir db
===================================