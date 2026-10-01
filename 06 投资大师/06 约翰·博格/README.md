<div align="center">

# bogle.skill

> "不要在干草堆里找那根针，直接买下整个干草堆。" ------ 约翰·博格

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将约翰·博格的指数基金哲学、低成本投资原则与长期持有信念蒸馏为 Claude Code 可调用的 skill，让 AI 用先锋集团创始人的朴素智慧帮你构建简单有效的投资方案。**

</div>

---

## 效果示例

### 1. 成本是确定的，回报是不确定的

> **用户:** 有人给我推荐一个年管理费2%的主动基金，说能跑赢指数。
>
> **Claude (bogle-perspective):** 让我给你算一笔简单的账。假设市场年化回报7%，管理费2%意味着你每年实际拿到5%。听起来差距不大？30年后，100万投入在7%下会变成761万，在5%下只有432万——你白白送出了329万。而且这是确定的损失，换来的只是一个不确定的"跑赢指数"的承诺。数据告诉我们：在任何15年周期内，大约90%的主动基金跑不赢它们的基准指数。你愿意用确定的高成本去赌一个10%的概率吗？在投资中，你付出的每一分成本都是确定的，而回报永远是不确定的。

### 2. 简单投资组合设计

> **用户:** 我30岁，想开始长期投资，但不知道从哪里开始。
>
> **Claude (bogle-perspective):** 好消息是：你不需要成为金融专家就能做好投资。我的建议异常简单——简单到很多人不愿意相信它真的有效。核心就两步：(1) 买一只覆盖全市场的低成本指数基金；(2) 根据你的年龄配置一部分债券指数基金。一个粗略的规则：债券比例约等于你的年龄，所以30岁可以70%股票指数+30%债券指数。然后——这是最难的部分——什么都不做。不要看每日涨跌，不要听市场噪音，每月定投，坚持30年。这个策略会跑赢90%的专业投资者，而你花在投资上的时间每月不超过30分钟。

### 3. 对抗华尔街的营销话术

> **用户:** 基金销售跟我说，他们有独家的量化策略，历史收益非常好。
>
> **Claude (bogle-perspective):** 我在这个行业待了将近60年，让我翻译一下华尔街的话术："独家量化策略"意味着你无法验证它是真是假；"历史收益非常好"意味着他们从所有策略中挑了表现最好的给你看——这叫幸存者偏差。华尔街的商业模式是把简单的事情复杂化，然后向你收取"复杂化"的费用。整个基金行业的利润来源只有一个：从投资者口袋里掏钱。我创建先锋集团的初衷就是打破这个循环——让基金公司由投资者拥有，利润返还给投资者。记住：在投资中，你付出的费用越少，留给自己的回报就越多。这是算术，不是观点。

### 4. 市场波动时的定力

> **用户:** 市场跌了20%，我的指数基金也跟着跌了，要不要先卖出避避风险？
>
> **Claude (bogle-perspective):** 我理解你的恐惧，但请听我说：在过去100年里，市场经历了无数次20%以上的下跌，但长期趋势始终向上。如果你在2008年金融危机时卖出了你的指数基金，你就会错过2009年开始的十年大牛市。择时是一个需要你做对两次的决定——既要在正确的时间卖出，又要在正确的时间买回。几乎没有人能持续做对这两个决定。我的建议是：坚持你的投资计划。如果市场下跌让你焦虑，说明你的股票比例可能超出了你的风险承受能力——调整配比，但不要离开市场。时间在市场里比择时进出市场重要得多。

---

## 安装

```bash
npx skills add Panmax/bogle-skill
```

---

## 蒸馏了什么

本 skill 从约翰·博格的思想体系中蒸馏了以下核心方法论：

- **指数化投资（Indexing）** —— 买下整个市场，不试图挑选赢家
- **成本至上** —— 费用是投资中唯一可以确定控制的变量
- **长期持有（Stay the Course）** —— 时间在市场里远比择时进出重要
- **简单优于复杂** —— 最有效的投资策略往往是最简单的
- **回归均值** —— 过去的赢家和输家都会向均值回归
- **投资者利益优先** —— 基金行业应该为投资者服务，而非从投资者身上获利
- **算术真理** —— 全体投资者的回报=市场回报-成本，这是不可逾越的数学
- **反对投机** —— 区分投资（基于长期价值）和投机（基于短期价格波动）

---

## 调研来源

- 《共同基金常识》(Common Sense on Mutual Funds)
- 《长赢投资》(The Little Book of Common Sense Investing)
- 《坚守》(Stay the Course)
- 《够了》(Enough: True Measures of Money, Business, and Life)
- 《博格谈共同基金》(Bogle on Mutual Funds)
- 先锋集团（Vanguard Group）年报与创始人信件
- 博格在 Bogleheads 年度大会的演讲
- 《华尔街日报》《纽约时报》专栏与专访

详细调研内容见 [`references/research.md`](./references/research.md)。

---

## 仓库结构

```
bogle-skill/
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
