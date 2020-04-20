一、Java入门
			

变量与数据类型
			数据类型转换
			ASCII码表
			

循环语句
			方法重载
			成员变量默认值
			构造方法
			

JavaBean
			ArrayList
			

静态方法
			继承
			抽象类与抽象方法
			接口，多态
			

final关键字
			权限修饰符
			

集合
			泛型

List子类
				ArrayList集合
				LinkedList集合
			

Set子类
				HashSet集合
				LinkedHashSet
			

可变参数
			Comparator比较器
			

异常
			异常处理方式
				抛出异常throw
				声明异常throws
				捕获异常try…catch

自定义异常类			线程类
			

线程同步
				同步代码块
				同步方法
				Lock锁
			

线程状态
			等待与唤醒
			线程池
			

lambda表达式
			

文件过滤器Filter
			字节流与字符流
			

Properties类
			序列化
			反序列化
			

网络通信协议
			IP地址
			端口号
			Socket类
			TCP通信分析图解

函数式接口
				Supplier接口
				Consumer接口
				Predicate接口 
			Function接口 

Stream流
			

方法引用
	通过对象名引用成员方法
	通过类名称引用静态方法
	通过super引用成员方法
	通过this引用		成员方法
	类的构造器引用
		数组的构造器引用
			

反射
	获取Class对象的方式：
	Class对象功能：
		Field：成员变量
		Constructor:构造方法

Method：方法对象
			

注解
	作用分类：
自定义注解
			

JDBC
	JDBCUtils
	JDBC控制事务
	数据库连接池
	JDBCUtils连接池工具类
	Spring JDBC

二、java-web
			

软件架构
			标签学习
			CSS
			

JavaScript
				ECMAScript
				DOM
				BOM
				事件
			

Bootstrap
				响应式布局
			

XML
				语法
				约束
				Jsoup
			

Servlet
			ServletContext
			

HTTP
				请求消息数据格式
				响应消息
			

Request
			Response
			Cookie
			Session
			

JSP
				指令
				注释
				内置对象
				JSP脚本
				EL表达式
				JSTL
		

MVC开发模式
			三层架构：软件设计架构
			

Filter
			Listener监听器
			

JQuery
				选择器
				DOM操作
				动画
				插件
			

AJAX
			

JSON
				JSON数据和Java对象的相互转换
			

Redis
				NOSQL
				Redis应用场景
				Redis命令操作
				Redis持久化
				

Java客户端 Jedis
				Jedis连接池
			

Maven
		maven项目构建流程
		maven工作目录结构
		Maven 指令的生命周期      maven依赖管理
							scope
	pom配置
	Maven依赖调解原则
	

Maven私服
	nexus仓库
	将项目发布到私服
	从私服下载jar包
	把第三方 jar 包放入本地仓库或私服

三、Java框架
			

Mybatis
	mybatis环境搭建
	

​					SqlMapConfig.xml
​	properties
​	typeAliases（类型别名）
​	mappers（映射器）

​					mybatis连接池
​				

​					mybatis动态sql
​				

​					mybatis 多表查询
​				

​					mybatis一级缓存和二级缓存
​				

​					mybatis延迟加载
​				

​					mybatis常用注解
​					@Results注解
​			

Spring
		spring 的依赖注入
				

​					常用注解
​	用于创建对象的
​	用于注入数据的
​	用于改变作用范围的
​	配置
​				

​					spring整合Junit
​				

​					AOP	AOP相关术语
​	AOP的xml配置	AOP的注解
​				

​					spring事务隔离
​		事务的传播行为
​		事务的xml配置
​		事务的注解配置

SpringMVC
	常用的注解
	RequestMapping注解
	RequestParam注解
	RequestBody注解
														PathVariable注解
	RequestHeader注解
	CookieValue注解
														ModelAttribute注解
	SessionAttributes注解
				

​						SpringMVC的异常处理
​				

​						SpringMVC拦截器
​			

SSM
			

SpringData JPA
	JPA与hibernate的关系
				

​								JPA操作步骤
​				

​								JPA注解
​				

​								JPA配置文件
​				

​								Specification动态查询
​			

SpringBoot
	SpringBoot核心功能
				

​						SpringBoot配置文件类型
​				

​						application.yml配置文件
​				

​						SpringBoot配置信息的查询
​				

​						配置文件与配置类的属性映射
：使用注解@Value映射																						使用注解@ConfigurationProperties映射
​			

idea快捷键