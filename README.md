**扫码 >> 源码商城 获取** ![qrcode_for_gh_1266b4b5294a_258 (2)](https://github.com/user-attachments/assets/45838afd-19a8-4cdc-bdd5-74b9c76fb241)


**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务，项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具：SpringBoot + jdk8 + mysql5.7 + redis + Maven3 + idea2022

系统角色：管理员（商家自己派送）、普通用户

系统功能：管理员（菜品分类管理、菜品管理、套餐管理、员工管理、订单管理等）、普通用户（登录、分类查看、个人信息、查看订单、购物车、下单、钱包等）

#### 2.系统部署

- 创建数据库，导入sql文件（可以通过navicat工具创建）

- 打开idea，导入项目（open->双击项目里的pom.xml）

- 根据本地数据库环境，修改数据库连接src/main/resources/application.yml 8-11行

- window本地启动redis， 默认是无密码的

- 启动项目

- 管理员账号/密码： admin/123456  http://localhost:8099/backend/index.html

- 移动web端：http://localhost:8099/front/index.html， 通过邮箱验证登录。src/main/resources/application.yml中17-19行配置了QQ邮箱的客户端，可以使用，你可以自行修改，修改很简单，自行百度
