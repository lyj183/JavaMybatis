参考：
https://www.cnblogs.com/hyyq/p/7087620.html

一、逆向工程main方法运行，使用MyBatis Generator自动生成实体、mapper和dao层
1、在本地MySql数据库sampledb，建立新表mybatisTest
   id 	bookName
   1	计算机网络
   2	软件工程
   3	世界经济
   4	国际经济
2、按照链接文章配置文件
   generatorConfig1.xml (运行的时候要改成generatorConfig.xml)
   jdbc.properties
   GenMain.java
3、运行GenMain.java，生成文件

二、数据库反向生成java
1、在本地MySql数据库sampledb，建立新表apps
2、下载mysql jdbc驱动mysql-connector-java-5.1.38.jar，放置在固定位置
3、按照链接文章配置文件
   generatorConfig.xml
   jdbc.properties
   GenMain.java
4、点击右侧的MavenProjects，在Plugins里找到mybatis-generator:generate，右键Run Maven Build

