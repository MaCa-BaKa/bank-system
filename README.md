# 34-银行管理系统

RuoYi框架  前后端不分离

**1、系统环境**

- Java EE 8
- Servlet 3.0
- Apache Maven 3

**2、主框架**

- Spring Boot 2.2.x
- Spring Framework 5.2.x
- Apache Shiro 1.7

**3、持久层**

- Apache MyBatis 3.5.x
- Hibernate Validation 6.0.x
- Alibaba Druid 1.2.x

**4、视图层**

- Bootstrap 3.3.7
- Thymeleaf 3.0.X



#### **用户端功能**

1.首页轮播图展示,点击图片快捷跳转至相应功能页
2.通知公告增删改查
3.银行卡管理: 可进行银行卡申请  补卡  挂失操作
4.理财产品:  购买理财产品
5.资金交易记录: 查看相对应的  存取款、转账、消费、理财购买等的列表记录
6.生活缴费管理: 可进行手机费、学杂费、电费、房租、彩票等的消费操作

7.贷款管理: 可进行申请贷款操作
8.留言板: 添加留言板功能

9.个人中心: 个人资料查看和修改



#### 审核人员端功能

1.首页: 展示审核和待审核状态情况分析图以及系统通知
2.公告: 增删改查
3.银行卡管理: 对用户的银行卡申请进行处理
4.理财产品列表
5.资金交易管理: 对用户的每笔资金交易进行审核或者驳回
6.贷款管理: 对用户的贷款请求进行操作

7.留言板: 添加留言板功能

8.个人中心: 个人资料查看和修改



#### 管理端功能

1.首页: 展示当日交易总金额、以及用户数量
2.系统管理: 用户管理 角色管理 菜单管理 通知公告 日志管理
3.银行卡管理: 可进行银行卡 锁卡 和 解锁 操作
4.理财产品:  增删改查 以及 查看购买记录
5.资金交易记录: 查看存取款、转账、消费、理财购买等的列表记录
6.生活缴费管理: 可进行手机费、学杂费、电费、房租、彩票等的消费操作

7.贷款管理: 可进行申请贷款请求的操作处理
8.留言板: 添加留言板功能

9.个人中心: 个人资料查看和修改



### 用户端功能图

![银行登录页](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行登录页.jpg)

![银行用户1](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户1.jpg)

![银行用户2](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户2.jpg)

![银行用户3](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户3.jpg)

![银行用户4](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户4.jpg)

![银行用户5](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户5.jpg)

![银行用户6](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户6.jpg)

![银行用户7](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户7.jpg)

![银行用户8](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户8.jpg)

![银行用户9](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户9.jpg)

![银行用户10](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户10.jpg)

![银行用户11](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行用户11.jpg)

### 审核人员端功能图

![银行审核1](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行审核1.jpg)

![银行审核2](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行审核2.jpg)

![银行审核3](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行审核3.jpg)

![银行审核4](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行审核4.jpg)

![银行审核5](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行审核5.jpg)

![银行审核6](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行审核6.jpg)

![银行审核7](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行审核7.jpg)

### 管理端功能图

![银行管理1](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行管理1.jpg)

![银行管理2](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行管理2.jpg)

![银行管理3](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行管理3.jpg)

![银行管理4](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行管理4.jpg)

![银行管理5](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/银行管理5.jpg)

绿泡泡MaKaBaca0