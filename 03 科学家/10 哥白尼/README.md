<div align="center">

# copernicus.skill

> *"认识到显而易见的事实往往需要最大的勇气。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

**将哥白尼的范式革命思维、以证据挑战权威的勇气与长期观察积累的方法蒸馏进 Claude，让 AI 敢于质疑默认假设，从根本上重新审视问题的参照系。**

</div>
---

## 效果示例

### 示例 1：质疑一个团队的技术架构假设

> **用户**：我们团队坚持用微服务架构，但项目越来越难维护了。
>
> **Claude (copernicus-perspective)**：让我做一次"哥白尼式转向"——也许问题不是微服务不够好，而是你们的参照系选错了。当年所有人都认为地球是宇宙中心，天体运行的复杂本轮-均轮模型就是"微服务化"的古代版本——不断增加复杂性来修补一个错误的基本假设。你的基本假设是什么？"每个功能都应该是独立服务"——这个假设在你们 5 人团队、单一产品线的背景下，可能就是你们的"地心说"。证据在这里：部署次数下降 40%、跨服务 bug 增加 3 倍、团队大量时间花在基础设施上……

### 示例 2：重新审视一个产品的核心指标

> **用户**：我们的 DAU 一直在涨，但收入没怎么增长。
>
> **Claude (copernicus-perspective)**：你正在经历一个"本轮现象"——用越来越复杂的解释来维护一个可能错误的中心假设。你的"地心说"是："DAU 增长 = 产品健康"。让我换一个参照系：如果我们把"用户价值密度"而非"用户数量"放在中心呢？观察数据——DAU 涨了 50%，但平均使用时长下降了 30%，付费转化率下降了 60%。这些数据就像第谷的天文观测数据，它们在告诉你：当前的模型解释不了现实。你需要一次范式革命……

### 示例 3：挑战一个行业"最佳实践"

> **用户**：所有人都说代码覆盖率要达到 80% 以上，我们应该追这个指标吗？
>
> **Claude (copernicus-perspective)**：我花了三十年观察天空才敢说地球不是中心。让我也仔细观察一下"80% 覆盖率"这个权威论断。证据一：Google 的研究显示，覆盖率与 bug 发现率的相关性在 60% 之后迅速衰减。证据二：高覆盖率项目中，大量测试只是在测试 getter/setter 这类无意义的代码。证据三：真正导致事故的往往是集成层面和边界条件，而非单元逻辑。谨慎但坚定的结论：80% 不是真理，它是一种"地心说式"的简化。真正应该追踪的指标是……

### 示例 4：分析一个失败的项目

> **用户**：我们的项目做了一年，最后发现用户根本不需要这个功能。
>
> **Claude (copernicus-perspective)**：这是一个经典的范式陷阱——你们在错误的参照系里工作了一年。让我帮你做一次事后的"天体运行论"分析。首先，你们最初的核心假设是什么？"用户需要 X 功能"——这个假设什么时候开始出现裂缝的？通常不是最后才发现，而是很早就有信号，只是被忽略了（就像古代天文学家忽略了行星逆行的真正含义）。回顾你的数据：第 3 个月的用户测试反馈、第 5 个月的 beta 数据、第 8 个月的留存率下降——这些都是"观测异常"，但当时被用"本轮"（更多功能、更好 UI）来解释了……

---

## 安装

```bash
npx skills add Panmax/copernicus-skill
```

---

## 蒸馏了什么

本 Skill 从哥白尼的思维方式中蒸馏了以下核心模式：

- **范式革命意识**：自动检测当前分析框架是否基于错误的"中心假设"，勇于提出完全不同的参照系。
- **以证据挑战权威**：不迷信"最佳实践"和"行业标准"，用数据和观测结果说话。
- **长期积累与谨慎判断**：哥白尼积累了数十年的观测数据才发表日心说。重大结论需要充分的证据支撑。
- **参照系转换**：问题可能不是"怎么在当前框架下做得更好"，而是"我们是否选错了框架"。
- **简洁性原则**：如果一个模型需要越来越多的"补丁"来解释现实，那么模型本身可能是错的。正确的模型应该更简洁。

---

## 调研来源

- 《天体运行论》（De revolutionibus orbium coelestium, 1543）——日心说的奠基之作
- 哥白尼与托勒密地心说的对比分析
- Thomas Kuhn《科学革命的结构》——范式转换理论
- 第谷·布拉赫的天文观测数据及其对哥白尼模型的验证
- Owen Gingerich《The Book Nobody Read: Chasing the Revolutions of Nicolaus Copernicus》

详见 [references/research.md](references/research.md)。

---

## 仓库结构

```
copernicus-skill/
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
