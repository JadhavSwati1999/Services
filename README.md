
# Services

1. **FTP(file transfer protocol)[port 21]**


FTP is primarily used for transferring files between client & server over TCP/IP network /protocol

### Q Difference between SCP(secure copy) & FTP(file transfer protocol)

### **SCP (secure copy)**

- While SCP supports SSH key-based authentication which involves generating public & private key pairs & security exchanging data between client & server
- It uses port 22 & SSH protocol
- More secure than FTP

### FTP(file transfer protocol)

- Support different authentication mechanism which includes anonymous login via username & password, FTP does not encrypt credentials
- It uses port  21 & FTP protocol
- Less secure than SCP

### Steps

Sudo apt update

Sudo systemctl status vsftpd

Sudo apt install vsftpd

Sudo apt enable vsftpd

Sudo apt start vsftpd

Sudo apt status

cd /etc /vsftpd.conf

cd / etc/vsftpd/vsftpd.conf

### 2.Nginx

Nginx is a high-performance web server & reverse proxy server & it is also known for event-driven architecture it will efficiently handle large no of requests while consuming minimal system resources

### Steps

Sudo yum install nginx 

Sudo systemctl enable nginx 

Sudo systemctl start nginx 

Sudo systemctl status nginx 

cd nginx

cd etc/nginx/nginx.conf

### 3.MariaDB

it is relational database system that is compatible MySQL it is designed for high performance , scalability, relability

### Steps

Sudo apt install mariadb server

Sudo systemctl enable mariadb

Sudo systemctl start mariadb

Sudo systemctl status mariadb

Sudo systemctl disable mariadb

Sudo systemctl stop mariadb

Sudo mysql_server_installation

Sudo mysql-u root -p   -to access the db

SHOW DATABASE ;    - to view the database

exit     - to come out

cd /etc/mysql/my.any    -conf file of mariadb/path

### 4.Tomcat : java web application host

Sudo apt install tomcat?

/etc/tomcat9/server.xml -conf file of tomcat

/etc/tomcat9/login.properties

### 5.NFS(network file system) port no:2049

It is distributed file system protocol that allows clients to access file & directory stored on remote server over a network as if they were local files

config file  → /etc/exports

### Installation

Sudo apt-get

Sudo apt install nfs-kernel-server

create a dir mkdir -p /mnt/sharedrepo

cd  /etc/exports

/mnt /shared_repo

sudo mount serverip: /mnt/shared_repo  /mnt/localmount
