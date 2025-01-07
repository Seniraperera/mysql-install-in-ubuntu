# Update package list
```bash 
sudo apt update
```

# Install MySQL Server
```bash 
sudo apt install mysql-server
```

# Secure MySQL installation
```bash 
sudo mysql_secure_installation
```

# Start and enable MySQL service
```bash 
sudo systemctl start mysql
sudo systemctl enable mysql
```

# Check MySQL status
```bash 
sudo systemctl status mysql
```

# Log in to MySQL
```bash 
sudo mysql -u root -p
```

# New User for Workbench
```bash 
CREATE USER 'senira'@'localhost' IDENTIFIED BY '#######';
GRANT ALL PRIVILEGES ON *.* TO 'senira'@'localhost';
FLUSH PRIVILEGES;
```
