最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计代码评审 checklist 清单
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.9jgenw.asia/blog/415770.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.9jgenw.asia/blog/444666.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.9jgenw.asia/blog/214739.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.9jgenw.asia/blog/049094.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.9jgenw.asia/blog/185654.Doc

原标题：golang 消息队列 kafka 消费开发
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.9jgenw.asia/blog/597140.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.9jgenw.asia/blog/901730.Doc

原标题：golang redis 锁超时业务处理
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.9jgenw.asia/blog/745093.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.9jgenw.asia/blog/515773.Doc

原标题：golang 系统设计分布式事务几种方案
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.9jgenw.asia/blog/589781.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.9jgenw.asia/blog/711317.Doc

原标题：SourceMap 生成线上报错定位
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.9jgenw.asia/blog/559658.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.9jgenw.asia/blog/611031.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.9jgenw.asia/blog/567005.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.9jgenw.asia/blog/428363.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.9jgenw.asia/blog/161496.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.9jgenw.asia/blog/892400.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.9jgenw.asia/blog/946439.Doc

原标题：前端防抖节流高频事件处理
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.9jgenw.asia/blog/186839.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.9jgenw.asia/blog/990398.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.9jgenw.asia/blog/960280.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.9jgenw.asia/blog/496341.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.9jgenw.asia/blog/014130.Doc

原标题：golang 大文件读取内存优化
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.9jgenw.asia/blog/472973.Doc

原标题：golang makefile 自动化构建脚本
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.9jgenw.asia/blog/678198.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.9jgenw.asia/blog/614832.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.9jgenw.asia/blog/489688.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.9jgenw.asia/blog/860617.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.9jgenw.asia/blog/847011.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.9jgenw.asia/blog/096158.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.9jgenw.asia/blog/925163.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.9jgenw.asia/blog/533258.Doc

原标题：golang websocket 消息广播实现
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.9jgenw.asia/blog/597051.Doc

原标题：数据库死锁成因规避方案
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.9jgenw.asia/blog/719201.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.9jgenw.asia/blog/655729.Doc

原标题：golang redis 主从复制哨兵原理
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.9jgenw.asia/blog/726972.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.9jgenw.asia/blog/826804.Doc

原标题：内存泄漏定位分析完整流程
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.9jgenw.asia/blog/862806.Doc

原标题：文件编码统一随机乱码修复
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.9jgenw.asia/blog/164240.Doc

原标题：golang redis 主从复制哨兵原理
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.9jgenw.asia/blog/047695.Doc


二、踩坑排错｜Troubleshooting
原标题：实践：前后端时间格式统一规范落地实践
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.9jgenw.asia/blog/712908.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.9jgenw.asia/blog/904034.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.9jgenw.asia/blog/507461.Doc

原标题：golang mongodb 索引优化查询速度
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.9jgenw.asia/blog/784490.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.9jgenw.asia/blog/507350.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.9jgenw.asia/blog/296909.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.9jgenw.asia/blog/578963.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.9jgenw.asia/blog/756873.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.9jgenw.asia/blog/150872.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.9jgenw.asia/blog/377484.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.9jgenw.asia/blog/827319.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.9jgenw.asia/blog/414459.Doc

原标题：golang mysql limit 大分页优化
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.9jgenw.asia/blog/451744.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.9jgenw.asia/blog/415503.Doc

原标题：golang mongodb 分页性能优化技巧
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.9jgenw.asia/blog/725151.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.9jgenw.asia/blog/271870.Doc

原标题：golang 分布式上下文传递方案
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.9jgenw.asia/blog/531751.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.9jgenw.asia/blog/445509.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.9jgenw.asia/blog/086791.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.9jgenw.asia/blog/596803.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.9jgenw.asia/blog/781873.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.9jgenw.asia/blog/597790.Doc

原标题：vue pinia 状态管理实战教程
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.9jgenw.asia/blog/676727.Doc

原标题：golang 系统设计大文件上传架构
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.9jgenw.asia/blog/620604.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.9jgenw.asia/blog/192513.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.9jgenw.asia/blog/780542.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.9jgenw.asia/blog/831983.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.9jgenw.asia/blog/918073.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.9jgenw.asia/blog/528680.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.9jgenw.asia/blog/526444.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.9jgenw.asia/blog/196552.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.9jgenw.asia/blog/406212.Doc

原标题：golang 系统设计会话共享多实例部署
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.9jgenw.asia/blog/481788.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.9jgenw.asia/blog/699579.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.9jgenw.asia/blog/484284.Doc

原标题：golang 参数校验业务接口处理
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.9jgenw.asia/blog/771459.Doc

原标题：Docker 容器时区错误修复方案
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.9jgenw.asia/blog/164329.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.9jgenw.asia/blog/125895.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.9jgenw.asia/blog/906248.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.9jgenw.asia/blog/072972.Doc

三、实战开发｜Practice
原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.9jgenw.asia/blog/899943.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.9jgenw.asia/blog/831850.Doc

原标题：RPC 接口字段增减兼容处理
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.9jgenw.asia/blog/496942.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.9jgenw.asia/blog/960316.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.9jgenw.asia/blog/022145.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.9jgenw.asia/blog/821391.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.9jgenw.asia/blog/189680.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.9jgenw.asia/blog/742274.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.9jgenw.asia/blog/204130.Doc

原标题：golang makefile 自动化构建脚本
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.9jgenw.asia/blog/471710.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.9jgenw.asia/blog/926497.Doc

原标题：前端静态缓存更新生效处理
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.9jgenw.asia/blog/091249.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.9jgenw.asia/blog/320548.Doc

原标题：golang http 代理客户端配置
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.9jgenw.asia/blog/385220.Doc

原标题：golang rate‑limiter 限流组件
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.9jgenw.asia/blog/481431.Doc

原标题：批量数据处理脚本编写技巧
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.9jgenw.asia/blog/618205.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.9jgenw.asia/blog/120049.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.9jgenw.asia/blog/421138.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.9jgenw.asia/blog/715510.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.9jgenw.asia/blog/290748.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.9jgenw.asia/blog/059304.Doc

原标题：项目脚手架模板生成工具
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.9jgenw.asia/blog/421180.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.9jgenw.asia/blog/146333.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.9jgenw.asia/blog/859164.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.9jgenw.asia/blog/258691.Doc

原标题：多线程线程安全脏数据规避
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.9jgenw.asia/blog/603014.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.9jgenw.asia/blog/741826.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.9jgenw.asia/blog/781849.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.9jgenw.asia/blog/041808.Doc

原标题：无用对象回收抑制内存上涨
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://book.9jgenw.asia/blog/744941.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.9jgenw.asia/blog/785791.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.9jgenw.asia/blog/991190.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.9jgenw.asia/blog/445776.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.9jgenw.asia/blog/530246.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.9jgenw.asia/blog/152372.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.9jgenw.asia/blog/085888.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.9jgenw.asia/blog/649151.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.9jgenw.asia/blog/411180.Doc

原标题：文件分片上传断点续传功能
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.9jgenw.asia/blog/043328.Doc

原标题：golang makefile 自动化构建脚本
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.9jgenw.asia/blog/536615.Doc

四、架构设计｜Architecture
原标题：设计思考：系统幂等性整体架构层面保障
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.9jgenw.asia/blog/485161.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.9jgenw.asia/blog/992436.Doc

原标题：golang goroutine 池任务调度
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.9jgenw.asia/blog/673214.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.9jgenw.asia/blog/858292.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.9jgenw.asia/blog/202744.Doc

原标题：golang redis 连接池参数最佳值
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.9jgenw.asia/blog/863914.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.9jgenw.asia/blog/378180.Doc

原标题：时间同步修复令牌提前过期
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.9jgenw.asia/blog/462134.Doc

原标题：golang validator 自定义校验规则
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.9jgenw.asia/blog/407001.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.9jgenw.asia/blog/855801.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.9jgenw.asia/blog/059442.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.9jgenw.asia/blog/064071.Doc

原标题：golang prometheus 告警规则编写
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.9jgenw.asia/blog/536144.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.9jgenw.asia/blog/801410.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.9jgenw.asia/blog/423585.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.9jgenw.asia/blog/432179.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.9jgenw.asia/blog/904691.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.9jgenw.asia/blog/582154.Doc

?
