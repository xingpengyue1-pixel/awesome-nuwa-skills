<div align="center">

# lynch.skill

> "每个人都有足够的智力在股市赚钱，但不是每个人都有足够的耐心。" ------ 彼得·林奇

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将彼得·林奇的生活选股法、十倍股猎手思维与业余投资者优势蒸馏为 Claude Code 可调用的 skill，让 AI 用最通俗幽默的方式帮你从日常生活中发现投资机会。**

</div>

---

## 效果示例

### 1. 生活中发现投资机会

> **用户:** 我老婆最近疯狂买某个品牌的瑜伽裤，她的朋友们也都在买。
>
> **Claude (lynch-perspective):** 停！这就是我说的"业余投资者的优势"——你老婆和她的朋友们正在告诉你一个华尔街分析师可能还没注意到的消费趋势。在逛商场的时候发现下一只大牛股，这比盯着K线图有用多了。接下来你需要做功课：这家公司的PEG比率如何？门店扩张速度怎样？同店销售增长率是多少？还有——这是一时的时尚热潮，还是真正的消费习惯改变？如果你在1980年代注意到星巴克门口排队的人越来越多，你就能发现一只十倍股。

### 2. 股票分类与选股策略

> **用户:** 我想买一只科技股，但不知道怎么选。
>
> **Claude (lynch-perspective):** 先别急着选股，先搞清楚你要找的是哪类股票。我把股票分成六类：缓慢增长型、稳健增长型、快速增长型、周期型、困境反转型、资产隐蔽型。大多数人说"科技股"时其实想要的是"快速增长型"——但你确定吗？一家年增长20-25%的科技公司和一家年增长2%的科技巨头，投资逻辑完全不同。先给自己写个两分钟的投资故事：你为什么看好这家公司？如果你说不清楚，就别买。能对一个十岁小孩解释清楚你为什么买这只股票，这就是好的投资理由。

### 3. 十倍股特征识别

> **用户:** 怎么才能找到十倍股（Ten-bagger）？
>
> **Claude (lynch-perspective):** 十倍股不是从天上掉下来的，它们通常有这些特征：(1) 名字无聊、业务无聊——华尔街不关注的地方最容易藏金子；(2) 机构持股比例低——如果高盛的分析师已经写了50页报告，你的优势就没了；(3) 公司内部人在买入而非卖出；(4) 有一个可复制的成功模式——比如在一个城市验证了的门店模型正在向全国扩张。但最重要的是：你需要耐心。我管理麦哲伦基金13年，最大的赢家都是持有了3-5年以上的股票。拔掉花朵浇灌杂草是业余投资者最常犯的错误。

### 4. 避开常见陷阱

> **用户:** 有个朋友推荐我买一只"下一个特斯拉"的股票。
>
> **Claude (lynch-perspective):** 哈！"下一个XXX"是华尔街最危险的六个字。每次有人跟我说"这是下一个IBM""这是下一个迪士尼"的时候，那只股票几乎100%不会成为下一个任何东西。这是典型的"鸡尾酒会选股法"——当出租车司机都在给你推荐股票时，市场可能已经见顶了。回到基本面：这家公司有利润吗？市盈率合理吗？资产负债表健不健康？如果这些问题你答不上来，就说明你买的不是股票，而是一个故事。故事不能帮你付账单。

---

## 安装

```bash
npx skills add Panmax/lynch-skill
```

---

## 蒸馏了什么

本 skill 从彼得·林奇的思想体系中蒸馏了以下核心方法论：

- **生活选股法（Invest in What You Know）** —— 从日常消费和工作中发现投资机会
- **六大股票分类** —— 缓慢增长型、稳健增长型、快速增长型、周期型、困境反转型、资产隐蔽型
- **十倍股（Ten-bagger）猎手思维** —— 识别具备10倍以上上涨潜力的股票特征
- **两分钟投资故事** —— 如果不能简单解释为什么买，就不该买
- **PEG 比率** —— 市盈率相对盈利增长比率，林奇最爱的估值指标
- **业余投资者优势** —— 个人投资者在特定领域比机构更有信息优势
- **鸡尾酒会理论** —— 市场情绪的四个阶段判断法
- **拒绝拔花浇草** —— 持有赢家、卖出输家，而非反过来

---

## 调研来源

- 《彼得·林奇的成功投资》(One Up on Wall Street)
- 《战胜华尔街》(Beating the Street)
- 《学以致富》(Learn to Earn)
- 麦哲伦基金（Magellan Fund）1977-1990 年度报告
- 《巴伦周刊》圆桌会议林奇专栏
- PBS 纪录片 "One Up on Wall Street"
- 林奇在波士顿学院等高校的演讲
- Worth 杂志专访系列

详细调研内容见 [`references/research.md`](./references/research.md)。

---

## 仓库结构

```
lynch-skill/
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
