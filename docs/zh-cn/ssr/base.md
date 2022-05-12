# SAGIRI简介
这是一段关于SAGIRI基础介绍
## SAGIRI官方介绍
```
基于Sqlalchemy的异步ORM
权限管理系统
频率限制模块
错误重发模块
丰富的功能
可视化管理模块
基于loguru的日志系统
基于alembic的数据库版本管理功能
开始使用
使用前准备
不同于老版的SAGIRI-BOT，新版的SAGIRI-BOT使用了ORM框架，这意味着可以很方便的将项目适配各种不同的数据库

目前仅适配sqlite，使用mysql等产生的bug暂不在修复考虑范围内，但仍可提出ISSUE，在之后可能会修复
从v4迁移过来的用户请先进行数据库备份
配置数据库链接
sqlite: sqlite+aiosqlite:///filename.db
mysql: mysql+aiomysql://username:password@localhost:3306/dbname
注意：请自行安装对应的异步库，如aiomysql、aiosqlite等
下载 mirai-console 并配置 mirai-api-http ，这些都可以在 mirai 项目中找到
若上一条不会配置，请考虑使用 mirai-console-loader 加载器进行配置
打开 config_demo.yaml，配置好个人信息，并将文件更名为 config.yaml，配置说明见config文件参数说明
打开 alembic.ini ，将 sqlalchemy.url 更换为自己的连接（不要使用异步引擎否则会报错）（如sqlite:///data.db）
如何启动
首先，启动 mirai-console，确保其正常运行且插件正常安装 在文件夹下执行 python main.py 即可 
```