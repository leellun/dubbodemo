# dubbodemo
dubbo 入门demo
模块划分
dubbo-interface 接口抽取模块
user-center 服务提供模块
order-service 订阅调用服务模块

注意一点
```
<dubbo:registry address="zookeeper://192.168.10.103:2181" timeout="10000"></dubbo:registry>
```xml
timeout需要设置，具体大小自己指定，不指定，很容易报错
