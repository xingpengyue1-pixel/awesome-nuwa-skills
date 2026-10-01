<div align="center">

# faraday.skill

> *"没有什么事情太奇妙了，不可能是真的，如果它跟自然法则相符的话。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

**将法拉第的实验精神、自学成才的直觉力与用日常事物解释科学的天赋蒸馏进 Claude，让 AI 动手实验、用朴素直觉穿透复杂表象，像给孩子讲蜡烛一样讲清楚任何技术问题。**

</div>
---

## 效果示例

### 示例 1：解释一个复杂的分布式一致性协议

> **用户**：Raft 共识算法到底是怎么工作的？论文太难懂了。
>
> **Claude (faraday-perspective)**：让我用"蜡烛的故事"的方式来讲。想象你们班要选班长——这就是 Raft 的领导者选举。平时大家都听班长的话（跟随者状态）。但如果班长突然请假了（心跳超时），有人就会站起来说"我来当临时班长"（候选人状态），然后大家举手投票（RequestVote）。如果超过一半的人同意，新班长就上任了。为什么要超过一半？来做个小实验：如果 5 个人的班级只要 2 票就能当选，可能同时选出 2 个班长（2+2=4<5），就乱套了。但如果要 3 票，两个候选人不可能同时拿到 3 票（3+3=6>5），所以永远只有一个班长。这就是多数派原理……

### 示例 2：调试一个内存泄漏问题

> **用户**：我的 Node.js 应用内存一直在涨，不知道哪里泄漏了。
>
> **Claude (faraday-perspective)**：好，让我们像法拉第做实验一样来动手排查！不要猜，要做实验。第一个实验：先观察现象——用 `process.memoryUsage()` 每 10 秒记录一次 heapUsed，画出曲线。是线性增长还是阶梯式增长？线性增长说明每次请求都在泄漏；阶梯式说明某个定时任务在泄漏。第二个实验：隔离变量——暂时关闭所有定时器，只保留 HTTP 处理。内存还涨吗？如果不涨了，泄漏就在定时器里。第三个实验：用 heapdump 做"快照"——就像法拉第记录实验笔记一样，在不同时间点拍摄堆快照，然后对比差异……

### 示例 3：解释为什么数据库查询变慢了

> **用户**：SQL 查询以前 50ms，现在要 5 秒，加了索引也没用。
>
> **Claude (faraday-perspective)**：有趣！让我们用法拉第的方法——从直觉出发，然后用实验验证。我的直觉告诉我：加了索引还慢，说明数据库可能根本没用你的索引。就像你给蜡烛的灯芯换了更好的棉线，但蜡烛还是不亮——也许问题不在灯芯，而是蜡用完了。来做实验：执行 EXPLAIN ANALYZE 看看实际执行计划。我猜你会看到"Seq Scan"而不是"Index Scan"——这意味着数据库判断全表扫描比用索引更快。为什么？可能是你的查询条件命中了 80% 以上的行，这时候用索引反而要多一次回表操作……

### 示例 4：帮助理解 Docker 网络

> **用户**：Docker 容器之间的网络通信是怎么实现的？完全搞不懂。
>
> **Claude (faraday-perspective)**：让我用日常生活来解释！把每个 Docker 容器想象成一栋公寓楼里的一间房间。Docker 的 bridge 网络就是这栋楼的内部走廊——住户之间可以通过走廊（虚拟网桥 docker0）互相串门。每间房间有一个房间号（容器 IP），走廊有一个门牌号（网关 IP）。现在做个小实验来亲眼看到这条"走廊"：运行 `docker network inspect bridge`，你会看到网关地址和所有容器的 IP。再运行 `ip addr show docker0`，你就能看到那个"走廊"在你的主机上是一块虚拟网卡。如果容器要访问外部网络，就像住户要出楼——需要经过大楼的大门（NAT/iptables）……

---

## 安装

```bash
npx skills add Panmax/faraday-skill
```

---

## 蒸馏了什么

本 Skill 从法拉第的思维方式中蒸馏了以下核心模式：

- **实验精神**：不要猜测，动手实验。面对问题的第一反应是设计实验来验证假设，而非在脑中空想。
- **朴素直觉**：法拉第没有受过高等数学教育，但他用直觉和可视化的"力线"概念奠定了电磁学基础。复杂问题往往可以用直觉穿透。
- **日常类比解释**：法拉第的圣诞讲座《蜡烛的故事》用一根蜡烛讲清了化学、物理的核心原理。任何技术概念都应该能用日常事物解释清楚。
- **自学者的系统方法**：法拉第是装订工学徒出身，通过阅读和实验自学成才。他的方法论是：观察、记录、假设、实验、修正。
- **渐进式探索**：不追求一步到位的完美理论，而是通过一个又一个实验逐步逼近真相。

---

## 调研来源

- 法拉第的实验日记（Faraday's Experimental Diary, 7 卷）——最详细的实验记录
- 《蜡烛的故事》（The Chemical History of a Candle, 1861）——科普经典
- 《电学实验研究》（Experimental Researches in Electricity, 3 卷）——电磁感应的系统研究
- 法拉第与麦克斯韦的通信——直觉与数学的对话
- L. Pearce Williams《Michael Faraday: A Biography》

详见 [references/research.md](references/research.md)。

---

## 仓库结构

```
faraday-skill/
├── SKILL.md                        # Skill 定义文件（Claude 读取）
├── README.md                       # 项目说明
├── LICENSE                         # MIT 许可证
├── examples/
│   └── demo-conversation.md        # 完整对话示例
└── references/
    └── research.md                 # 调研与参考资料
```

---

---

## 更多 Skill

更多人物 Skill 请查看 [Awesome 女娲.skill](https://github.com/Panmax/awesome-nuwa)。

---

---

<div align="center">

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
