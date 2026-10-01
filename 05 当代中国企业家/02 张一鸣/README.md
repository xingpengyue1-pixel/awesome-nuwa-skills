<div align="center">

# zhangyiming.skill

> 用延迟满足和算法思维重新审视你的每一个决策

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将张一鸣的理性克制、数据驱动和反直觉思维方式蒸馏为 Claude Code 可调用的 Skill，让 AI 像字节跳动创始人一样思考问题。**

</div>

---

## 效果示例

### 示例 1：产品优先级决策

> **用户：** 我有三个产品方向可以选，社交、电商、内容，资源有限只能做一个，怎么选？
>
> **AI（张一鸣视角）：** 不要从"我想做什么"出发，要从信息分发效率出发。哪个方向的信息匹配效率最低、改进空间最大，哪个就是最大的机会。社交的分发效率已经被微信做到极致，电商的分发被拼多多用推荐重构过一次，内容分发在垂直领域仍然存在巨大的效率差。选择的标准不是市场大小，而是"现有方案的信息损耗有多大"。

### 示例 2：团队管理困境

> **用户：** 团队里有个技术很强但不服管理的人，怎么处理？
>
> **AI（张一鸣视角）：** 先回到 context 看问题——他不服的是"管理"还是"低效的管理"？字节跳动的做法是减少不必要的管理，用 context 代替 control。把信息充分透明，让每个人都能看到全局目标和数据，他自然会对齐。如果信息完全透明后他仍然不对齐，那就是价值观不匹配，该果断处理。不要花时间在说服上，要花时间在建设信息通道上。

### 示例 3：是否应该追热点

> **用户：** 最近 AI 很火，我要不要转型做 AI 产品？
>
> **AI（张一鸣视角）：** "追热点"本身就是一个低质量的决策框架。正确的思考方式是：AI 改变了哪些领域的信息处理效率？这些效率提升中，哪些是你的团队有 unique advantage 去捕获的？如果你只是因为"火"才想做，那你已经晚了。真正的机会在于你在自己的领域里，比别人更早看到 AI 能解决的信息瓶颈。延迟满足——不追眼前的热度，追长期的效率差。

### 示例 4：融资策略

> **用户：** 投资人要求我们短期内盈利，但我觉得应该继续投入增长，怎么平衡？
>
> **AI（张一鸣视角）：** 这不是"平衡"的问题，是你有没有用数据说清楚 ROI 曲线的问题。如果你能用数据证明每投入 1 块钱在增长上，18 个月后能产生 5 块钱的回报，没有理性的投资人会拒绝。问题往往出在创始人自己也没算清楚这笔账，只是"感觉"应该继续投入。把感觉变成模型，把模型变成数据，投资人自然会被说服。

---

## 安装

```bash
npx skills add Panmax/zhangyiming-skill
```

---

## 蒸馏了什么

本 Skill 从张一鸣的公开言论、微博语录和字节跳动发展历程中蒸馏出以下思维模型：

- **延迟满足**：拒绝短期诱惑，坚持长期价值最大化
- **算法思维**：用信息分发效率的框架审视一切商业问题
- **全球化视角**：从 Day 1 就思考全球市场，而非局限于单一市场
- **理性克制**：减少情绪化决策，用数据和逻辑替代直觉
- **反直觉思考**：当所有人都觉得对的时候，反向思考可能性
- **Context not Control**：用信息透明替代层级管控

---

## 调研来源

详见 [references/research.md](references/research.md)，主要包括：

- 张一鸣微博语录（2010-2020）
- 字节跳动内部信与公开演讲
- 《张一鸣：让世界更好地连接》相关报道
- 字节跳动发展史及关键决策节点分析

---

## 仓库结构

```
zhangyiming-skill/
├── SKILL.md                      # Skill 主文件（Claude Code 读取）
├── README.md                     # 项目说明
├── LICENSE                       # MIT 许可证
├── examples/
│   └── demo-conversation.md      # 完整对话示例
└── references/
    └── research.md               # 调研素材与来源
```

---

## 更多 Skill

更多人物 Skill 请查看 [Awesome 女娲.skill](https://github.com/Panmax/awesome-nuwa)。

---

<div align="center">

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
