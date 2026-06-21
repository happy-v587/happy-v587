### Hi there 👋

我是 Happy，一名长期做云数据库、云原生数据库、Serverless 数据库内核和管控建设的工程师。云计算从业 7 年，在这之前做过图像处理方向的目标检测、目标识别和目标追踪。

- 🔭 关注方向：MySQL、TiDB、RocksDB、Redis-compatible KV、数据库备份恢复、云原生数据库管控
- 🔨 常用工具：Linux、Docker、Kubernetes
- 📺 常用语言：Go、Rust、C/C++、Python、TypeScript
- 👁 近期兴趣：AI Agent、个人知识系统、视频自动化、开发者效率工具

## 项目地图

下面是从我的公开 GitHub 仓库整理出来的一份项目概览。这里优先列原创项目和有代表性的实验项目；fork 仓库更多体现我长期关注和研究的技术栈。

### 数据库、分布式系统与云原生

这一类是我的主线方向，仓库里大量项目围绕数据库内核、KV 存储、数据库管控、备份恢复和一致性测试展开。

- [awesome-database](https://github.com/happy-v587/awesome-database)：数据库资料收集仓库，覆盖数据库内核、云原生数据库和相关生态。
- [jepsen-pikiwidb](https://github.com/happy-v587/jepsen-pikiwidb)：围绕 PikiwiDB 做 Jepsen 一致性测试的实验项目。
- [pikiwidb](https://github.com/happy-v587/pikiwidb)、[kiwi](https://github.com/happy-v587/kiwi)：关注 Redis-compatible、RocksDB、Raft、多租户和持久化 KV 存储方向。
- [tidb](https://github.com/happy-v587/tidb)、[pd](https://github.com/happy-v587/pd)、[kvproto](https://github.com/happy-v587/kvproto)、[tinykv](https://github.com/happy-v587/tinykv)：TiDB / TiKV 生态相关学习和研究。
- [tidb-operator](https://github.com/happy-v587/tidb-operator)、[kubeblocks](https://github.com/happy-v587/kubeblocks)、[mysql-operator](https://github.com/happy-v587/mysql-operator)：数据库在 Kubernetes 上的部署、运维和管控。
- [mysql-server](https://github.com/happy-v587/mysql-server)、[PolarDB-for-PostgreSQL](https://github.com/happy-v587/PolarDB-for-PostgreSQL)、[MaxScale](https://github.com/happy-v587/MaxScale)：关系型数据库内核、云原生数据库和数据库代理方向。
- [myhoard](https://github.com/happy-v587/myhoard)、[pghoard](https://github.com/happy-v587/pghoard)、[binlog2sql](https://github.com/happy-v587/binlog2sql)、[py_innodb_page_info](https://github.com/happy-v587/py_innodb_page_info)：备份恢复、binlog 解析和 InnoDB 页面分析工具链。
- [sysbench](https://github.com/happy-v587/sysbench)、[tipocket](https://github.com/happy-v587/tipocket)：数据库压测和稳定性测试相关工具。

### 开发者工具与自动化

这类项目更偏“自己用得上的工具”，通常围绕抓取、代理、任务管理、效率自动化和 Agent 工作流。

- [http-proxy-dashboard](https://github.com/happy-v587/http-proxy-dashboard)：轻量 HTTP/HTTPS 代理和实时 Web Dashboard，用于捕获、过滤、搜索、统计和导出网络请求，支持 JSON / HAR 导出。
- [github_trending.py](https://github.com/happy-v587/github_trending.py)：GitHub Trending 抓取工具，支持按语言、时间范围过滤，带缓存、表格输出、JSON / CSV 导出。
- [auto-commit](https://github.com/happy-v587/auto-commit)：近期自动化方向的小实验。
- [shell-tool](https://github.com/happy-v587/shell-tool)：日常 Shell 工具集合。
- [task-hub](https://github.com/happy-v587/task-hub)：Vue todo list 练手项目。
- [mcp-zero](https://github.com/happy-v587/mcp-zero)、[learn-claude-code](https://github.com/happy-v587/learn-claude-code)、[claude-code](https://github.com/happy-v587/claude-code)：关注 MCP、Claude Code 和 AI Agent 开发方式的学习与研究。

### AI、个人知识系统与内容生产

这类项目体现了我最近对 AI 应用、信息流整理、视频生成和数字人的兴趣。

- [the-second-brain](https://github.com/happy-v587/the-second-brain)：个人第二大脑项目，目标是把公众号、书籍、知乎、小红书、短视频、电商等信息流中的点赞和收藏沉淀为知识中心，再用 AI 总结兴趣、风格和 todo。
- [szrzb](https://github.com/happy-v587/szrzb)：数字人直播方案相关探索。
- [lhpt](https://github.com/happy-v587/lhpt)：量化平台实验。
- [interflow-video-cut](https://github.com/happy-v587/interflow-video-cut)、[videocut-skills](https://github.com/happy-v587/videocut-skills)：视频剪辑 Agent 和卡片式成片流程相关探索。
- [TrendRadar](https://github.com/happy-v587/TrendRadar)：多平台热点聚合、AI 分析和消息推送方向的工具关注。
- [stable-diffusion](https://github.com/happy-v587/stable-diffusion)、[stable-diffusion-webui](https://github.com/happy-v587/stable-diffusion-webui)、[metahuman-stream](https://github.com/happy-v587/metahuman-stream)、[Mora](https://github.com/happy-v587/Mora)：图像生成、视频生成和实时数字人方向的学习仓库。

### 计算机视觉与早期算法项目

早期项目主要集中在目标检测、目标跟踪、SVM 和一些视觉实验。

- [KCF_IOU_Tracker](https://github.com/happy-v587/KCF_IOU_Tracker)：多目标跟踪实验，在 MOT15 / MOT16 数据集上做过测试。
- [iou-tracker](https://github.com/happy-v587/iou-tracker)、[mosse-tracker](https://github.com/happy-v587/mosse-tracker)、[hog_pedestran_detect_python](https://github.com/happy-v587/hog_pedestran_detect_python)：目标跟踪、行人检测和传统 CV 算法学习。
- [svm-mnist](https://github.com/happy-v587/svm-mnist)：使用 SVM 识别 MNIST 的 C 语言实验。

### 小工具、爬虫与趣味项目

这些项目跨度比较大，更多是学习、练手和解决具体问题。

- [tuchong-Spider](https://github.com/happy-v587/tuchong-Spider)：图虫摄影作品下载爬虫。
- [wechat_jump_gui](https://github.com/happy-v587/wechat_jump_gui)、[wechat_jump_gui_bin](https://github.com/happy-v587/wechat_jump_gui_bin)、[wechat_jump_game](https://github.com/happy-v587/wechat_jump_game)：微信跳一跳辅助和 GUI 实验。
- [snake](https://github.com/happy-v587/snake)：Python 贪吃蛇小游戏。
- [leetcode](https://github.com/happy-v587/leetcode)：Go 语言算法题练习。
- [real-time-fund](https://github.com/happy-v587/real-time-fund)：基金实时估值查看工具。
- [blivechat](https://github.com/happy-v587/blivechat)、[blivedm](https://github.com/happy-v587/blivedm)：B 站直播弹幕和 OBS 评论栏相关工具关注。

## 我关注的技术关键词

`MySQL` · `TiDB` · `RocksDB` · `Redis-compatible KV` · `Raft` · `Kubernetes Operator` · `Database Backup & Recovery` · `Jepsen` · `Go` · `Rust` · `C/C++` · `Python` · `TypeScript` · `AI Agent`

<!-- <br />

[![happy-v587's GitHub stats](https://github-readme-stats.vercel.app/api?username=happy-v587&show_icons=true&theme=tokyonight)](https://github.com/vn7n24fzkq/github-profile-summary-cards)

<h2></h2>
<br />

![Visitor Count](https://profile-counter.glitch.me/happy-v587/count.svg) -->
