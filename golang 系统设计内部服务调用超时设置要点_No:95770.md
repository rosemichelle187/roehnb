最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内部服务调用超时设置要点
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/416298.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.1d3jeg.asia/arts/099971.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.1d3jeg.asia/arts/746770.Doc

原标题：编译打包产物依赖分析解读
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.1d3jeg.asia/arts/804376.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/137159.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.1d3jeg.asia/arts/571329.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.1d3jeg.asia/arts/154491.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/182399.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/087878.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.1d3jeg.asia/arts/310454.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.1d3jeg.asia/arts/702400.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.1d3jeg.asia/arts/020708.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.1d3jeg.asia/arts/532365.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.1d3jeg.asia/arts/315287.Doc

原标题：灰度发布策略服务平滑升级
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.1d3jeg.asia/arts/964147.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.1d3jeg.asia/arts/340199.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.1d3jeg.asia/arts/813782.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/451939.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.1d3jeg.asia/arts/563290.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/755771.Doc

原标题：golang 系统设计防重复提交实现
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/873475.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.1d3jeg.asia/arts/910623.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.1d3jeg.asia/arts/212986.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.1d3jeg.asia/arts/599523.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.1d3jeg.asia/arts/212545.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/418025.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.1d3jeg.asia/arts/319163.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/512925.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.1d3jeg.asia/arts/192148.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.1d3jeg.asia/arts/079124.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.1d3jeg.asia/arts/626906.Doc

原标题：Cookie Session 会话状态管理
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/025248.Doc

原标题：golang redis stream 消息队列实践
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.1d3jeg.asia/arts/239559.Doc

原标题：快速入门异步编程基础模型
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/773454.Doc

原标题：全平台系统环境变量配置
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.1d3jeg.asia/arts/137988.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.1d3jeg.asia/arts/644543.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/039212.Doc

原标题：灰度发布策略服务平滑升级
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.1d3jeg.asia/arts/985067.Doc

原标题：nodejs 日志轮转生产环境配置
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/785867.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.1d3jeg.asia/arts/641401.Doc


二、踩坑排错｜Troubleshooting
原标题：安全实践：接口速率限制防止暴力破解
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.1d3jeg.asia/arts/509685.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.1d3jeg.asia/arts/082613.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.1d3jeg.asia/arts/996479.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.1d3jeg.asia/arts/141192.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.1d3jeg.asia/arts/293059.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/969757.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.1d3jeg.asia/arts/653307.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/237992.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/570538.Doc

原标题：Nginx 丢失请求头配置修正
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.1d3jeg.asia/arts/013853.Doc

原标题：golang channel 通道并发处理
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/193953.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/459335.Doc

原标题：golang mysql 避免 select * 查询
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.1d3jeg.asia/arts/571481.Doc

原标题：缓存过期策略优化防业务故障
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/666666.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.1d3jeg.asia/arts/967705.Doc

原标题：前端组件库按需加载性能优化
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.1d3jeg.asia/arts/833192.Doc

原标题：golang 系统设计分布式任务调度
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/866514.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.1d3jeg.asia/arts/567188.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.1d3jeg.asia/arts/649593.Doc

原标题：Git 混乱提交历史清理方法
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.1d3jeg.asia/arts/455474.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.1d3jeg.asia/arts/520026.Doc

原标题：golang docker compose 本地开发最佳实践
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/784997.Doc

原标题：golang docker 容器资源限制设置
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/003803.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.1d3jeg.asia/arts/748363.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/695481.Doc

原标题：分布式锁失效问题排查修复
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.1d3jeg.asia/arts/863707.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.1d3jeg.asia/arts/891473.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.1d3jeg.asia/arts/489327.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.1d3jeg.asia/arts/423020.Doc

原标题：golang 配置文件多环境加载
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.1d3jeg.asia/arts/377685.Doc

原标题：golang net/http 超时全套配置
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.1d3jeg.asia/arts/177807.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/931060.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/160878.Doc

原标题：接口请求重试容错机制实现
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.1d3jeg.asia/arts/802358.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.1d3jeg.asia/arts/462388.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.1d3jeg.asia/arts/827580.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/544518.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.1d3jeg.asia/arts/663074.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.1d3jeg.asia/arts/271891.Doc

原标题：Shell 脚本自动化命令编写
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.1d3jeg.asia/arts/667273.Doc

三、实战开发｜Practice
原标题：业务错误码完整落地实践
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.1d3jeg.asia/arts/994099.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.1d3jeg.asia/arts/914833.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.1d3jeg.asia/arts/371148.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/225274.Doc

原标题：文件分片上传断点续传功能
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/191324.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.1d3jeg.asia/arts/268043.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/249232.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.1d3jeg.asia/arts/748517.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.1d3jeg.asia/arts/816242.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/561728.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.1d3jeg.asia/arts/635275.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.1d3jeg.asia/arts/672330.Doc

原标题：批量数据处理脚本编写技巧
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.1d3jeg.asia/arts/586738.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/561091.Doc

原标题：golang mysql 长连接短连接对比
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.1d3jeg.asia/arts/049097.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.1d3jeg.asia/arts/265905.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.1d3jeg.asia/arts/624723.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.1d3jeg.asia/arts/072237.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.1d3jeg.asia/arts/859398.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.1d3jeg.asia/arts/716627.Doc

原标题：全局异常处理器接口返回统一
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.1d3jeg.asia/arts/123742.Doc

原标题：前端大文件分片上传完整方案
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.1d3jeg.asia/arts/563012.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.1d3jeg.asia/arts/972223.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.1d3jeg.asia/arts/500094.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.1d3jeg.asia/arts/207623.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.1d3jeg.asia/arts/737753.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/576602.Doc

原标题：golang mongodb 事务多文档使用
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.1d3jeg.asia/arts/049468.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.1d3jeg.asia/arts/492208.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/566389.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/756628.Doc

原标题：MySQL 慢查询索引优化实战
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.1d3jeg.asia/arts/234843.Doc

原标题：golang redis 过期策略内存淘汰
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.1d3jeg.asia/arts/949346.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/215983.Doc

原标题：跨域偶现失败配置修复
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/821170.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/067252.Doc

原标题：golang channel 通道并发处理
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.1d3jeg.asia/arts/713385.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/673559.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.1d3jeg.asia/arts/380152.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.1d3jeg.asia/arts/131107.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 api 网关核心能力梳理
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.1d3jeg.asia/arts/598218.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.1d3jeg.asia/arts/790404.Doc

原标题：请求工具封装统一异常处理
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.1d3jeg.asia/arts/923802.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/498216.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.1d3jeg.asia/arts/591457.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.1d3jeg.asia/arts/014842.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.1d3jeg.asia/arts/717033.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.1d3jeg.asia/arts/205517.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/512908.Doc

原标题：golang 单元测试 table‑driven
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.1d3jeg.asia/arts/826767.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.1d3jeg.asia/arts/190420.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.1d3jeg.asia/arts/594776.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.1d3jeg.asia/arts/112267.Doc

原标题：JSON XML 数据解析处理示例
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.1d3jeg.asia/arts/166656.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.1d3jeg.asia/arts/585574.Doc

原标题：日志切割配置防止日志丢失
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/965513.Doc

原标题：golang kafka 核心概念分区副本
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/248163.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/350061.Doc

?
