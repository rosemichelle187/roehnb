最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://web.qianshuwangluo.com/question/1288105.html

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://web.qianshuwangluo.com/question/3140227.html

原标题：golang 系统设计接口幂等架构设计
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://web.qianshuwangluo.com/question/2040240.html

原标题：golang 系统设计性能优化通用思路方法论
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://web.qianshuwangluo.com/question/3860970.html

原标题：快速上手简易网关转发逻辑模拟
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://web.qianshuwangluo.com/question/9348040.html

原标题：前端工程化 webpack 打包优化
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://web.qianshuwangluo.com/question/3598047.html

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://web.qianshuwangluo.com/question/6158899.html

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://web.qianshuwangluo.com/question/5333597.html

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://web.qianshuwangluo.com/question/4230639.html

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://web.qianshuwangluo.com/question/5494109.html

原标题：一次数据库死锁现场分析与解决方案记录
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://web.qianshuwangluo.com/question/0577639.html

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://web.qianshuwangluo.com/question/6776621.html

原标题：缓存过期打散防止缓存雪崩
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://web.qianshuwangluo.com/question/3060830.html

原标题：golang docker compose 部署 minio
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://web.qianshuwangluo.com/question/8707575.html

原标题：golang 简易埋点日志上报实现
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://web.qianshuwangluo.com/question/7897329.html

原标题：golang docker 部署 prometheus 整套
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://web.qianshuwangluo.com/question/6758062.html

原标题：golang 系统设计数据库索引设计方法论
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://web.qianshuwangluo.com/question/4278312.html

原标题：golang 系统设计接口向前兼容改造实操
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://web.qianshuwangluo.com/question/0125709.html

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://web.qianshuwangluo.com/question/3215752.html

原标题：Spring 事务传播机制配置生效
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://web.qianshuwangluo.com/question/6402935.html

原标题：golang 结构体 json 序列化坑点
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://web.qianshuwangluo.com/question/8640540.html

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://web.qianshuwangluo.com/question/0517989.html

原标题：Practice：实现请求重试组件支持退避策略
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://web.qianshuwangluo.com/question/4425461.html

原标题：golang http 代理客户端配置
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://web.qianshuwangluo.com/question/1148918.html

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://web.qianshuwangluo.com/question/1978180.html

原标题：golang 接口返回统一封装工具
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://web.qianshuwangluo.com/question/8941600.html

原标题：网络读取超时设置连接挂起防护
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://web.qianshuwangluo.com/question/3929130.html

原标题：golang makefile 自动化构建脚本
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://web.qianshuwangluo.com/question/2048532.html

原标题：golang docker 网络模式桥接 host
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://web.qianshuwangluo.com/question/2090077.html

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://web.qianshuwangluo.com/question/1416521.html

原标题：golang validator 自定义校验规则
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://web.qianshuwangluo.com/question/5073161.html

原标题：golang 数据库批量更新性能优化
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://web.qianshuwangluo.com/question/7211376.html

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://web.qianshuwangluo.com/question/4278396.html

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://web.qianshuwangluo.com/question/3020611.html

原标题：golang 系统设计容器健康检查设计思路
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://web.qianshuwangluo.com/question/4027098.html

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://web.qianshuwangluo.com/question/0885468.html

原标题：Performance：数据库大表优化，冷热数据分离
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://web.qianshuwangluo.com/question/1785240.html

原标题：golang k8s ingress 路由域名转发
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://web.qianshuwangluo.com/question/5042394.html

原标题：开源项目本地运行排错完整清单
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://web.qianshuwangluo.com/question/2932030.html

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://web.qianshuwangluo.com/question/5875469.html


二、踩坑排错｜Troubleshooting
原标题：golang 接口请求日志记录中间件
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://web.qianshuwangluo.com/question/9181602.html

原标题：golang docker compose 环境变量
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://web.qianshuwangluo.com/question/1209160.html

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://web.qianshuwangluo.com/question/7210051.html

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://web.qianshuwangluo.com/question/5617485.html

原标题：golang 系统设计令牌桶漏桶算法对比
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://web.qianshuwangluo.com/question/8783696.html

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://web.qianshuwangluo.com/question/8466281.html

原标题：实践：Git工作流主干开发团队协作实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://web.qianshuwangluo.com/question/8259025.html

原标题：Practice：实现请求body重复读取中间件实践
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://web.qianshuwangluo.com/question/9335572.html

原标题：golang 错误包装 errors.wrap 用法
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://web.qianshuwangluo.com/question/7490562.html

原标题：nodejs 日志轮转生产环境配置
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://web.qianshuwangluo.com/question/2915744.html

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://web.qianshuwangluo.com/question/4155760.html

原标题：手写简易 ORM 理解对象映射
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://web.qianshuwangluo.com/question/2132074.html

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://web.qianshuwangluo.com/question/0614876.html

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://web.qianshuwangluo.com/question/5339084.html

原标题：开源实践：开源项目本地调试构建排坑经验
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://web.qianshuwangluo.com/question/1575364.html

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://web.qianshuwangluo.com/question/9449526.html

原标题：golang redis 过期 key 监听业务
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://web.qianshuwangluo.com/question/9688420.html

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://web.qianshuwangluo.com/question/6904902.html

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://web.qianshuwangluo.com/question/3822130.html

原标题：golang 系统设计 mq 消息积压解决方案
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://web.qianshuwangluo.com/question/3805856.html

原标题：golang 系统设计 grpc proto 接口设计原则
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://web.qianshuwangluo.com/question/7501080.html

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://web.qianshuwangluo.com/question/7749006.html

原标题：golang mysql 时间类型选型避坑
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://web.qianshuwangluo.com/question/1180699.html

原标题：Practice：实现批量任务失败断点续跑实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://web.qianshuwangluo.com/question/5381843.html

原标题：热更新开发环境配置教程
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://web.qianshuwangluo.com/question/0487190.html

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://web.qianshuwangluo.com/question/4036660.html

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://web.qianshuwangluo.com/question/2805339.html

原标题：golang 系统设计分表 id 生成策略对比
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://web.qianshuwangluo.com/question/2608887.html

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://web.qianshuwangluo.com/question/7942372.html

原标题：Nginx 请求头大小上限调整
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://web.qianshuwangluo.com/question/3511047.html

原标题：Security：文件路径穿越漏洞完整防护
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://web.qianshuwangluo.com/question/0427863.html

原标题：GraphQL 接口查询优化实操
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://web.qianshuwangluo.com/question/3950568.html

原标题：golang 系统设计结构化日志字段规范约定
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://web.qianshuwangluo.com/question/0423710.html

原标题：多环境配置中心灵活切换方案
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://web.qianshuwangluo.com/question/3494458.html

原标题：WebSocket 双向通信 demo 开发
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://web.qianshuwangluo.com/question/3050974.html

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://web.qianshuwangluo.com/question/3855039.html

原标题：调优方案：Docker容器内核参数性能调优
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://web.qianshuwangluo.com/question/7759436.html

原标题：echarts 大数据渲染性能调优
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://web.qianshuwangluo.com/question/2441328.html

原标题：golang 系统设计数据库索引设计方法论
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://web.qianshuwangluo.com/question/3164987.html

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://web.qianshuwangluo.com/question/6759597.html

三、实战开发｜Practice
原标题：golang redis 缓存穿透解决方案
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://web.qianshuwangluo.com/question/7145422.html

原标题：简易日志收集集中管理方案
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://web.qianshuwangluo.com/question/5050902.html

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://web.qianshuwangluo.com/question/6526532.html

原标题：golang k8s 滚动更新回滚策略
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://web.qianshuwangluo.com/question/8810668.html

原标题：golang 系统设计日志脱敏防止信息泄露
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://web.qianshuwangluo.com/question/6094276.html

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://web.qianshuwangluo.com/question/5069132.html

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://web.qianshuwangluo.com/question/2398784.html

原标题：限流规则误拦截正常请求修复
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://web.qianshuwangluo.com/question/0131243.html

原标题：灰度发布策略服务平滑升级
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://web.qianshuwangluo.com/question/6589646.html

原标题：Git 标签版本标记发布管理
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://web.qianshuwangluo.com/question/4203786.html

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://web.qianshuwangluo.com/question/1321937.html

原标题：golang pprof 线上采集性能数据
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://web.qianshuwangluo.com/question/7547952.html

原标题：网关集成鉴权限流日志一体化
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://web.qianshuwangluo.com/question/2343205.html

原标题：golang 静态编译缩小镜像体积
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://web.qianshuwangluo.com/question/5091931.html

原标题：接口压测定位系统性能瓶颈
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://web.qianshuwangluo.com/question/0897606.html

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://web.qianshuwangluo.com/question/3254756.html

原标题：echarts 大数据渲染性能调优
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://web.qianshuwangluo.com/question/3160946.html

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://web.qianshuwangluo.com/question/1841932.html

原标题：快速上手阅读开源项目源码的入门思路
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://web.qianshuwangluo.com/question/1861578.html

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://web.qianshuwangluo.com/question/2054615.html

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://web.qianshuwangluo.com/question/5575754.html

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://web.qianshuwangluo.com/question/1486532.html

原标题：nodejs jwt 登录鉴权完整示例
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://web.qianshuwangluo.com/question/8286240.html

原标题：数据库连接池参数调优
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://web.qianshuwangluo.com/question/4519306.html

原标题：架构笔记：业务操作审计日志系统架构设计
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://web.qianshuwangluo.com/question/8061725.html

原标题：Hands‑on：简易邮件发送服务封装实践
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://web.qianshuwangluo.com/question/9793062.html

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://web.qianshuwangluo.com/question/0319459.html

原标题：css 变量主题切换方案实现
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://web.qianshuwangluo.com/question/9234347.html

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://web.qianshuwangluo.com/question/0572544.html

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://web.qianshuwangluo.com/question/4350516.html

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://web.qianshuwangluo.com/question/7573533.html

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://web.qianshuwangluo.com/question/8953147.html

原标题：设计思考：分布式会话架构选型对比
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://web.qianshuwangluo.com/question/7356204.html

原标题：golang redis 发布订阅简单示例
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://web.qianshuwangluo.com/question/3740901.html

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://web.qianshuwangluo.com/question/5215798.html

原标题：golang 系统设计定时任务执行超时中断防护
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://web.qianshuwangluo.com/question/1821724.html

原标题：vite 插件开发自定义构建逻辑
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://web.qianshuwangluo.com/question/1770831.html

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://web.qianshuwangluo.com/question/3958455.html

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://web.qianshuwangluo.com/question/6914271.html

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://web.qianshuwangluo.com/question/6124111.html

四、架构设计｜Architecture
原标题：golang 系统设计大事务拆分实战思路
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://web.qianshuwangluo.com/question/5237753.html

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://web.qianshuwangluo.com/question/5907429.html

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://web.qianshuwangluo.com/question/0971499.html

原标题：零基础理解JSON、XML数据格式处理
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://web.qianshuwangluo.com/question/5056208.html

原标题：git stash 代码暂存切换分支
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://web.qianshuwangluo.com/question/0611669.html

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://web.qianshuwangluo.com/question/6017341.html

原标题：pnpm 包管理工具实战避坑指南
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://web.qianshuwangluo.com/question/8016353.html

原标题：nodejs 接口限流防刷代码实现
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://web.qianshuwangluo.com/question/4224686.html

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://web.qianshuwangluo.com/question/2674755.html

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://web.qianshuwangluo.com/question/5359710.html

原标题：nodejs 中间件模式原理剖析
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://web.qianshuwangluo.com/question/6828682.html

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://web.qianshuwangluo.com/question/9154775.html

原标题：golang 系统设计分库分表 id 全局生成策略
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://web.qianshuwangluo.com/question/4213783.html

原标题：内存溢出问题现象识别排查
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://web.qianshuwangluo.com/question/3182571.html

原标题：golang 系统设计缓存与数据库一致性权衡
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://web.qianshuwangluo.com/question/3737531.html

原标题：golang 系统设计错误码体系完整设计
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://web.qianshuwangluo.com/question/1614681.html

原标题：前端骨架屏提升页面体验
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://web.qianshuwangluo.com/question/2319839.html

原标题：用户敏感数据脱敏代码实现
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://web.qianshuwangluo.com/question/5151965.html

?
