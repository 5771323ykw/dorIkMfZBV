# 旅游推荐系统 python727

## 项目概述

旅游推荐系统是一个基于协同过滤算法的推荐平台，使用Python开发，以Flask框架搭建。该系统旨在为用户提供个性化的旅游信息推荐，同时让管理员能够高效管理旅游信息及用户反馈。

## 技术栈

- 开发语言：Python 3.7.7
- 框架：Flask
- 数据库：MySQL 5.7
- 数据库工具：Navicat 11
- 开发软件：PyCharm

## 功能模块

### 系统角色

#### 管理员

- **登录功能**：管理员通过登录界面进行操作，增强系统的安全性。账号和密码信息存储在数据库中。

- **管理功能**：
  - 用户信息管理：查看、修改和删除用户信息。
  - 景点信息管理：查看、修改和删除景点信息。
  - 景点类型管理：管理景点类型信息。
  - 景点门票管理：更新景点门票信息。
  - 在线反馈查看：查看用户反馈。
  - 系统查看与维护：监控系统运行状态，执行必要的维护。

#### 用户

- **个人信息管理**：用户可以修改个人信息。
- **旅游信息查看**：
  - 查看景点信息。
  - 查看景点门票详情。
  - 阅读旅游资讯。
  - 提交在线反馈。

## 运行环境

- Python 3.7.7
- Flask
- MySQL 5.7
- Navicat 11（可选，用于数据库管理）

## 部署步骤

1. 确保服务器环境符合运行要求。
2. 安装依赖的Python库。
3. 配置MySQL数据库，导入初始数据。
4. 部署应用代码到服务器。
5. 运行Flask应用。

## 目录结构

```plaintext
项目目录/
├── app/
│   ├── __init__.py
│   ├── models.py
│   ├── views/
│   │   ├── __init__.py
│   │   ├── admin_views.py
│   │   └── user_views.py
│   └── templates/
│       ├── admin/
│       └── user/
├── venv/
├── requirements.txt
└── run.py
```

## 核心亮点

- **个性化推荐**：基于协同过滤算法，为用户提供精准的旅游推荐。
- **灵活的管理界面**：管理员可以方便地管理用户和旅游信息。

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img14.360buyimg.com/ddimg/jfs/t1/290764/13/20497/24032/68d530c8F288be5fc/73b86e4dad6aabcc.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/293954/35/25603/54987/68d530c8F9a9ba24e/4f51702a3e406275.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/331956/9/17288/169374/68d530c8Fba00313f/d1eb6a308bcc1871.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/351259/39/7427/44384/68d530c9F21d43fed/fb09bab978672f64.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/331276/21/17301/12733/68d530c9Fb493458a/b8ce38107e5199ff.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/331089/32/17212/20264/68d530c9F65568eac/01944f79c785a0dd.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/334778/5/17124/16481/68d530c9F376735ab/c5922afc56229661.jpg)
