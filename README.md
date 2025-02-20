# 基于SpringBoot+Vue实现的电影院售票
### 一、相关技术
- 后端：`Java`、`JavaWeb` / `Springboot`、`Shiro`、`quartz`、`druid`。
- 前端：`Vue`、`HTML` / `CSS` / `Javascript` 等。
- 数据库：`MySQL8.0`

### 二、相关软件（列出的软件其一均可运行）
- `IDEA`
- `Eclipse`
- `Visual Studio Code(VScode)`
- `Navicat`
- 等

### 三、功能描述
基于SpringBoot+Vue实现的电影院售票系统整体设计了用户、管理员两个角色。
详细代码介绍和截图移步：https://www.notmaker.com/detail/4d916704b3d842d3b8ae1067b14cbe88


**普通用户功能：**
1. 登录
2. 注册
3. 电影搜索
4. 购票
5. 选座
6. 电影榜单
7. 即将上映
8. 热播影片


**管理员功能：**
管理员可进行系统管理，影院管理、影片管理、影厅管理、订单管理、用户管理、角色权限管理

影院管理：影院信息管理：可对影院的名称、开放时间、影厅类型、介绍等进行管理

**影片管理**

电影信息管理：对电影进行新增、修改、搜索、删除、所属类型管理

电影类别管理：可对电影类别进行新增、修改、删除

**影厅管理**

影厅信息管理：可对电影院的影厅进行新增、修改、删除、座位管理，可设置座位是否可用，可根据名称、类别进行搜索

场次信息管理：可对影厅上映的电影场次进行新增、修改、删除、以及查看该场次座位预定情况

**订单管理**

订单信息管理：对用户订单进行管理

**用户管理**

用户信息管理：对电影院系统所有用户进行管理

**角色权限管理**

角色信息管理、权限信息管理
