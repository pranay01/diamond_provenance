
sudo apt install python-pip
pip install django

pip install djangorestframework
pip install markdown       
pip install django-filter

sudo pip install django-cors-headers

In diamond_hash folder -> 
python manage.py runserver



$ sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev

$ sudo apt-get install python3.5-dev python3-numpy libtbb2 libtbb-dev

Install opencv 3.2

sudo apt-get install libjpeg-dev libpng-dev libtiff5-dev libjasper-dev libdc1394-22-dev libeigen3-dev libtheora-dev libvorbis-dev libxvidcore-dev libx264-dev sphinx-common libtbb-dev yasm libfaac-dev libopencore-amrnb-dev libopencore-amrwb-dev libopenexr-dev libgstreamer-plugins-base1.0-dev libavutil-dev libavfilter-dev libavresample-dev


$ sudo -s

cd /opt

/opt$ git clone https://github.com/Itseez/opencv.git

/opt$ git clone https://github.com/Itseez/opencv_contrib.git

Instructions for installing opencv 3.2.x
http://www.codebind.com/linux-tutorials/install-opencv-3-2-ubuntu-16-04/

sudo pip install opencv-python

sudo npm install webpack-dev-server -g


Ubunutu Xenial’s node version is very old - use below to update
Otherwise truffle compile will give error

curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs


light chain sync worked in geth

In the code directory run - webpack-dev-server --host 0.0.0.0

webpack-dev-server -d --host 0.0.0.0 --public <public-ip>:8080




https://github.com/trufflesuite/truffle-hdwallet-provider

screen geth --testnet --rpc --rpcapi db,eth,net,web3,personal --cache=1024  --rpcport 8545 --rpcaddr 0.0.0.0 --rpccorsdomain “*"

put public ip of VM when getting the webProvider

Open 8545 in Network Security group of Azure VM

sudo netstat -ntlp

For active servers soon Ubuntu

git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/pranay01/diamond_provenance.git
git push -u origin master

