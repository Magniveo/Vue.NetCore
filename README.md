#### The framework is an open-source free product. If you purchase a system developed by a third-party individual or enterprise using this framework, any disputes arising are unrelated to this framework. The framework does not provide after-sales service or technical support. Please be cautious. The official and only release channel is http://www.volcore.xyz/


## Vue + .NetCore front-end and back-end separation, a different rapid development framework (providing Vue2/Vue3 versions)

## Framework Core
 - Rapid development (basic functions are all generated by the code generator)
 - Supports customization of front-end and back-end business code extension. The back-end provides a large number of common extensions and utility classes
 - Nearly 300 extension methods and properties are provided for front-end and back-end. Developers can write custom business code extensions based on these functions
 - Code generation (the code generator can directly generate front-end and back-end business code for main/subordinate tables, with over 30 properties that can be configured online to generate the code)
 - Front-end table automatically converts key/value
 - Front-end form select/checkbox automatically binds data sources, no need to write any code
 - Supports the automatic generation of front-end and back-end code for one-to-one (master-slave) tables, and supports automatic data source binding and business code extension, without the need to write any code
 - Supports custom extensions for one-to-many subordinate tables (unlimited subordinate table types and quantities). The use of extensions for one-to-many subordinate tables can be easily achieved
 - If you can get started with the framework, you can experience the feeling of not having to work 996 and not losing your hair ^_^

## 框架适用范围 
 - Front-end and back-end separation projects
 - Writing various back-end RESTful API interfaces. The basic back-end code is generated by the code generator, and you can continue to develop business on the generated code
 - Front-end form development (you can directly check out the demo to get started)
 - Collaborating with apps for H5 or full H5 development
 - Mobile development, apps, WeChat mini-programs (uniapp), as described below
 - Continuing to customize the development of the code generator based on the existing code generator functionality to address repetitive work
## Framework Development Dependencies
 - Back-end: VS2019, vs2022, .NetCore3.1, .Net6, EFCore3.1/6.0, SqlSugar, JWT, Dapper, SignalR, Quartz.Net, Autofac, SqlServer/MySql/PGSql/Oracle, Redis
 - Front-end: VsCode, Vue2/Vue3 (requires installation of nodejs), Vuex, Axios, Promise, Element UI, Element Plus
 - As of October 2023, support for sqlsugar is available. See the back-end project code Vol.Net.SqlSugar
## Links

## [vol框架视频](https://www.cctalk.com/m/group/90268531)
## [vol框架企业版](http://pro.volcore.xyz/)
## [NET视频教程(微软MVP-ACE录制)](https://space.bilibili.com/525836469)
## [元讯趣编程交流社区](https://www.qubcedu.com/)

#### 框架文档
vue3版本: [http://v2.volcore.xyz/document/guide](http://v2.volcore.xyz/document/guide) <br> 
vue3版本: [http://www.volcore.xyz](http://www.volcore.xyz) <br> 
演示地址2: [http://120.48.115.252:9990/](http://120.48.115.252:9990/) <br> 
App、H5、微信小程序: [http://v2.volcore.xyz/app/guide](http://v2.volcore.xyz/app/guide) <br> 

#### 2023.10增加sqlsugar适配
不是简单的增加sqlsugar而是重写后台，增加框架后台sqlsugar版本并独立维护 <br> 
sqlsugar: [https://www.donet5.com/](https://www.donet5.com/)

## 2023.05.13增加审批流程分支、条件功能
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/flow.png)  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/flow2.png)  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/flow3.png)  


## 框架移动端（uniapp）已发布,同样全自动生成代码,扫描小程序二维码即可查看

![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/qrcode.png)  

![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/app-01.png)  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/app-02.png)  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/m001.png)  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/m002.png)  
## 框架已支持Vue3版本
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/v3.png)  
## 框架已增加低代码设计器
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/fd01.png)  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/fd02.png)  
## 框架2.0已更新(部分新增功能截图)
增加切换皮肤功能
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/h.png)  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/home_them.png)  
增加可复用的后台请求参数校验
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/validator.png)  
增加树形菜单与代码生成页面使用
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/x7tree.png)  
增加文本编辑器直接发布静态页面功能
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/editor.png)  
一对一多从表显示(只需要少量代码就可完成成，其他都由代码生成器生成)
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/m1.png)  
表合并显示 (只需要几行代码完成代码生成器生成的页面实现扩展)
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/span.png)  
从图上传图片 (只需要几行代码完成代码生成器生成的页面实现扩展)
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/p1.png)  
一对多从表(不限从表数量)扩展
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/multi.png)  
图表
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/charts.png)  



## 1、只读基础表单
整个只读的基础表单的所有前后端代码，全部由代码生成器生成，代码生成器中几乎不需要配置，并支持并后端业务代码扩展，直接生成代码后，配置菜单权限即可
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/table1.png)  

## 2、自动绑定下拉框数据表单
整个自动绑定下拉框数据表单的所有前后端代码，全部由代码生成器生成，并支持并后端业务代码扩展，在代码生成器中只需要指定数据源编号，页面加载时会根据编号自动加载数据源并绑定  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/table2.png)  

## 3、启用图片支持、审核表单
整个启用图片支持、审核表单的所有前后端代码，全部由代码生成器生成，并支持并后端业务代码扩展，审核功能需要在菜单配置权限、代码生成器中勾选启用图片支持
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/table3.png)  

## 4、高级查询
整个表单的所有前后端代码，全部由代码生成器生成，并支持并后端业务代码扩展，查询字段、类型(下拉框、日期、TextArea等)、所在行与列都由代码生成器完成，不需要写任何代码  
    ![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/tablesearch4.png)  
    
## 5、主从表新建、编辑
主从表新建、编辑所有前后端代码，全部由代码生成器生成，并支持并后端业务代码扩展，新建、编辑从表配置、字段、类型(下拉框、日期、TextArea等)、所在行与列、字段是否只读、标签显示的长度等都由代码生成器完成，不需要写任何代码  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/editTbale2.png)  


## 6、excel导入
excel导入整个页面都由代码生成器生成，导入的字段、字段是否必填，下载模板也由代码生成器上配置(自己根据实际需要决定是否采用此方法)，导入时会验证是否为空与数据的合法性，逻辑校验自己实现扩展方法即可  
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/importTable1.png)  


## 7、H5开发
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/h5.jpg)  

## 8、权限分配
目前只实现了对用户的角色的Action进行权限分配
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/auth.png)  

## 9、代码生成器
代码生成器提供了20多种可配置的属性，可灵活配置显示、查询、编辑、导入、导出、主从关系等功能<a href="http://132.232.2.109/document/coder">点击看代码生成器文档</a>
![Home](https://github.com/cq-panda/Vue.NetCore/blob/master/imgs/coder.png)  

其他功能。。。。。

## 框架预览
 - 框架内置了大量的通用组件可直接使用,并内置了基于本框架定制开发的代码生成器，尽量避免重复性代码编写。
 - 框架不仅仅是快速开发，更多的是倾向于业务代码扩展的编写与代码规范。
 - 如果有什么问题或建议，提issue或加QQ：283591387

 - QQ2群：913189178
 - QQ3群：743852316
 - 
 - vue3地址：http://www.volcore.xyz
 - vue2地址：http://v2.volcore.xyz
 - 帐号：admin666密码：123456（本地超级管理员帐号：admin密码123456)
 - github地址：https://github.com/cq-panda/vue.netcore
 - gitee码云：https://gitee.com/x_discoverer/Vue.NetCore
 - 框架文档：http://v2.volcore.xyz/document/guide
 - 框架更新日志：http://v2.volcore.xyz/document/log
 
