# Installation Guide 

## For Mac

1. Download MySQL Installer from https://dev.mysql.com/downloads/mysql/ and execute it.

![step1](Step1.png)

2. Make sure you remember the password you enter here

![step2](step2.png)

3. Go to the terminal and to go to the path where your installer is in it should be `usr/local/mysql/bin`

![step3](step3.png)

4. Enter `./mysql -u root -p` to go to the mysql  
![step4](step4.png)

5. it will ask for the password enter the password you entered earlier.  

![step5](step5.png)

6. Create database called test then exit mysql  

![step6](step6.png)

7. go to dbeaver and connect to MySQL 

![step7](step7.png)

8. Enter the name of the database you created and the password 

![step8](step8.png)





## For Windows 

1. Download MySQL Installer from https://dev.mysql.com/downloads/mysql/ and execute it.

![step1](Step1.png)

2. Make sure you remember the password you enter here

![step2](step2.png)

3. search for vriable enviroments in windows and open this 

![step3](step3-win.png)

4. write path in the variable and the path for the installer in the value the path should be something like this `C:\Program Files\MySQL\MySQL Shell 8.0\bin`

English: 

![step4](step4-win2.png)

![step5](step5-win.png)

Arabic: 
![step3](step3-win.png)
![step3](variable2.png)
![step4](step4-wind.png)

5. search for mysqlshell and open it 

![step6](step6-win.png)

6. Enter the following command to enter mysql 

- `sql\`
- `connect root@localhost\`

7. when you are in mysql create database by using this command 

- `create database test;`

8. go to dbeaver and connect to MySQL 

![step7](step7.png)

9. Enter the name of the database you created and the password 

![step8](step8.png)


