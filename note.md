feign 服务消费者, 自带断路器, eureka client
ribbon 不带断路器, 可以添加hystrix

hystrix dashboard 单个节点的hystrix metrics
turbine 监控集群中所有hystrix metrics

eureka: 服务注册, 服务发现
zuul: 智能路由
service: 服务提供者, eureka client注册

config-server: 分布式配置中心, 与git repo进行交互
config-client: 暴露api接口给其他组件使用, 跟config-server进行交互


