# clone the repo into your disk.
$ git clone https://github.com/bxm0927/lottery.git

# 安装 npm
sudo apt install npm

# 安装依赖
$ npm install

# 安装MongoDB
sudo apt update
sudo apt install -y mongodb

## 查看数据库状态与停启服务
sudo systemctl status mongodb
sudo systemctl stop mongodb
sudo systemctl start mongodb
sudo systemctl restart mongodb

sudo ufw allow from 127.0.0.1/32 to any port 27017

# 导入 MongoDB 数据
$ mongoimport -d vue_xiaomi -c goods --file E:\resource\dumall-goods
$ mongoimport -d vue_xiaomi -c users --file E:\resource\dumall-users

# 运行 Vue
$ npm run dev

# 运行 Node.js
$ node server/bin/www