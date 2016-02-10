# linux-setup
# install wireless router
apt-get install linux-image-$(uname -r|sed 's,[^-]*-[^-]*-,,') linux-headers-$(uname -r|sed 's,[^-]*-[^-]*-,,') broadcom-sta-dkms
sudo apt-get install linux-image-$(uname -r|sed 's,[^-]*-[^-]*-,,') linux-headers-$(uname -r|sed 's,[^-]*-[^-]*-,,') broadcom-sta-dkms
modprobe -r b44 b43 b43legacy ssb brcmsmac bcma
sudo modprobe -r b44 b43 b43legacy ssb brcmsmac bcma
modprobe wl

#install text editor
wget https://atom.io/download/deb 
sudo dpkg -i deb
# install nvm 

curl https://raw.githubusercontent.com/creationix/nvm/v0.11.1/install.sh | bash
source ~/.profile
nvm install 5
nvm use v5
#install  Work project 
mkdir work
cd work/
git clone https://github.com/Directorpoint/dpoint-website/tree/HarrisEvent

sudo apt-get update
sudo apt-get -y upgrade
sudo apt-get -f install
sudo apt-get -y upgrade
sudo apt-get install linux-image-extra-`uname -r`
uname -r
apt-get install apt-transport-https ca-certificates
sudo apt-get install apt-transport-https ca-certificates
apt-key adv --keyserver hkp://p80.pool.sks-keyservers.net:80 --recv-keys 58118E89F3A912897C070ADBF76221572C52609D
sudo apt-key adv --keyserver hkp://p80.pool.sks-keyservers.net:80 --recv-keys 58118E89F3A912897C070ADBF76221572C52609D
sudo atom /etc/apt/sources.list.d/docker.list
apt-get update
sudo apt-get update
apt-cache policy docker-engine
sudo apt-get update
sudo apt-get install docker-engine
sudo service docker start
sudo docker run hello-world
sudo groupadd docker
sudo gpasswd -a jharri34 docker
sudo service docker restart
apt-get upgrade docker-engine
sudo apt-get upgrade docker-engine

cd dpoint-website/

apt-get    update 
sudo apt-get    update 
sudo apt-get -y upgrade
echo "deb http://www.rabbitmq.com/debian/ testing main" >> /etc/apt/sources.list
 echo "deb http://www.rabbitmq.com/debian/ testing main" >> /etc/apt/sources.list
su
sudo su
curl http://www.rabbitmq.com/rabbitmq-signing-key-public.asc | sudo apt-key add -
apt-get update
sudo apt-get update
sudo apt-get install rabbitmq-server
sudo atom sudo /etc/default/rabbitmq-server
man ulimit
sudo rabbitmq-plugins enable rabbitmq_management
service rabbitmq-server start
sudo service rabbitmq-server start
sudo apt-get update
sudo apt-get install build-essential
wget http://download.redis.io/releases/redis-stable.tar.gz
ls
tar xzf redis-stable.tar.gz
cd redis-stable
make
make test
sudo make install
cd utils
sudo ./install_server.sh
ls
cd ..
ls
cd ..
mv redis-stable ~/
ls
rm redis-stable.tar.gz 
git status
redis-cli
sudo service redis_6379 start
sudo service redis start
cd ..
ls
cd redis-stable/
ls
cd utils/
ls
./install_server.sh 
sudo ./install_server.sh 
service redis start
sudo service redis start
sudo service redis_6379 start
redis-cli
sudo update-rc.d redis_6379 defaults
cd ~
sudo apt-get install mysql-server
sudo apt-get install monit
sudo atom /etc/monit/monitrc
monit reload
sudo monit reload
cd work/dpoint-website/
ls
npm update
npm install
nvm ls
nvm ls-remote
nvm ls
nvm install v10.25
nvm install v0.10.25
nvm use v0.10
ls
npm install
ls
cd database/
ls
./createDB
atom createDB 
npm update
mysql
mysql -ujharri34 -pfour22436one
mysql -uroot 
mysql -uroot -pfour22436one
npm search mite
ls
cd work/
ls
cd dpoint-website/
ls
npm search mite
which npm 
nvm
mysql -ujharri34 -pfour22436one
exit
cd /etc/environment
touch /etc/environment
sudo touch /etc/environment
sudo atom /etc/environment 
wd

pwd
sudo apt-get install mysql-workbench
mysql-workbench 
source ./profile
ls
source .profile
npm 
nvm
nvm ls
nvm use v0.10
ls
cd work/
ls
cd dpoint-website/
ls
npm search mite
npm install -g mite
ls |grep mite
ls -a|grep mmite
ls -a|grep mite
mite init
ls
nano .mite
mite init
ls
mite up
ls
cp settings.js.example settings.js
atom settings.js
ls
cp newrelic.js.example newrelic.js
atom newrelic.js
ls
rabbitmqctrl
npm install -g less
node scripts/less-watch-compiler.js less/ public/css/
sudo cp prereqs/pdf2json /usr/local/bin
apt-cache search swftools
sudo apt-get install -y swftools
sh start_app.sh 
sudo service rabbitmq-server status 
sh start_app.sh 
npm install 
npm install repository
mkdir logs files uploads
ls
sh start_app.sh 
npm install buffertools
sh start_app.sh 
npm install buffertools.node
npm install
sh start_app.sh 
crontab crontab
sudo apt-get install zsh
source .profile
cd ~
source .profile
atom &
zsh
