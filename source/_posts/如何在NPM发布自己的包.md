title: 如何在NPM发布自己的包
author: leeyasuo
tags: []
categories: []
date: 2019-09-17 13:18:00
---
#### 注册

	https://www.npmjs.com/signup 到该网站注册一个自己的npm账号

#### 对包 package.json 的要求

	{
  	"name": "npm-test",
  	"version": "0.0.1"
    }
#### 终端登录
	npm config set registry http://registry.npmjs.org
	然后 npm login 会要求你输入用户名、密码和邮箱，根据你注册npm的时候输入
    
#### 发布
	npm publish