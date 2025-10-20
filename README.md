README.md

sudo dnf config-manager --disable mysql57-community
sudo dnf config-manager --enable mysql80-community

sudo dnf install mysql-community-server -y

sudo mysql_secure_installation
