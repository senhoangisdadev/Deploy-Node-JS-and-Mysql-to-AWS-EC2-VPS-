# Deploy-Node-JS-and-Mysql-to-AWS-EC2-VPS

## Prepare basic app Node-JS have connect mysql 

- You can clone my basic app here: https://github.com/

## Create new instance
##  2. Install and config MY-SQL  
- Update ubuntu and  Install MY-SQL

    `$ sudo apt update`

    `$ sudo apt install mysql-server`

- Config MY-SQL

    `$ sudo mysql_secure_installation`

- change method authenticated user mysql_native_password

    `$ sudo mysql `

    `mysql> ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '12345678';`

    `mysql> exit`

- test connect mysql

    `$ mysql -u root -p `

    Enter password: 12345678

    `mysql> exit`

##  3. App Node-JS
