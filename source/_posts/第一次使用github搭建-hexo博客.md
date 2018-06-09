---
##title: 第一次使用github搭建 hexo博客
date: 2018-06-01 00:32:43
tags:
---

安装hexo https://www.cnblogs.com/fengxiongZz/p/7707219.html

setp1：安装node.js

setp2: 创建一个仓库 格式为：账户名.github.io(需勾选readme)

setp3: 创建一个文件夹，安装hexo : npm install hexo -g    (hexo -v 检查版本)
		hexo init  初始化文件

setp4: npm install 安装所需文件

setp5: hexo g,首次体验Hexo,hexo s 开启服务器  （hexo server -p 端口号可修改端口）

setp6: 配置Deployment的repo值
		deploy:git
			type:git
			repository:git项目路径
			branch:master

setp7: hexo new post"名字"  创建一文章

setp8: hexo d -g 生成部署到网站