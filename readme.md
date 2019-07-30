## 尧诚

- Email：[chengy.c@foxmail.com](mailto:chengy.c@foxmail.com)

- 基本信息：男   ---   23岁  

- 工作经验： 2 年

- 期望职位：Java开发工程师

- 联系方式：13133820605

  


## **技能清单**

后端方面：

- 熟悉javaWeb开发、熟练使用Idea、Maven、GIT等软件开发工具；
- 熟悉Spring、Spring MVC、Mybatis等主流开源框架的应用；
- 熟悉分布式框架Dubbo、zookeeper等使用；
- 熟悉缓存redis 、消息中间件RabbitMQ等使用；
- 熟悉Linux系统基础操作；
- 熟悉mysql、oracle数据库。


前端方面：

- 熟悉html、css、js、jquery、Vue、element-UI、bootstrap、ajax等基本使用

- 有良好的产品意识，有责任心和团队精神，善于沟通及合作

  

##   **工作经历**   

2018.01—2019-07     杭州海拍客网络科技有限公司

2017.08—2017.12     南昌飞达商用设备有限公司

java后端开发 \| 研发部  

工作内容：

- 负责系统功能设计、开发、自测、维护，保证线上功能的性能和稳定；

- 根据日常需求、参与需求评审、分析需求、分配功能模块、

- 确定任务后进行test环境开发功能模块、开发完成后与测试同事合作解决bug；

- 项目测试完成后上线 预发环境--- 线上环境发布 --- 项目总结。






## 项目经验

### **1. Hipac运营系统**   

​    2018.01—2019.07

**Hipac** 是一套垂直于母婴领域的B2B2C系统，主要有：admin运营系统、seller后台系统、前台门户系统；

细分模块主要有：登录模块、搜索模块、商品模块、供应商模块、营销活动、购物车模块、订单模块等。

**职责**：本人主要参与了供应商、商品、订单、营销活动等模块的开发和自测，保证项目按时上线。

**商品模块**：新商品审核通过上架后及商品修改后，通过mq异步发送消息给页面渲染服务，生成该商品静态页面。 

**订单模块**：由于分布式系统情况下，订单服务、商品服务会有分布式事务问题，我们采用MQ+本地消息表来解决

**营销活动模块**：针对大促活动可预知高并发的业务，主要使用缓存、MQ等技术进行削峰，尽量将压力放在上游，将数据提前放入缓存等缓解数据库压力，使用定时任务及时更新大促商品放入缓存，利用redis-List特性，将下单信息放入队列，下单时从队列进行左压右取，依次消费，提高系统稳定性。

**● 技术栈:**

**Spring+SpringMVC+Mybatis+springBoot+Dubbo+zookeeper+redis+RabbitMQ+ElasticSearch+ thymeleaf+oss**+**mysql**



### **2.**  **南昌飞达ERP管理系统：**

​      2017.08—2017.12

**南昌飞达ERP管理系统**:是公司内部使用的一套企业信息管理系统，   主要有:人力资源管理、采购管理、物流管理、销售管理、资产管理、资源调度、资源权限管理等模块。

**职责**：人力资源管理、角色管理、资源权限管理、销售管理等模块开发。

**销售管理模块**：通过定时任务，更新当天销售数据持久化到数据库，前台采用Echars进行图表展示；

**权限管理模块**：其中使用SpringSecurity进行安全认证，用户--角色之间、角色--资源权限之间通过中间表关联，结合SpringSecurity通过注解方式指定某些敏感资源只能特定用户访问，从而使不同用户根据其角色访问不同资源。

**● 技术栈: **

**Spring+SpringMVC+Mybatis+redis+maven+SpringTask+SpringSecurity+Echars+mysql**



### 3.高校教务管理系统

​    2017.06—2017.08

**高校教务管理系统：**是为高校开发的一套考评系统。

主要功能模块有：后台选题、出题、评卷打分、考试结果导入导出、前台答题等。

**职责**：研发教务管理系统前后端、开发教务系统考试系统，题目的导入导出，在线遍题、随机出卷、评卷等功能。

**● 技术栈：**

**Spring+SpringMVC+Mybatis+POI +Html +CSS+ jquery+mysql**







## 教育经历



江西现代学院      2015—2018            专业： 软件技术



##  个人荣誉

- 2016年 获 国家励志奖学金
- 2016年 获 江西省“大学生科技创新竞赛””软件设计”专科组一等奖
- 2017年 获“大学生移动互联网站设计”三等奖



### 自我评价

-   Java基础扎实，对新技术可以快速上手，有查官方文档的习惯
-  善于沟通交流，乐于和同事分享技术，能够协助同事解决问题
-  对事情认真负责，能吃苦受累，有很强的责任心和团队意识



##  致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。