# service_mesh
知识倍速爆炸  平台技术升级  

AI engine | data stream | **core service engine** - openapi | app 
--- | --- | --- | ---
tensorflow / spark hbase | docker k8s (mysql/mariadb galera - redis sentinel - kafka zookeeper)  | **(springcloud - istio) springboot jvm/go(go-libs)** | vue(or react)/electron

预测股价 教育 企业application



## core service:
#### springboot(enterpise logics)
#### cap: jvm 多线程 协程 并发 nio cache 持久化 选主 连接池 多路复用  linux_kernel
#### service cloud:  e.g. cloud provision systems
* config / register / discovery / route / 智能lb <- service 1, 2...
* retry, timeout, 隔板，熔断, **queue** <- service 1 call 2...
* 链路追踪 <- service 1 call 2 call 3...


<br/>


深度分析：Istio替代Spring Cloud的合理性 https://cloud.tencent.com/developer/article/1070496
https://github.com/saturnism/istio-by-example-java/tree/master/spring-boot-example

Markdown: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
