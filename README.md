11)12)1stpart
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
apt-get install -y nodejs
git clone https://github.com/bhumiprasad14/MyAwsRepo.git
cd MyAwsRepo
npm install
node index.js


12)
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install nginx
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
sudo apt install nodejs
nodejs -v
git clone https://github.com/bhumiprasad14/MyAwsRepo.git
cd MyAwsRepo
npm install
node index.js
//////////////////////////////////////////////

Open another terminal. Type the following commands:
cd / 
pwd
cd /etc/nginx/sites-available/ 
sudo nano default

Now in the nano editor go to location and paste the following code: location / {
proxy_pass http://localhost:4000; proxy_http_version 1.1;
proxy_set_header Upgrade $http_upgrade; proxy_set_header Connection 'upgrade'; proxy_set_header Host $host; proxy_cache_bypass $http_upgrade;
}
Now back to bash shell
Type: sudo systemctl restart nginx 
8)
git config --global user.name "bhumiprasad14"
git config --global user.email "prasad14bhumi@gmail.com"
git config --global --list
git init
git add .
git status
git commit -m "done"
git remote add origin "repolink"
git branch -m master
git push -u origin master



git clone https://github.com/moumita02314/testds.git

4)Public bucket create bucket ACLs enabled and Uncheck Block all Public Access. bucket created upload file-> before uploading file Under Permissions click ACLs(edit)->select Specify individual ACL permissions-> click all read options->upload button click Copy the Object URL

5)Private bucket create bucket acl disable->block all public access->create bucket upload file->upload it-> Click on the check box of our file->Actions->Share with presigned URL SET THE TIMER->Created presigned URL->object url copy paste in new tab

6)Static website on S3 create bucket->public bucket->create bucket->create index.hyml,next.html,prvs.html upload those->Go to bucket and click on properties-> Static website hosting on below-> write index.html on index document then select all files->actions->last option->copy paste->answer

sudo apt-get update sudo apt-get upgrade -y sudo apt install nginx cd .. cd .. cd var ls cd www sudo chmod 777 html goto sftp window and then in remote files \var\www\html path and then drag and drop(the following files) from left to right

<title>Page Title</title>
This is a Heading
This is a paragraph.

Go to Next Page ➡️ <title>Next Page</title>
This is Next Page
⬅️ Back to Home

Go to Previous Page ➡️

<title>Previous Page</title>
This is Previous Page
⬅️ Back to Next Page

🏠 Go to Home

8)LOcal machine to github create a github token create a folder on yout desktop and open it in gitbash then commands: 
git clone https://github.com/soumalyokundu123/aws_assg8.git 
cd aws_assg8 
git config --global user.email "soumalyokundu123@gmail.com" 
git config --global user.name "soumalyokundu123" git config --global --list 
IF ANY OTHER EMAIL OR NAME WE CAN REMOVE IT: (git config --global --unset user.name git config --global --unset user.email) 
git init 
git add . 
git status 
git commit -m "done" 
git remote add origin https://github.com/soumalyokundu123/assg.git 
git push -u origin master

9)Github to EC2 using terminal sudo apt-get update sudo apt-get upgrade -y sudo apt install nginx sudo systemctl start nginx sudo systemctl enable nginx

sudo apt install nodejs -y 
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - 
git clone https://github.com/soumalyokundu123/aws_assg8.git 
cd aws_assg8 
sudo apt install npm 
npm install 
node index.js

10)Github to EC2 using user data 
apt-get update 
apt-get install -y nginx 
systemctl start nginx 
systemctl enable nginx
curl -SL https://deb.nodesource.com/setup_18.x | sudo -E bash - 
apt-get install -y nodejs 
git clone https://github.com/soumalyokundu123/aws_assg8.git 
cd aws_assg8 
npm install 
node index.js

11)Load balancer Launch template then auto scale choose any one instance and open bitvise vi infi.sh code sudo chmod 777 infi.sh sh infi.sh

12)without port 
sudo apt-get update 
sudo apt-get upgrade -y 
sudo apt install nginx 
sudo systemctl start nginx 
sudo systemctl enable nginx
sudo apt install nodejs -y 
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - 
git clone https://github.com/soumalyokundu123/aws_assg8.git 
cd aws_assg8 
sudo apt install npm 
npm install 
node index.js 
another terminal: cd / pwd cd /etc/nginx/sites-available/ 
sudo nano default location / { 
proxy_pass http://localhost:4000; 
proxy_http_version 1.1; 
proxy_set_header Upgrade $http_upgrade; 
proxy_set_header Connection 'upgrade'; 
proxy_set_header Host $host; 
proxy_cache_bypass $http_upgrade; 
} 
sudo systemctl restart nginx

14)elastic ip instance create without code then elstic ip create allocate->upar green wala associate

15)serverless lambda se karna haii Under the Advanced settings, check the Enable Function URL checkbox & under Auth type, select NONE. Then click on Create Function. baki khud kar and error dikhane ke liye deploy karna
