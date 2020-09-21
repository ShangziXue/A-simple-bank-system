# bank_management_app

> A Vue.js project by PB17111604 薛尚子

## Build Setup

1. 进入lab3-BankManage\bankManage目录，在命令行中输入下面的命令  

   ```bash
   cnpm install
   cnpm run dev
   ```

2.  打开浏览器，在地址栏输入http://localhost:8080/可以对网页进行访问  

3.  进入lab3-BankManage\bankManage\backEndService目录，在命令行中输入下面的命令 

   ```bash
   python login.py
   ```

4.  前后端启动部署完成 

**注意**(**非常重要**)

1. 具体的requirements请参见**doc/report**中的“**3.1运行环境配置概述**”

2. 当你安装了对应版本的Oracle数据库之后，需要手动将**System**用户（默认的）的密码置为"**db2019**", 否则前后端部署无法成功，因为无法连接到oracle数据库

3. 在build之前，你需要在sqlplus命令窗口中输入用户名和密码登入System用户，用户名为“system", 密码为"db2019”（需要先手动设置），之后在命令行中输入如下命令

   ```bash
   @bank.sql
   @change_sub_bank_name.sql
   @change_employee_name.sql
   @change_customer_name.sql
   ```

   注意以上这几个SQL脚本文件在bankmanage/sql目录下，注意文件的位置，以免不能成功运行这几个脚本文件

   For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
