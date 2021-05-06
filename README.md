# Sentinel持久化到Nacos配置中心
基于Sentinel 1.8.0改造。 将authority（授权规则）、degrade（降级规则）、flow（流控规则）、param（热点规则）、system（系统规则）五种规则持久化到Nacos中。 另外还增加网关的两个（api分组，限流）

# 使用方法

方法一：

- 拉取源码。
- 修改sentinel-dashboard模块下的application.properties文件中Nacos相关配置。
- 前往源码根目录执行mvn package -DskipTests打包。
- 运行sentinel-dashboard/target文件夹下的jar包。

方法二：

- 拉取源码。
- 修改sentinel-dashboard模块下的application.properties文件中Nacos相关配置。
- 直接在idea中启动项目 sentinel-dashboard

