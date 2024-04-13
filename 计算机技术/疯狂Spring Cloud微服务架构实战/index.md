《疯狂Spring Cloud微服务架构实战》这本书的大纲如下：

1. Spring Cloud 概述
   - 传统的应用
     - 单体应用
     - 架构演进
   - 微服务与 Spring Cloud
     - 什么是微服务
     - 关于 Netflix OSS
     - Spring Cloud 与 Netflix
   - Spring Cloud 的主要模块
   - 关于本书
     - 下载本书的软件及源码
     - 导入本书的案例
   
2. 开发环境搭建
   - 安装与配置 Maven
     - 关于 Maven
     - 下载与安装 Maven
     - 配置远程仓库
   - 安装 Eclipse
     - Eclipse 版本
     - 在 Eclipse 配置 Maven
   
3. Spring Boot 简介与配置
   - Spring Boot 简介
     - Spring Boot 简介
     - 新建 Maven 项目
     - 编写启动类
     - 编写控制器
     - 发布 REST WebService
   - Spring Boot 配置文件
     - 默认配置文件
     - 指定配置文件位置
     - yml 文件
     - 运行时指定 profiles 配置
     - 热部署
   
4. 微服务发布与调用

   - **Eureka 介绍**
     - **关于 Eureka**：Eureka 是 Netflix 开源的一款服务发现工具，用于管理微服务架构中的服务注册与发现。作为微服务架构中的服务注册中心，Eureka 允许服务实例动态地注册和注销，客户端服务可以通过 Eureka 来发现其他可用的服务。
     - **Eureka 架构**：介绍了 Eureka 的工作机制和架构设计，包括 Eureka 服务器和 Eureka 客户端的角色和职责。Eureka 服务器负责维护服务注册表，而客户端则负责注册自己提供的服务并从注册表中发现其他服务。
     - **服务器端**：详细描述了 Eureka 服务器的搭建和配置过程，以及如何启动和维护 Eureka 服务。
     - **服务提供者**：讲解了作为服务提供者的客户端如何将自己提供的服务注册到 Eureka 服务器，并保持心跳以确保服务的可用性。
     - **服务调用者**：说明了服务调用者如何通过 Eureka 服务器发现和调用其他服务，并处理服务调用过程中可能出现的问题。
   - **第一个 Eureka 应用**
     - **构建服务器**：指导读者如何创建第一个 Eureka 服务器实例，并进行配置以运行服务。
     - **服务器注册开关**：介绍了如何在服务提供者中控制是否将自己注册到 Eureka 服务器。
     - **编写服务提供者**：通过示例代码，展示了如何创建一个简单的服务提供者，并将其注册到 Eureka 服务器。
     - **编写服务调用者**：同样通过示例代码，讲解了如何创建服务调用者，并通过 Eureka 服务器调用其他服务提供的 API。
     - **程序结构**：阐述了整个微服务架构的程序结构和组件关系，帮助读者更好地理解微服务之间的交互和依赖。

   

   - 第一个 Eureka 应用
     - 构建服务器
     - 服务器注册开关
     - 编写服务提供者
     - 编写服务调用者
     - 程序结构

5. Eureka 集群搭建
   - Eureka 集群搭建
     - 本例集群结构图
     - 改造服务器端
     - 改造服务提供者
     - 改造服务调用者
     - 编写 REST 客户端进行测试
   
6. 负载均衡框架 Ribbon 介绍
   - Ribbon 介绍
     - Ribbon 简介
     - Ribbon 子模块
     - 负载均衡器组件
   - 第一个 Ribbon 程序
     - 编写服务
     - 编写请求客户端
     - Ribbon 配置
   
7. Ribbon 负载均衡器
   - Ribbon 负载均衡器
   - 自定义负载规则
   - Ribbon 自带的负载规则
   - Ping 机制
   - 自定义 Ping
   - 其他配置
   
8. Spring Cloud 与 RibbonRibbon
   - 准备工作
   - 使用代码配置 Ribbon
   - 使用配置文件设置 Ribbon
   - Spring 使用 Ribbon 的 API
   
9. RestTemplate 负载均衡原理
   - @LoadBalanced 注解概述
   - 编写自定义注解以及拦截器
   - 使用自定义拦截器以及注解
   - 控制器中使用 RestTemplate
   
10. REST 客户端 Feign 介绍
    - 使用 CXF 调用 REST 服务
    - 使用 Restlet 调用 REST 服务
    - Feign 框架介绍
    - 第一个 Feign 程序
    - 请求参数与返回对象
    
11. Feign 的编码器与解码器
    - 编码器
    - 解码器
    - XML 的编码与解码
    - 自定义编码器与解码器
    
12. 自定义 Feign 客户端

13. Feign 第三方注解与注解翻译器
    - 使用第三方注解
    - Feign 解析第三方注解
    
14. Spring Cloud 整合 Feign
    - Spring Cloud 整合 Feign
    - Feign 负载均衡
    - 默认配置
    
15. 第一个 Hystrix 程序
    - 准备工作
    - 客户端使用 Hystrix
    - 调用错误服务
    - Hystrix 运作流程
    - Hystrix 属性配置与回退

书中详细介绍了Spring Cloud微服务架构的各个方面，包括开发环境的搭建、Spring Boot的配置、服务的发布与调用、负载均衡、Feign客户端的使用、Hystrix断路器等。每一部分都通过实际的代码示例和详细的解释，帮助读者理解和掌握Spring Cloud微服务架构的实战应用。

复制再试一次分享