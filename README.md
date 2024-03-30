#installing Docker
apt install docker -y

#installing git
apt install git -y

#installing Node.js
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
nvm install --lts
source ~/.bashrc
nvm install --lts
node -e "console.log('Running Node.js ' + process.version)"
Node.js
npm install

#installing Docker Compose
curl -SL https://github.com/docker/compose/releases/download/v2.25.0/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
docker compose --version
chmod +x /usr/local/bin/docker-compose
docker compose --version
