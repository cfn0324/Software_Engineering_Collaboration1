# 学生作业管理系统

### 数据库

1. 首先将本地数据库打开。一般情况下是在服务里面,找到MySQL或者MySQL80，双击进去后点击启动按钮
2. 用Navicat或者MySQL Workbench打开T071并执行内部脚本

### 后端

1. 使用IDEA打开back文件
2. 在IDEA里面依次点击设置，构建、执行、部署，构建工具，Maven
3. 将Maven主路径设置为...\xm1\maven,
4. 将用户设置文件设置为...\xm1\maven\conf\settings.xml
5. 将本地仓库设置为...\xm1\maven\repository
6. 应用确定后点击IDEA右边的m，点击增量重新加载所有Maven项目
7. 将src\main\java\resources\application.yml里面的数据库密码改成自己的数据库密码
8. 执行src\main\java\com\SpringbootSchemaApplication文件

### 前端

1. 首先确保nodejs版本是13（推荐使用nvm管理nodejs版本）

2. 使用vscode打开front文件

3. 在终端中依次输入以下命令

   ```shell
   npm i -g node-gyp
   npm i -d
   npm config set sass_binary_site=https://npm.taobao.org/mirrors/node-sass
   npm run serve

