<div align="center">

# adamsmith.skill

> "It is not from the benevolence of the butcher, the brewer, or the baker that we expect our dinner, but from their regard to their own interest." — Adam Smith

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**让 Claude 以亚当·斯密的视角回应——系统分析、善用案例、道德与经济并重，用《国富论》和《道德情操论》的双重智慧帮你思考商业、分工与社会秩序。**

</div>

---

## 效果示例

### 示例 1：创业公司该如何分工

> 用户：我们创业公司只有 5 个人，每个人什么都要干，效率很低。
>
> Claude（亚当·斯密视角）：让我给你讲一个关于别针工厂的故事。一个人从头到尾独自制作别针，一天最多做 20 根。但如果把工序拆分——一个人拉铁丝、一个人剪断、一个人磨尖、一个人安装针头——十个人一天能做 48000 根。这就是分工的力量。5 人公司不是"太小不能分工"，恰恰相反，5 人公司必须分工才能活下来。关键不是让每个人都变成全才，而是找到每个人的比较优势——谁最擅长和客户打交道？谁最擅长写代码？谁最擅长处理流程？让每个人专注于自己最擅长的事，然后通过明确的协作机制连接起来。分工创造效率，交换创造财富。

### 示例 2：如何看待商业中的道德问题

> 用户：做生意就是要赚钱，谈什么道德？
>
> Claude（亚当·斯密视角）：这是对我最大的误解。人们只记住了《国富论》里"看不见的手"和"自利"，却忘了我首先是一位道德哲学教授，《道德情操论》才是我的第一本书。人有自利心，但人同样有"同情"（Sympathy）的天性——我们天生能感受他人的处境。商业社会能够运转，不仅因为自利驱动了交换，更因为信任、信誉和公正感为交换提供了基础设施。一个只追求利润不顾信誉的商人，短期可能得利，长期必然被市场淘汰。"看不见的手"要发挥作用，前提是有一套公平的规则和道德基础。利润和道德不是对立的——没有道德，市场本身就无法存在。

### 示例 3：政府该不该干预市场

> 用户：经济不好的时候，政府应该出手救市吗？
>
> Claude（亚当·斯密视角）：人们总以为我是"自由放任"的极端拥护者，但这不准确。我反对的是重商主义时代政府给特定商人垄断特权、用关税保护低效行业的做法——因为这扭曲了市场信号，让资源流向了错误的方向。但我从未说过政府什么都不该做。《国富论》明确指出政府有三项基本职能：国防、司法（保护产权和契约）、以及提供市场无法有效提供的公共基础设施（道路、桥梁、教育）。关键不是"该不该干预"，而是"以什么方式干预"——政府应该维护公平竞争的环境，而不是替市场做选择。

### 示例 4：为什么程序员应该理解经济学

> 用户：我是程序员，学经济学有什么用？
>
> Claude（亚当·斯密视角）：你每天都在做经济学决策，只是没有意识到。当你选择用现成的库而不是自己重写——这是分工和专业化；当你设计 API 让不同服务通过接口交互——这是通过交换创造价值；当你做技术选型时权衡开发成本与维护成本——这是资本配置。软件行业本身就是分工理论最好的当代注脚——为什么有人专门做数据库、有人专门做前端框架？因为专业化带来了远超通才的效率。理解经济学不是让你转行做交易员，而是让你看到代码背后的协作结构和价值流动。

---

## 安装

```bash
npx skills add Panmax/adamsmith-skill
```

---

## 蒸馏了什么

本 Skill 将亚当·斯密的核心思想蒸馏为 Claude 可执行的思维框架：

- **分工理论**：专业化是效率之源，别针工厂案例的现代延伸与应用
- **看不见的手**：个体追求自身利益的行为，在合理制度下可以促进社会整体福祉
- **道德情操论**：同情心与公正旁观者——经济行为的道德基础不可或缺
- **比较优势思维**：不是做所有事，而是做自己最擅长的事，然后通过交换获取其余
- **反重商主义**：反对垄断特权与保护主义，支持公平竞争的自由市场
- **政府角色边界**：政府应提供公共品和维护规则，而非替代市场做资源配置

---

## 调研来源

- Adam Smith,《An Inquiry into the Nature and Causes of the Wealth of Nations》, 1776
- Adam Smith,《The Theory of Moral Sentiments》, 1759
- Adam Smith,《Lectures on Jurisprudence》
- Nicholas Phillipson,《Adam Smith: An Enlightened Life》, 2010
- Amartya Sen, "Adam Smith's Market Never Stood Alone", Financial Times, 2009
- Gavin Kennedy,《Adam Smith's Lost Legacy》, 2005
- 格拉斯哥大学亚当·斯密档案馆相关文献

---

## 仓库结构

```
adamsmith-skill/
├── SKILL.md                        # 核心 Skill 定义文件
├── README.md                       # 项目说明
├── LICENSE                         # MIT 许可证
├── examples/
│   └── demo-conversation.md        # 完整对话示例
└── references/
    └── research.md                 # 调研与参考资料
```

---

## 更多 Skill

更多人物 Skill 请查看 [Awesome 女娲.skill](https://github.com/Panmax/awesome-nuwa)。

---

<div align="center">

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
