<div align="center">

# marks.skill

> "投资中最重要的事，不是你买了什么，而是你付了多少钱。" ------ 霍华德·马克斯

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将霍华德·马克斯的第二层思维、周期理论与风险意识蒸馏为 Claude Code 可调用的 skill，让 AI 用橡树资本的深度思考方式帮你穿越周期、管控风险、逆向投资。**

</div>

---

## 效果示例

### 1. 第二层思维分析

> **用户:** 大家都说经济要衰退了，我应该卖出所有股票吗？
>
> **Claude (marks-perspective):** 这是典型的"第一层思维"：经济要衰退→卖出股票。让我带你进入第二层思维：如果所有人都认为经济要衰退，那么这个预期已经反映在价格里了。问题不是"经济会不会衰退"，而是"衰退的程度会比市场已经定价的更糟还是更好"？当共识是悲观的时候，超额收益来自于发现"没那么糟"。反过来，当共识是乐观的时候，风险来自于"没那么好"。第二层思维要求你永远比市场多想一步。

### 2. 周期定位判断

> **用户:** 现在的市场处于周期的哪个位置？
>
> **Claude (marks-perspective):** 我无法精确告诉你我们在周期的哪个刻度，但我可以帮你判断温度。问这几个问题：(1) 投资者现在更贪婪还是更恐惧？(2) 信贷市场是宽松还是收紧？(3) 新发行的债券条款对借款人友好还是对贷款人友好？(4) 估值相对于历史中位数是高还是低？(5) 媒体标题是"错过机会"还是"避免风险"？记住我的核心判断：我们不知道要去哪里，但最好知道我们现在在哪里。周期永远不会消失，钟摆永远不会停在中间。

### 3. 风险的本质认知

> **用户:** 我买了一只波动很小的基金，应该算低风险吧？
>
> **Claude (marks-perspective):** 这是对风险最常见的误解。波动率不等于风险。真正的风险是永久性损失的可能性。一只波动很小的基金可能持有大量低流动性资产——表面平静，水面下暗流涌动。就像2008年之前那些"从不亏损"的CDO产品。我在橡树资本学到的最重要的一课：风险意味着可能发生的结果比实际发生的结果更广泛。你不能因为结果是好的就说当时没有风险。出色的投资者不是承担更多风险来获得更高回报的人，而是在承担相同风险时获得更高回报的人。

### 4. 逆向投资的纪律

> **用户:** 所有人都在买某个热门赛道，我是不是也应该跟上？
>
> **Claude (marks-perspective):** "所有人都在买"——这六个字应该让你的警报系统响起来，而不是让你的FOMO发作。投资中最危险的话不是"这次不同"，而是"价格只会涨"。当资本大量涌入一个赛道时，回报的前景必然下降——因为价格已经被推高了。逆向投资不是简单地"和大家反着来"，而是在大家的乐观已经把价格推到不合理水平时保持谨慎，在大家的悲观已经创造了安全边际时勇于出手。买得好比买好东西更重要。

---

## 安装

```bash
npx skills add Panmax/marks-skill
```

---

## 蒸馏了什么

本 skill 从霍华德·马克斯的思想体系中蒸馏了以下核心方法论：

- **第二层思维（Second-Level Thinking）** —— 超越表面共识，追问"然后呢？"
- **周期理论** —— 理解并尊重市场周期的不可避免性，钟摆永远不会停在中间
- **风险认知** —— 风险不是波动率，而是永久性资本损失的可能性
- **逆向投资** —— 在共识乐观时谨慎，在共识悲观时出手
- **"买得好"vs"买好东西"** —— 价格是决定投资成败的核心变量
- **不确定性思维** —— 拥抱概率分布而非确定性预测
- **防御性投资** —— 避免输比追求赢更重要
- **市场温度计** —— 用多维指标判断当前市场处于周期的哪个阶段

---

## 调研来源

- 《投资最重要的事》(The Most Important Thing)
- 《周期》(Mastering the Market Cycle)
- 橡树资本（Oaktree Capital）备忘录合集（1990至今）
- 《投资最重要的事（全新升级版）》含巴菲特等人批注
- 哥伦比亚商学院价值投资课程讲义
- Bloomberg、CNBC 深度专访
- CFA 协会年会演讲系列
- 与沃伦·巴菲特、查理·芒格的公开对谈记录

详细调研内容见 [`references/research.md`](./references/research.md)。

---

## 仓库结构

```
marks-skill/
├── SKILL.md                        # Claude Code skill 定义文件
├── README.md                       # 本文件
├── LICENSE                         # MIT 许可证
├── examples/
│   └── demo-conversation.md        # 完整对话演示
└── references/
    └── research.md                 # 调研资料与来源
```

---

## 更多 Skill

更多人物 Skill 请查看 [Awesome 女娲.skill](https://github.com/Panmax/awesome-nuwa)。

---

<div align="center">

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
