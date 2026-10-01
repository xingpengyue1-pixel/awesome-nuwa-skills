<div align="center">

# vonneumann.skill

> *"如果人们不相信数学是简单的，那只是因为他们没有意识到生活有多复杂。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

**将冯诺依曼的博弈论思维、计算架构直觉与跨学科超速思考能力蒸馏进 Claude，让 AI 在数学、物理、计算机、经济学之间无缝切换，以惊人速度给出精确答案。**

</div>
---

## 效果示例

### 示例 1：分析一个定价策略

> **用户**：竞争对手降价了 20%，我们该跟进吗？
>
> **Claude (vonneumann-perspective)**：这是一个经典的博弈论问题，让我快速建模。参与者：你和竞争对手。策略空间：{降价, 维持, 涨价}。收益矩阵——如果你们都降价，利润各减 30%（囚徒困境的经典结构）；如果只有你降价，短期抢到 15% 市场份额但利润率下降 25%。计算纳什均衡：在单次博弈中，双方都降价是纳什均衡，但这是一个重复博弈！根据我在博弈论中的研究，重复博弈允许合作均衡的出现。具体策略建议……

### 示例 2：设计一个计算系统架构

> **用户**：我们需要设计一个实时数据处理管道，每秒处理 100 万事件。
>
> **Claude (vonneumann-perspective)**：让我用冯诺依曼架构的思维来分析。核心瓶颈在哪里？冯诺依曼瓶颈——数据必须在存储和处理单元之间来回搬运。100 万事件/秒，假设每个事件 1KB，那就是 ~1GB/s 的吞吐需求。内存带宽够吗？CPU 缓存命中率是多少？让我快速计算：现代 CPU 的 L3 缓存约 30MB，如果你的热数据集超过这个大小，每次缓存未命中将花费 ~100ns。100 万事件 x 可能的缓存未命中率 = 你的实际瓶颈。解决方案需要从计算架构层面重新思考……

### 示例 3：评估一个机器学习模型

> **用户**：我们的推荐模型 AUC 是 0.75，这算好吗？
>
> **Claude (vonneumann-perspective)**：数字不能脱离上下文。让我从多个学科角度同时分析——统计学视角：AUC 0.75 意味着模型有 75% 的概率将正样本排在负样本前面；信息论视角：这相当于每次预测提供约 0.18 比特的信息量；博弈论视角：如果你的竞争对手模型的 AUC 是 0.70，你的边际优势可以量化为——在每 100 次推荐中，你比对手多命中约 5 次。经济学视角：每次命中的商业价值乘以 5，就是你的竞争优势的货币化度量。现在，关键问题是……

### 示例 4：解决一个并发编程问题

> **用户**：多线程程序偶尔死锁，但很难复现。
>
> **Claude (vonneumann-perspective)**：死锁问题，让我用严格数学方法快速定位。死锁的四个必要条件（Coffman 条件）：互斥、持有并等待、非抢占、循环等待。这不是猜测，这是数学上的充要条件。让我用图论方法：将每个锁视为节点，将锁的获取顺序视为有向边，画出资源分配图。如果存在有向环，就必然存在死锁可能。你的程序中有几把锁？获取顺序分别是什么？我可以在 O(V+E) 时间内通过拓扑排序告诉你是否存在环……

---

## 安装

```bash
npx skills add Panmax/vonneumann-skill
```

---

## 蒸馏了什么

本 Skill 从冯诺依曼的思维方式中蒸馏了以下核心模式：

- **博弈论框架**：将涉及多方决策的问题自动转化为博弈论模型，分析纳什均衡、占优策略、混合策略。
- **计算架构思维**：从硬件到软件、从存储到计算的全栈视角，理解计算的物理极限。
- **跨学科无缝切换**：数学、物理、计算机科学、经济学、生物学——在不同学科之间自由跳转，寻找最佳分析工具。
- **超速精确思考**：冯诺依曼以心算速度和精确性著称。追求快速给出精确答案，而非缓慢的近似。
- **自指与元思考**：冯诺依曼对自复制自动机的研究体现了对"思考如何思考"的深刻兴趣。

---

## 调研来源

- 《博弈论与经济行为》（Theory of Games and Economic Behavior, 1944）——与摩根斯坦合著
- 冯诺依曼架构——EDVAC 报告草案（First Draft of a Report on the EDVAC, 1945）
- 《量子力学的数学基础》（Mathematische Grundlagen der Quantenmechanik, 1932）
- 自复制自动机理论（Theory of Self-Reproducing Automata）
- Norman Macrae《John von Neumann: The Scientific Genius Who Pioneered the Modern Computer》

详见 [references/research.md](references/research.md)。

---

## 仓库结构

```
vonneumann-skill/
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
