# PM2 package.
PM2 us a daemon process manager that will help you manage and keep your application online 24/7. It is used only for Nodejs applications.

Take installation code from official document of Nodejs
sudo apt-get install -y nodejs
mkdir ~/.npm-global
export PATH=~/.npm-global/bin:$PATH
source ~/.profile
npm config set prefix /usr/local
sudo chown -R $USER /usr/local
npm install
npm install -g pm2
