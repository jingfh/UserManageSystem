员工管理系统（SSH+MySQL）项目介绍

（1）功能介绍：

	* - 增删改查员工。
	* - 增删改查页面显示当前用户信息（session里获取）
	* - 点击button，倒序，正序显示员工列表
	* - 在list页面模糊查询（按姓名查询）
	* - 分页功能
	* - 部分前端代码


（2）运用的知识：
spring，springmvc，hibernate，mysql


	* - 基本数据库知识MySQL
	* - Spring+SpringMVC+Hibernate
	* - （重点）框架的MVC设计模式的应用
	* - （重点）分页查询
	* - 部分前端代码（css的应用）



 (3)项目构建 
  项目分包：MVC架构

	* controller:控制层，写SpringMvc的action
	* dao：数据层，Hibernate对数据的操作
	* entity：实体类和相应的*.hbm.xml(hibernate的类配置文件)
	* servicesDao：业务Dao，对单笔Dao进行业务封装
	* utils：工具类


（4）数据库

	*系统管理员
   	user(id,username,password,gender)
	*员工
   	employee(t_id,empname,empage,empsalary)
	
	
	
