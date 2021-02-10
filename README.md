**[MyBatis generator](http://mybatis.org/generator/)**

1. 利用MyBatis generator生成代码
   
  ```shell
  java -jar mybatis-generator-core-1.3.2.jar -configfile generatorConfig.xml -overwrite
  java -jar mybatis-generator-core-1.3.2.jar -configfile generateConfig.xml -overwrite
  ```

2. Mybatis mapper.xml
   Mybatis中namespace用于绑定dao接口，dao接口的方法对应mapper中的sql语名
   
3. [MyBatis GeneratorXML Configuration File Reference](http://mybatis.org/generator/configreference/xmlconfig.html)

   
   
   
   
   **注意**：
   
   	1. 以上 `jar` 包文件适用于 MySQL 5.7 版本的DB，对于 MySQL 8.0 请去官网下载 对应的数据库驱动，或者在 [Maven 仓库](https://mvnrepository.com/artifact/mysql/mysql-connector-java)中下载对应的 `jar` 文件使用。
    	2. 也可以找到最新版本的 `mybatis-generator-core-1.3.2.jar`  在 [Maven仓库](https://mvnrepository.com/artifact/org.mybatis.generator/mybatis-generator-core) 中。
   
   未完待续... ...