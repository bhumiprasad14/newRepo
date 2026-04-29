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


Open another terminal. Type the following commands:
Cd / pwd
cd /etc/nginx/site-available/ 
sudo nano default

Now in the nano editor go to location and paste the following code: location / {
proxy_pass http://localhost:4000; proxy_http_version 1.1;
proxy_set_header Upgrade $http_upgrade; proxy_set_header Connection 'upgrade'; proxy_set_header Host $host; proxy_cache_bypass $http_upgrade;
}
Now back to bash shell
Type: sudo systemctl restart nginx Then type: node index.js


8)
git config --global user.name "bhumiprasad14"
git config --global user.email "prasad14bhumi@gmail.com"
git config --global --list
git init
git add .
git status
git commit -m "done"
git remote add origin "repolink"
git push -u origin master

