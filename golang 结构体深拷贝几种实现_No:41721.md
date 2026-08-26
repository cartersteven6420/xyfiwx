最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 结构体深拷贝几种实现
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.nyh7w9.asia/blog/430695.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.nyh7w9.asia/blog/771336.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.nyh7w9.asia/blog/279282.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.nyh7w9.asia/blog/533007.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.nyh7w9.asia/blog/614948.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.nyh7w9.asia/blog/838793.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.nyh7w9.asia/blog/822964.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.nyh7w9.asia/blog/487547.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.nyh7w9.asia/blog/491577.Doc

原标题：全量回归测试提升代码质量
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.nyh7w9.asia/blog/892855.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.nyh7w9.asia/blog/281997.Doc

原标题：golang toml 配置文件解析教程
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.nyh7w9.asia/blog/971077.Doc

原标题：CI 流水线超时时间延长配置
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.nyh7w9.asia/blog/756030.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.nyh7w9.asia/blog/610507.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.nyh7w9.asia/blog/422122.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.nyh7w9.asia/blog/851040.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.nyh7w9.asia/blog/481883.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.nyh7w9.asia/blog/746198.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.nyh7w9.asia/blog/429109.Doc

原标题：JWT 令牌过期异常处理
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.nyh7w9.asia/blog/711355.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.nyh7w9.asia/blog/722549.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.nyh7w9.asia/blog/053622.Doc

原标题：Cookie 跨环境登录配置调整
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.nyh7w9.asia/blog/073608.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.nyh7w9.asia/blog/488385.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.nyh7w9.asia/blog/908818.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.nyh7w9.asia/blog/137799.Doc

原标题：GET POST 接口请求参数处理
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.nyh7w9.asia/blog/864416.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.nyh7w9.asia/blog/083388.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.nyh7w9.asia/blog/190437.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.nyh7w9.asia/blog/494136.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.nyh7w9.asia/blog/014914.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.nyh7w9.asia/blog/088384.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.nyh7w9.asia/blog/862793.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.nyh7w9.asia/blog/104466.Doc

原标题：接口签名校验防篡改实现
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.nyh7w9.asia/blog/095131.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.nyh7w9.asia/blog/807175.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.nyh7w9.asia/blog/237734.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.nyh7w9.asia/blog/728801.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.nyh7w9.asia/blog/048790.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.nyh7w9.asia/blog/681942.Doc


二、踩坑排错｜Troubleshooting
原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.nyh7w9.asia/blog/569215.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.nyh7w9.asia/blog/684498.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.nyh7w9.asia/blog/380810.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.nyh7w9.asia/blog/506654.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.nyh7w9.asia/blog/154774.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.nyh7w9.asia/blog/331703.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.nyh7w9.asia/blog/387427.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.nyh7w9.asia/blog/207805.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.nyh7w9.asia/blog/481506.Doc

原标题：express 请求参数校验处理
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.nyh7w9.asia/blog/634194.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.nyh7w9.asia/blog/481980.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.nyh7w9.asia/blog/246790.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.nyh7w9.asia/blog/214878.Doc

原标题：golang 工具函数库封装思路
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.nyh7w9.asia/blog/860257.Doc

原标题：热更新开发环境配置教程
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.nyh7w9.asia/blog/808324.Doc

原标题：golang docker 部署 redis 配置要点
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.nyh7w9.asia/blog/563559.Doc

原标题：golang k8s 节点污点容忍度配置
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.nyh7w9.asia/blog/533892.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.nyh7w9.asia/blog/577060.Doc

原标题：golang pprof 线上采集性能数据
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.nyh7w9.asia/blog/963118.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.nyh7w9.asia/blog/180362.Doc

原标题：golang mysql 事务回滚异常处理
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.nyh7w9.asia/blog/257378.Doc

原标题：CI 持续集成自动构建流程
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.nyh7w9.asia/blog/344360.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.nyh7w9.asia/blog/074036.Doc

原标题：golang 开发环境快速搭建指南
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.nyh7w9.asia/blog/911822.Doc

原标题：golang redis bitmap 位图统计实现
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.nyh7w9.asia/blog/892258.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.nyh7w9.asia/blog/452229.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.nyh7w9.asia/blog/194417.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.nyh7w9.asia/blog/689325.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.nyh7w9.asia/blog/243917.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.nyh7w9.asia/blog/855225.Doc

原标题：golang 容器健康检查接口开发
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.nyh7w9.asia/blog/804492.Doc

原标题：golang 静态文件服务搭建教程
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.nyh7w9.asia/blog/839264.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.nyh7w9.asia/blog/333693.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.nyh7w9.asia/blog/068585.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://book.nyh7w9.asia/blog/943394.Doc

原标题：golang 链路追踪简易实现方案
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.nyh7w9.asia/blog/822873.Doc

原标题：golang 项目 docker compose 本地调试
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.nyh7w9.asia/blog/347655.Doc

原标题：golang 系统设计大文件上传架构
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.nyh7w9.asia/blog/852184.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.nyh7w9.asia/blog/400692.Doc

原标题：golang docker 容器资源限制设置
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.nyh7w9.asia/blog/450329.Doc

三、实战开发｜Practice
原标题：优化实践：批量操作性能优化，减少数据库IO
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.nyh7w9.asia/blog/209680.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.nyh7w9.asia/blog/255803.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.nyh7w9.asia/blog/825807.Doc

原标题：依赖版本冲突兼容修复方案
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.nyh7w9.asia/blog/742218.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.nyh7w9.asia/blog/533769.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.nyh7w9.asia/blog/299848.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.nyh7w9.asia/blog/637439.Doc

原标题：实践：数据库回滚点业务调试实践
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.nyh7w9.asia/blog/755166.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.nyh7w9.asia/blog/534803.Doc

原标题：golang mock 单元测试编写技巧
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.nyh7w9.asia/blog/132918.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.nyh7w9.asia/blog/203274.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.nyh7w9.asia/blog/751455.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.nyh7w9.asia/blog/041060.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.nyh7w9.asia/blog/260913.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.nyh7w9.asia/blog/674434.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.nyh7w9.asia/blog/465192.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.nyh7w9.asia/blog/193965.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.nyh7w9.asia/blog/374281.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.nyh7w9.asia/blog/563599.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.nyh7w9.asia/blog/441522.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.nyh7w9.asia/blog/679717.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.nyh7w9.asia/blog/655085.Doc

原标题：定时任务重复执行分布式锁
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.nyh7w9.asia/blog/832745.Doc

原标题：零基础理解前后端简单交互流程
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.nyh7w9.asia/blog/304015.Doc

原标题：golang 布隆过滤器实现去重
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.nyh7w9.asia/blog/631162.Doc

原标题：Git commit 钩子提交规范校验
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.nyh7w9.asia/blog/672813.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.nyh7w9.asia/blog/130675.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.nyh7w9.asia/blog/970754.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.nyh7w9.asia/blog/125365.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.nyh7w9.asia/blog/965039.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.nyh7w9.asia/blog/107324.Doc

原标题：API 大版本不兼容平滑迁移
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.nyh7w9.asia/blog/230054.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.nyh7w9.asia/blog/512576.Doc

原标题：业务错误码完整落地实践
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.nyh7w9.asia/blog/603673.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.nyh7w9.asia/blog/724570.Doc

原标题：前端错误监控上报系统搭建
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.nyh7w9.asia/blog/507436.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.nyh7w9.asia/blog/354860.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.nyh7w9.asia/blog/944137.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.nyh7w9.asia/blog/384223.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.nyh7w9.asia/blog/533962.Doc

四、架构设计｜Architecture
原标题：golang 系统设计内网外网服务隔离方案
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.nyh7w9.asia/blog/270393.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.nyh7w9.asia/blog/260251.Doc

原标题：Docker 网络模式容器互通设置
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.nyh7w9.asia/blog/236525.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.nyh7w9.asia/blog/736815.Doc

原标题：文件句柄耗尽资源泄露处理
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.nyh7w9.asia/blog/158451.Doc

原标题：多套环境灵活切换配置方案
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.nyh7w9.asia/blog/041037.Doc

原标题：文件分片上传断点续传功能
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.nyh7w9.asia/blog/040569.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.nyh7w9.asia/blog/818144.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.nyh7w9.asia/blog/118303.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.nyh7w9.asia/blog/909534.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.nyh7w9.asia/blog/679533.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.nyh7w9.asia/blog/253254.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.nyh7w9.asia/blog/566802.Doc

原标题：golang redis pipeline 批量操作
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.nyh7w9.asia/blog/781327.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.nyh7w9.asia/blog/058306.Doc

原标题：模拟登录鉴权权限判断示例
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.nyh7w9.asia/blog/051672.Doc

原标题：echarts 大数据渲染性能调优
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.nyh7w9.asia/blog/126100.Doc

原标题：Git 子模块更新代码不全修复
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.nyh7w9.asia/blog/824693.Doc

?
