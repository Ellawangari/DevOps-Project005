# DevOps-Project005

STEPS

**Step 1: Configuring two EC2 AWS instances one named mysql-server and the other mysql-client**
![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/2.PNG)

**Step 2: Installed MySQL Server software  Linux mysql-server**
 ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/4.PNG)
 - Ran the sudo command `sudo systemctl enable mysql`  to enable mysql on the server. 
 
**Step 3: Installed MySQL Client software  Linux mysql-client**
   ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/6.PNG)
 
**Step 4: Added an Inbound rule on client by opening port 3306 using  mysql-server IP address**
   ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/8.PNG)
 
**Step 5: Created a user, added a database and granted the user full privilleges on  mysql-server**
   ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/9.PNG)
   ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/10.PNG)
  
 **Step 6: Configured MYSQL Server to allow connections from remote hosts**
 -Ran the following  command to do so `sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf` and edited the file by replacing 127.0.0.1 by 0.0.0.0
   ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/10.PNG)
   
 **Step 7: Tested to ensure that mysql client linux server could connect remotely to mysql- server without using ssh and use the mysql utility to run sql command to show databases available non the server**
 ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/12.PNG)
 ![alt text](https://github.com/Ellawangari/DevOps-Project005/blob/main/Images/13.PNG)


****I always enjoy getting to learn something new and with [darey.io](https://www.darey.io) PBL(Project Based Learning) Structure it makes it so exicting and easier to learn.****
