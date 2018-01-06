 ### now
``` lua
pig
├── pig-ui -- element-vue-admin实现[9528]
├── pig-admin-service -- 权限管理提供[4000]
├── pig-auth-service -- 授权服务提供[3000]
├── pig-common -- 系统公共模块 
├── pig-config -- 配置中心[4001]
├── pig-eureka -- 服务注册与发现[1025]
├── pig-gateway -- ZUUL网关[9999]
└── pig-visual  -- 图形化模块 
     ├── pig-monitor -- 服务状态监控、turbine [5001]
     ├── pig-zipkin-elk -- zipkin、ELK监控[5002、5601]
     └── pig-cache-cloud -- 缓存管理、统一监控[5005]
```
###  future
```
  ○ 公共运行时服务
      ■ 服务发现Eureka
      ■ API网关Zuul --> Spring Gateway
      ■ 配置中心Spring Cloud Config
  ○ 服务框架和通信模式
      ■ REST框架 Fegin
      ■ 聚合层和后台服务层
  ○ 监控告警和可靠性工程
      ■ 综述三层监控体系
      ■ 数据采集总线(Turbine + RabbitMQ)
      ■ 统一日志(ELK)
      ■ 调用链监控(Spring Cloud Sleuth)
      ■ 统一告警(ZMON)
      ■ 限流熔断和Hystrix
      ■ 服务限流 Zuul-Ratelimit
  ○ 后台服务
      ■ 消息服务MQ(RabbitMQ)
      ■ 任务调度Job(Elastic-job)
      ■ 缓存服务(CacheCloud)
      ■ 分布式数据访问层(ShardingJDBC)
      ■ 统一认证服务 (Spring Cloud Oauth 2.0)
      ■ 代码自动生成 (Velocity Template)
  ○ 持续交付
      ■ 持续集成，多环境和发布流水线
      ■ 蓝绿、金丝雀和灰度发布
```  
欢迎加入QQ交流群，互相学习  
![image](http://oss.wjg95.cn/pig_qq_qun.png)

### 详细说明 wiki
##### https://gitee.com/log4j/pig/wikis/ 