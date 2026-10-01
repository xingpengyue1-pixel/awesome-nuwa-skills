<div align="center">

# grahamben-skill.skill

> "In the short run, the market is a voting machine but in the long run, it is a weighing machine." — Benjamin Graham

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将本杰明·格雷厄姆的价值投资思维方式注入 Claude Code,用安全边际和理性分析守护每一个投资决策。**

</div>

---

## 效果示例

### 示例 1：评估一只股票是否值得投资

> 用户: 这家公司PE 35倍,但增长很快,ROE 25%,值得买吗?
>
> Claude (Graham模式): 让我们先做一个保守的估计。PE 35倍意味着你在为未来的增长支付溢价。根据格雷厄姆公式,假设未来7-10年年化增长15%,内在价值对应的PE约为38.5倍。安全边际只有约9%——远低于我要求的33%。记住:好公司+高价格=坏投资。市场先生现在情绪高涨,他给出的报价反映的是乐观预期而非保守现实...

### 示例 2：市场大跌时的决策

> 用户: 市场暴跌20%了,我该抄底吗?
>
> Claude (Graham模式): 市场先生今天恐慌了,他给出的报价很可能低于企业的内在价值。但"抄底"是投机者的语言,我们用价值投资者的方式来思考。首先检查你的资产配置:如果股票仓位已经低于你的目标比例(比如低于50%),那么按纪律再平衡是合理的。然后逐一评估你关注的标的——它们现在的安全边际是否达到33%以上?...

### 示例 3：投资组合配置

> 用户: 我有100万准备投资,应该怎么分配?
>
> Claude (Graham模式): 作为防御型投资者的基准,我建议50万配置于高质量债券(或债券基金),50万配置于满足格雷厄姆选股标准的股票。股票部分应分散在至少10-15只不同行业的标的中,每只需通过严格的筛选:市盈率<15、市净率<1.5、连续盈利10年以上...

### 示例 4：评估一家公司的财务健康状况

> 用户: 这家公司流动比率1.2,负债率70%,但利润一直在增长,安全吗?
>
> Claude (Graham模式): 让我直说——这些数字让我担忧。流动比率1.2远低于格雷厄姆要求的2.0标准,这意味着短期偿债能力勉强。负债率70%意味着每赚1块钱的资产中有7毛钱是借来的。利润增长是好的,但利润增长建立在高杠杆之上就像在流沙上建楼——即使在最坏的情况下...

---

## 安装

```bash
npx skills add Panmax/grahamben-skill
```

---

## 蒸馏了什么

本 skill 将本杰明·格雷厄姆的价值投资体系蒸馏为 Claude Code 可执行的分析框架:

- **安全边际原则** — 只在价格远低于内在价值时才买入,要求至少33%的缓冲区
- **市场先生模型** — 用经典比喻理解市场情绪,利用而非被利用
- **内在价值评估** — 格雷厄姆估值公式、净流动资产价值法(Net-Net)、资产负债表深度分析
- **投资vs投机区分** — 严格定义投资的三个要素:深入分析、本金安全、适当回报
- **防御型/进取型分类** — 根据投资者类型给出差异化的策略建议
- **收益质量分析** — 识别会计操纵、区分经常性与非经常性收益
- **分散投资纪律** — 系统性的资产配置和再平衡策略

---

## 调研来源

详见 [references/research.md](references/research.md),包括:

- 《聪明的投资者》(The Intelligent Investor) — 投资者的圣经
- 《证券分析》(Security Analysis) — 价值投资的方法论基石
- 格雷厄姆-纽曼公司的投资记录与案例分析
- 巴菲特对格雷厄姆思想的传承与发展
- 塞斯·卡拉曼《安全边际》的现代诠释

---

## 仓库结构

```
grahamben-skill/
├── SKILL.md                        # Skill 核心定义文件
├── README.md                       # 项目说明
├── LICENSE                         # MIT 许可证
├── examples/
│   └── demo-conversation.md        # 示例对话
└── references/
    └── research.md                 # 调研来源与参考资料
```

---

## 更多 Skill

更多人物 Skill 请查看 [Awesome 女娲.skill](https://github.com/Panmax/awesome-nuwa)。

---

<div align="center">

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
