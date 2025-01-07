# Update package list
```bash sudo apt update```

# Install MySQL Server
sudo apt install mysql-server

# Secure MySQL installation
sudo mysql_secure_installation

# Start and enable MySQL service
sudo systemctl start mysql
sudo systemctl enable mysql

# Check MySQL status
sudo systemctl status mysql

# Log in to MySQL
sudo mysql -u root -p

# New User for Workbench
CREATE USER 'senira'@'localhost' IDENTIFIED BY '#######';
GRANT ALL PRIVILEGES ON *.* TO 'senira'@'localhost';
FLUSH PRIVILEGES;
