# 说明

> spring cloud 2.x示例

## 版本

各版本如下：

* spring cloud 2.1.0.RELEASE
* spring boot 2.1.2.RELEASE
* spring boot admin 2.1.3.RELEASE

## 模块

系统分为四个最基础的模块：

* admin（spring boot admin服务端）
* gateway（网关，基于spring cloud gateway）
* register（注册中心，基于spring cloud netflix eureka）
* server（用户自定义服务）

其中server模块（用户自定义服务模块）根据实际情况演变出用户服务等其他功能模块。

## 启动

最先启动register模块，剩下的随意。

```
spring-cloud-v2 > mvn clean package
```