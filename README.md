# PetHospitalManageSystem
springboot宠物医院管理系统
技术栈:springboot +spring+mybatis+ jquery+ + MySQL + Echarts + log4j+Maven
环境IDEA（或eclipse）+ JDK 1.8 + MySQL 8 + Tomcat 8+Maven


启动步骤：
1.将项目源码导入到idea或eclipse开发工具中
2.mysql8新建数据库，名称为prodata，将sql语句粘贴进去执行（项目运行必须为mysql8版本）
3.打开项目配置文件src/main/resources/application.properties，修改8-10行，改为您自己的数据库ip、账户和密码
4.右击src/main/java/com/phms/PhmsApp.java，运行springboot项目
5谷歌浏览器打开，访问  http://localhost:8086/  各角色账户密码如下
管理员  admin/123456
用户     user/123456
医生     医生1/123456
