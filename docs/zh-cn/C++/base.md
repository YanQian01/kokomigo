# Yunzai基本介绍
这是一段关于YunzaiBot的基础介绍

## 关于Yunzai服务
```
Yunzai-Bot
云崽，原神qq群机器人，通过米游社接口，查询原神游戏信息，快速生成图片返回

项目仅供学习交流使用，严禁用于任何商业用途和非法行为

使用方法
环境准备： Windows or Linux，Node.js（版本至少v14以上），Redis

Linux环境一键搭建，Windows按下面的就行，安卓手机搭建

1.克隆项目
git clone https://github.com/Le-niao/Yunzai-Bot.git
cd Yunzai-Bot

用cnpm安装
npm install -g cnpm --registry=https://registry.npmmirror.com
cnpm install

2.首次运行，按提示输入完成配置登录
node app

3.需要后台运行的，停止现在的输入下面命令
npm start
操作指令
#帮助 查看命令说明，下面详细指令展示

其他说明，如何获取cookie，抽卡记录说明，更新日志

```


## 关于miaomiao-Plugin
```
#Miao-Plugin说明

Miao-Plugin是一个Yunzai-Bot的升级插件，提供包括角色查询等升级功能。

一些实验性的新功能因功能可能不稳定，或者Yunzai-Bot存在类似功能，会在Miao-Plugin以插件形式提供，可按需选用。

部分非重复功能会在逐步稳定之后会合并入Yunzai-Bot。

具体功能可在安装插件后 通过 #喵喵帮助 进行查看。如需进行设置可通过 #喵喵设置 命令进行管理。

使用说明
Miao-Plugin需要最新版本的Yunzai-Bot，请确认Yunzai-Bot已升级至最新版

安装与更新
直接将miao-plugin放置在Yunzai-Bot的plugins目录下，重启Yunzai-Bot后即可使用。

推荐使用git进行安装，以方便后续升级。在BOT根目录夹打开终端，运行

git clone https://gitee.com/yoimiya-kokomi/miao-plugin.git ./plugins/miao-plugin/
进行安装。如需更新，在BOT文件夹打开终端，运行

git -C ./plugins/miao-plugin/ pull
```
