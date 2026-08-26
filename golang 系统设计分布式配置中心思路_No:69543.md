最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式配置中心思路
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.39ui03.asia/arts/674822.Doc

原标题：golang mysql innodb 事务隔离级别
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.39ui03.asia/arts/470626.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.39ui03.asia/arts/118071.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.39ui03.asia/arts/430495.Doc

原标题：依赖安装失败全方位排错
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.39ui03.asia/arts/228368.Doc

原标题：图片上传预览格式大小处理
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.39ui03.asia/arts/904666.Doc

原标题：前端骨架屏提升页面体验
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.39ui03.asia/arts/304302.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.39ui03.asia/arts/274860.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.39ui03.asia/arts/041618.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.39ui03.asia/arts/906113.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.39ui03.asia/arts/964328.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.39ui03.asia/arts/744041.Doc

原标题：golang mongodb 索引优化查询速度
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.39ui03.asia/arts/577660.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.39ui03.asia/arts/975237.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.39ui03.asia/arts/223183.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.39ui03.asia/arts/300004.Doc

原标题：golang rate‑limiter 限流组件
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.39ui03.asia/arts/410175.Doc

原标题：golang docker 镜像体积优化技巧
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.39ui03.asia/arts/151061.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.39ui03.asia/arts/537020.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.39ui03.asia/arts/200272.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.39ui03.asia/arts/484098.Doc

原标题：golang docker 镜像体积优化技巧
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.39ui03.asia/arts/859194.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.39ui03.asia/arts/863089.Doc

原标题：express 请求参数校验处理
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.39ui03.asia/arts/858058.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.39ui03.asia/arts/378191.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.39ui03.asia/arts/314839.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.39ui03.asia/arts/166950.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.39ui03.asia/arts/452405.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.39ui03.asia/arts/716846.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.39ui03.asia/arts/963583.Doc

原标题：vue3 组合式 API 业务开发实战
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.39ui03.asia/arts/417275.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.39ui03.asia/arts/103175.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.39ui03.asia/arts/351403.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.39ui03.asia/arts/612168.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.39ui03.asia/arts/056358.Doc

原标题：开源项目本地运行排错完整清单
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.39ui03.asia/arts/833557.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.39ui03.asia/arts/901800.Doc

原标题：nodejs 中间件模式原理剖析
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.39ui03.asia/arts/360702.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.39ui03.asia/arts/422418.Doc

原标题：环境变量不生效问题修复
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.39ui03.asia/arts/774579.Doc


二、踩坑排错｜Troubleshooting
原标题：限流规则误拦截正常请求修复
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.39ui03.asia/arts/307477.Doc

原标题：前端静态缓存更新生效处理
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.39ui03.asia/arts/641946.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.39ui03.asia/arts/123293.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.39ui03.asia/arts/824721.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.39ui03.asia/arts/296546.Doc

原标题：golang es 聚合统计查询实现
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.39ui03.asia/arts/371622.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.39ui03.asia/arts/354393.Doc

原标题：golang k8s 资源请求限制配置
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.39ui03.asia/arts/039495.Doc

原标题：简易网关请求路由过滤模拟
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.39ui03.asia/arts/293029.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.39ui03.asia/arts/696509.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.39ui03.asia/arts/637644.Doc

原标题：golang 分布式锁防死锁处理
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.39ui03.asia/arts/742680.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.39ui03.asia/arts/050542.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.39ui03.asia/arts/828453.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.39ui03.asia/arts/090459.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.39ui03.asia/arts/604474.Doc

原标题：定时任务重复执行分布式锁
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.39ui03.asia/arts/746652.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.39ui03.asia/arts/365721.Doc

原标题：正则表达式优化 CPU 占满问题
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.39ui03.asia/arts/824168.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.39ui03.asia/arts/896508.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.39ui03.asia/arts/696772.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.39ui03.asia/arts/926881.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.39ui03.asia/arts/626952.Doc

原标题：限流组件计数器令牌桶模式实现
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.39ui03.asia/arts/636899.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.39ui03.asia/arts/292815.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.39ui03.asia/arts/362811.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.39ui03.asia/arts/593810.Doc

原标题：CI 构建缓存加速编译速度
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.39ui03.asia/arts/181383.Doc

原标题：nodejs http 服务性能调优实战
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.39ui03.asia/arts/414327.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.39ui03.asia/arts/768559.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.39ui03.asia/arts/014914.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.39ui03.asia/arts/481951.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.39ui03.asia/arts/374587.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.39ui03.asia/arts/074516.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.39ui03.asia/arts/993944.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.39ui03.asia/arts/824144.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.39ui03.asia/arts/858287.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.39ui03.asia/arts/861958.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.39ui03.asia/arts/959262.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.39ui03.asia/arts/936039.Doc

三、实战开发｜Practice
原标题：golang 系统设计 vscode go 插件调试配置实操
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.39ui03.asia/arts/999710.Doc

原标题：后端大文件分片上传接口开发
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.39ui03.asia/arts/075141.Doc

原标题：golang 配置热更新不重启服务
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.39ui03.asia/arts/313274.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.39ui03.asia/arts/081933.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.39ui03.asia/arts/637360.Doc

原标题：RPC 接口字段增减兼容处理
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.39ui03.asia/arts/277626.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.39ui03.asia/arts/334320.Doc

原标题：Practice：实现接口防重提交组件实践
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.39ui03.asia/arts/426620.Doc

原标题：语义化版本依赖管理防错乱
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.39ui03.asia/arts/380292.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.39ui03.asia/arts/473494.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.39ui03.asia/arts/488582.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.39ui03.asia/arts/236399.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.39ui03.asia/arts/415334.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.39ui03.asia/arts/415297.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.39ui03.asia/arts/375179.Doc

原标题：限流规则误拦截正常请求修复
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.39ui03.asia/arts/045433.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.39ui03.asia/arts/523579.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.39ui03.asia/arts/264191.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.39ui03.asia/arts/643648.Doc

原标题：golang gitlab runner 部署与注册实操
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.39ui03.asia/arts/939222.Doc

原标题：golang docker 部署 es 本地开发
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.39ui03.asia/arts/117318.Doc

原标题：golang 系统设计海量数据分页查询
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.39ui03.asia/arts/317314.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.39ui03.asia/arts/903617.Doc

原标题：css 变量主题切换方案实现
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.39ui03.asia/arts/791807.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.39ui03.asia/arts/244544.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.39ui03.asia/arts/293316.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.39ui03.asia/arts/122867.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.39ui03.asia/arts/855863.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.39ui03.asia/arts/196051.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.39ui03.asia/arts/072166.Doc

原标题：golang docker 容器资源限制设置
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.39ui03.asia/arts/715570.Doc

原标题：git stash 代码暂存切换分支
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.39ui03.asia/arts/048120.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.39ui03.asia/arts/400614.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.39ui03.asia/arts/211498.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.39ui03.asia/arts/159784.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.39ui03.asia/arts/536381.Doc

原标题：golang docker compose 部署 minio
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.39ui03.asia/arts/935869.Doc

原标题：golang mysql innodb 事务隔离级别
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.39ui03.asia/arts/855395.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.39ui03.asia/arts/279710.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.39ui03.asia/arts/860529.Doc

四、架构设计｜Architecture
原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.39ui03.asia/arts/935009.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.39ui03.asia/arts/220628.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.39ui03.asia/arts/309481.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.39ui03.asia/arts/023804.Doc

原标题：golang kafka 核心概念分区副本
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.39ui03.asia/arts/516885.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.39ui03.asia/arts/891419.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.39ui03.asia/arts/977692.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.39ui03.asia/arts/993900.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.39ui03.asia/arts/450230.Doc

原标题：开源项目本地运行排错完整清单
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.39ui03.asia/arts/876841.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.39ui03.asia/arts/018833.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.39ui03.asia/arts/541540.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.39ui03.asia/arts/798735.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.39ui03.asia/arts/712189.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.39ui03.asia/arts/863527.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.39ui03.asia/arts/614589.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.39ui03.asia/arts/131665.Doc

原标题：入门实践：实现简单文件读写功能
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.39ui03.asia/arts/953892.Doc

?
