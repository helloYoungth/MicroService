# 微服务课程实验
https://github.com/leader-us/Monomer_eShop

- 启动redis镜像：docker run -d -p 6379:6379 --name redis redis:latest
- 启动mysql镜像：docker run -d -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_DATABASE=HPE_APP -e MYSQL_USER=lession -e MYSQL_PASSWORD=mypass -p 3306:3306 --name mysql mysql:5.7
- 启动电商项目程序：java -jar /root/monomer_eshop/target/mono_eshop.jar
- 访问：[http://](http://192.168.18.134:8033/)[192.168.18.134:8033](http://192.168.18.134:8033/)，用户名/密码：guest/111111