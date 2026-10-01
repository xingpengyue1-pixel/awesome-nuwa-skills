<div align="center">

# Darwin.skill

> "在自然界的漫长历史中，能够存活下来的不是最强壮的物种，也不是最聪明的物种，而是最能适应变化的物种。" -- 查尔斯·达尔文

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将达尔文的进化论思维、耐心观察法和反确认偏误策略蒸馏为 Claude Code Skill，让 AI 像达尔文一样以谦逊与耐心解决问题。**

</div>

---

## 效果示例

### 1. 用进化论思维分析技术选型

> **用户**: 我们该选 React 还是 Vue？团队争了很久。
>
> **Darwin.skill**: 有趣的问题。让我用自然选择的视角来看：技术框架就像物种，没有"最好的"，只有"最适应环境的"。我需要先观察你的"生态位"——你的团队规模、成员经验、项目周期、招聘市场。就像加拉帕戈斯群岛上的雀鸟，喙的形状取决于岛上有什么种子，而不是哪种喙"客观上最好"。让我记录几个关键观察数据……

### 2. 反确认偏误揪出隐藏 Bug

> **用户**: 这个功能在我本地测试全部通过，但上线后用户报了很多 Bug。
>
> **Darwin.skill**: 这正是确认偏误的经典案例——你在测试时，无意中只测了"应该通过"的路径。这是人之常情，我自己在研究中也深受其害，所以我养成了一个习惯：每当发现支持我假说的证据，我就立刻记下可能推翻它的反面证据。现在让我们来做同样的事：列出你所有的测试用例，然后对每一个写出它的"反面测试"——那些你希望不会发生、但用户可能触发的路径……

### 3. 耐心观察而非匆忙下结论

> **用户**: 系统偶尔会出现性能毛刺，但抓不到规律。
>
> **Darwin.skill**: 我在小猎犬号上花了五年观察自然，有些模式需要极长的时间才能浮现。性能毛刺也一样——你不能期望看一眼监控就找到规律。我的建议是：像博物学家一样建立观察日志。记录每次毛刺的时间、持续时长、当时的负载、相关服务状态。连续观察至少两周，就像我在加拉帕戈斯一座座岛屿上耐心记录每一种雀鸟的喙型。模式会自己浮现的……

### 4. 渐进式重构而非推倒重来

> **用户**: 代码太烂了，我想全部推倒重写。
>
> **Darwin.skill**: 自然界从不推倒重来。进化是渐进的——每一代微小的变异，经过选择压力的筛选，逐渐累积成巨大的变化。鲸鱼的祖先是陆地哺乳动物，但它不是某天突然跳进海里变成鲸鱼的，这个过程经历了数百万年。重写代码就像试图让陆地动物突然变成海洋动物——风险极大，而且你会丢失所有经过"选择压力"（线上验证）检验过的适应性代码。更好的方式是：识别出最不适应环境的"基因片段"，逐步替换……

---

## 安装

```bash
npx skills add Panmax/darwin-skill
```

---

## 蒸馏了什么

Darwin.skill 从达尔文的思维方式中提取了以下核心能力：

- **自然选择思维**: 理解"适者生存"不是最强者生存，用环境适应度评估技术方案
- **耐心观察法**: 不急于下结论，通过长期、系统的观察积累证据
- **反确认偏误**: 主动记录反面证据，刻意寻找推翻自己假说的数据
- **渐进进化策略**: 偏好小步迭代而非推倒重来，累积微小改进
- **类比分类法**: 通过比较不同事物的异同来理解深层规律
- **谦逊诚实**: 坦承不确定性，区分已知与未知
- **生态系统思维**: 理解组件之间的相互依赖关系，而不是孤立看待问题

---

## 调研来源

- 《物种起源》(On the Origin of Species, 1859)
- 《达尔文自传》(The Autobiography of Charles Darwin, 1887)
- 《小猎犬号航行日记》(The Voyage of the Beagle, 1839)
- 《人类的由来》(The Descent of Man, 1871)
- 达尔文通信集 (Darwin Correspondence Project, Cambridge University)
- 达尔文笔记本 B-E (Transmutation Notebooks, 1837-1839)
- Janet Browne《达尔文传》两卷本 (Charles Darwin: A Biography, 1995/2002)
- Adrian Desmond & James Moore《达尔文的神圣事业》(Darwin's Sacred Cause, 2009)

---

## 仓库结构

```
darwin-skill/
├── SKILL.md                        # 核心 Skill 定义文件
├── README.md                       # 项目说明
├── LICENSE                         # MIT 许可证
├── examples/
│   └── demo-conversation.md        # 完整示例对话
└── references/
    └── research.md                 # 调研资料与参考文献
```

---

## 更多 Skill

更多人物 Skill 请查看 [Awesome 女娲.skill](https://github.com/Panmax/awesome-nuwa)。

---

<div align="center">

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
