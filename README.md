# desc
      该项目为Spring4+SpringMVC4+mybatis3模板项目
        
         mybatis逆向工程
            配置文件：resources/config/generatorConfig.xml，修改对应自己的配置
            执行类：utils/GeneratorSqlmap，启动该类中main方法自动生成对应的dao，mapper，model
        
# structure
    src/java/com/duan2ping/
 * controller：控制层
 * dao：持久层
 * mapper：映射文件
 * model：实体类
 * service：业务逻辑层
 * utils：工具类
 * resources：配置文件
