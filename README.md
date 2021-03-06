# 自述文件

## 一、概述

###  1、 编写目的

+  为项目的系统的开发设计的依据与指导。
+  为参与该项目的编程人员提供依据；
+  为修改、维护提供条件；
+  项目负责人将按计划书的要求布置和控制开发工作全过程；
+  项目质量保证组将按此计划书做阶段性和总结性的质量验证和确认。

### 2、 读者对象

+  项目开发人员，特别是编程人员；
+  软件维护人员；
+  技术管理人员；
+  执行软件质量保证计划的专门人员；
+  参与本项目开发进程各阶段验证、确认以及负责为最后项目验收、鉴定提供相应报告的有关人员。
+  合作各方有关部门的负责人；项目组负责人和全体参加人员。

### 3、 注意事项

+  权限审查：此文档仅供技术部功能组内部使用。
+  保存备份：此文档仅在服务器上作修改，不允许本地备份。
+  该文档采用 markdown 编写规范，建议使用markdownPad或相关编辑工具查看和修改。


## 二、 文档说明

**文档修改纪录**

| **日期**   | **作者**     | **版本** | **备注说明**                   |
|------------|------------  |----------|--------------------------------|
| 2018/6/20  | xiexie1993   | V1.1     | 新建                           |

## 三、目录结构

~~~

./                    根目录
├─ Instant_Messaging_Solution             即时通讯系统类方案
│  ├─ IM_socket_Architecture_Solution.md    基于socket的tcp即时通讯系统架构方案
│  └─ ...              
├─ User_Authentication_Solution           用户认证系统类方案
│  ├─ Token_User_Auth_Solution.md           基于Token的用户认证系统架构方案
│  └─ ...              
├─ User_Authorization_Solution            用户授权类方案
│  ├─ 
│  └─ ...
├─ README.md          自述文件
└─ ...

~~~

## 四、参考资料

+ [1千用户与1千万用户的网站系统架构区别？](https://blog.csdn.net/zqftisson/article/details/51777042)
+ [权限管理——用户认证和用户授权](https://blog.csdn.net/xdd19910505/article/details/51926540/)
+ [APP授权设计：如何让用户不反感并同意授权](http://baijiahao.baidu.com/s?id=1596638869187800507&wfr=spider&for=pc)
+ [用户中心系统设计](https://www.cnblogs.com/tylercao/p/8053404.html)
+ [授权机制](http://open.weibo.com/wiki/%E6%8E%88%E6%9D%83%E6%9C%BA%E5%88%B6%E8%AF%B4%E6%98%8E?sudaref=www.baidu.com&display=0&retcode=6102)
+ [分布式架构之系统拆分](https://blog.csdn.net/zzz34k/article/details/52576731)