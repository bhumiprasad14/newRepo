11)
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
apt-get install -y nodejs
git clone http://github.com/sudip7407/Repo1.git
cd Repo1
npm install
node index.js


12)
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install nginx
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
sudo apt install nodejs
nodejs -v
git clone http://github.com/sudip7407/Repo1.git
cd Repo1
npm install
node index.js
//////////////////////////////////////////////
cd /
cd etc/nginx/sites-available/
sudo nano default
sudo systemctl restart nginx
sudo systemctl stop nginx
///////////////////////////////////////////
