# E-commerce-website-dailyfresh
本项目基于Django框架开发一个B2C电商平台----天天生鲜，平台可实现用户注册、登录、浏览、下单、支付等全部常用功能。
### 重点内容：
- 购物车记录、用户浏览记录、Session的存储——Redis
- 向用户邮箱发送注册激活邮件——以Celery异步操作实现
- 网站优化之首页动态页面静态化——以Celery异步操作实现
- 网站优化之首页缓存——Redis
- 分布式存储系统FastDFS存储网站商品图片——自定义存储器类
- 使用全文搜索框架haystack与搜索引擎whoosh实现商品搜索
- 订单并发库存问题之悲观锁与乐观锁
- 自定义管理器实现快速查询数据
- 采用Django内置的认证系统进行登录校验——自定义用户类、校验装饰器
- 支付宝接口
### 项目页面展示：
![image](https://github.com/haoforward/E-commerce-website-dailyfresh/raw/master/display_images/index.png)
