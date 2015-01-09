# SpringDemo
这是一个教会大家如何一步步不是springmvc+mybatis+bootstrap+mysql的教程式代码示例

简介:

数据库使用mysql 业务框架使用spring 3.1 持久层框架使用mybatis 页面表现使用bootstrap

step1 : 通过eclipse创建应用,部署在tomcat下,运行,出现正常的首页时,说明创建成功.(请注意:web-info/lib下是否已经自动添加了所有的jar包)

step2:项目右键-myEclipse-Project facets-install spring facet .添加项目对于spring的支持,值得注意的是,这里一定要添加presentation持久化包,否则后边需要连接数据库编程时还需要重新导入哦.

step3:在web-info/web.xml中添加对于spring的支持.

step4:如果想使用springmvc的注解形式开发,则需要修改applicationContent.xml文件,添加注解的spring类支持.到此为止,就能进行简单的示例开发了

step5:如果你的应用需要数据库支持,则需要修改applicationContent.xml文件添加对于数据库的支持,例如数据源/事务等.
