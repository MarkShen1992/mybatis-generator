**[MyBatis generator](http://mybatis.org/generator/)**

1. 利用MyBatis generator生成代码
    
  ```shell
  java -jar mybatis-generator-core-1.3.2.jar -configfile generatorConfig.xml -overwrite
  java -jar mybatis-generator-core-1.3.2.jar -configfile generateConfig.xml -overwrite
  ```

2. Mybatis mapper.xml
   Mybatis中namespace用于绑定dao接口，dao接口的方法对应mapper中的sql语名
3. [MyBatis GeneratorXML Configuration File Reference](http://mybatis.org/generator/configreference/xmlconfig.html)

   未完待续... ...