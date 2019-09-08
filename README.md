JD.BooksAPI

介绍

ASP.NET Core教程示例 - 书籍管理项目.

软件架构

ASP.NET Core / Web API / MongoDB

安装教程

1. 安装配置 MongoDB
2. 配置数据库
在MongoDB存储数据的目录打开命令行界面。 运行以下命令
mongod --dbpath <data_directory_path>
打开另一个命令行界面实例。 通过依次运行以下命令
1). mongo
2). use BookstoreDb
3). db.createCollection('Books')
4). db.Books.insertMany([{'Name':'Design Patterns','Price':54.93,'Category':'Computers','Author':'Ralph Johnson'}, {'Name':'Clean Code','Price':43.15,'Category':'Computers','Author':'Robert C. Martin'}])
3. 打开项目:
Visual Studio打开JD.BooksAPI.sln.
4. 运行项目:
F5运行即可.

使用说明

项目功能菜单:
书籍管理, 查看书籍信息.

参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request

![输入图片说明](https://images.gitee.com/uploads/images/2019/0908/171218_fbf3f558_2265734.png "JD.BooksAPI1.png")
![输入图片说明](https://images.gitee.com/uploads/images/2019/0908/171227_6f1b2818_2265734.png "JD.BooksAPI2.png")