# 简介
这是自定义的springboot starter  
利用caffeine和redis把数据库查询的结果进行缓存，加快查询速度。

# 技术选型
jdk 8  
springboot 2.2.1.RELEASE  
spring-boot-cache 2.2.1.RELEASE  
spring-boot-redis 2.2.1.RELEASE  
caffenie 2.8.0  
javassist 3.26.0-GA  

# 使用方式
1.引用依赖  
&lt;dependency&gt;  
    &lt;groupId&gt;com.wangtoye&lt;/groupId&gt;  
    &lt;artifactId&gt;double-cache-spring-boot-starter&lt;/artifactId&gt;  
    &lt;version&gt;0.0.1-SNAPSHOT&lt;/version&gt;  
&lt;/dependency&gt;  
  
2.引入其他需要的附属包  
lombok，commons-pool2，jackson-databind，guava等等  
具体demo配置可以参考 [solutions](https://github.com/wangtoye/solutions)  
  
3.使用springboot-cache附带的注解功能进行操作  