# blobs-back

# blobs-config 配置文件
blobs-config的配置文件application.yml中包含账户密码信息，故未上传，其内容如下
<pre>
spring:
  application:
    name: blobs-config
  cloud:
    config:
      server:
        git:
          uri: #repositories 地址
          search-paths: #该repositories 下存储配置文件的路径
          username: #GitHub 用户名
          password: #GitHub 密码
server:
  port: 8000
eureka:
  client:
    service-url:
      defaultZone: http://localhost:7000/eureka/
</pre>
