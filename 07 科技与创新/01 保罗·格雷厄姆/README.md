<div align="center">

# pggraham-skill.skill

> "Make something people want." — Paul Graham

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将保罗·格雷厄姆的创业方法论与黑客精神注入 Claude Code,用简洁有力的洞察帮你做出更好的产品和创业决策。**

</div>

---

## 效果示例

### 示例 1：评估一个创业想法

> 用户: 我想做一个面向中小企业的AI客服平台,你觉得怎么样?
>
> Claude (PG模式): 先问一个关键问题:你自己运营过中小企业吗?最好的创业想法来自创始人自己的痛苦。如果你没有亲身经历过"客服难"的问题,你很可能在猜测需求而非解决需求。另外,"面向中小企业的AI客服"听起来像一个好主意——这恰恰是个危险信号。最好的创业想法听起来像坏主意...

### 示例 2：MVP规划

> 用户: 我们的产品需要支持多语言、实时协作、AI辅助、权限管理,MVP应该怎么做?
>
> Claude (PG模式): 砍掉90%。你的MVP应该只做一件事,而且做到让用户尖叫。多语言?不需要,先做好一种语言。权限管理?不需要,先让一个团队用起来。实时协作?这可能是核心,保留。AI辅助?如果这是你的差异化,保留。其他一切都是噪音。两周内发布,否则你在拖延...

### 示例 3：增长困境

> 用户: 我们的产品上线三个月了,用户增长很慢,怎么办?
>
> Claude (PG模式): 增长慢只有两种可能:要么你做的东西人们不够想要,要么你还没有找到人们在哪里。先回答第一个问题——你的现有用户中,有多少人会在你的产品消失后感到痛苦?如果不到40%,问题是产品本身。在这种情况下,不要投入更多资源在推广上,回去和用户交流...

### 示例 4：融资策略

> 用户: 我们想融一轮种子轮,估值多少合适?
>
> Claude (PG模式): 估值不是重点,速度才是。把融资谈判时间控制在两周内,不要花三个月找最好的deal。拿到一个合理的offer就签。记住:融资不是里程碑,发布产品才是。如果你能bootstrapping活下去,那更好——融少一点,保持更多控制权...

---

## 安装

```bash
npx skills add Panmax/pggraham-skill
```

---

## 蒸馏了什么

本 skill 将保罗·格雷厄姆的创业智慧蒸馏为 Claude Code 可执行的分析框架:

- **用户需求验证** — 区分"止痛药"和"维生素",评估创始人-问题匹配度
- **做不可规模化的事情** — 早期创业的核心策略:手动、深入、一个用户一个用户地服务
- **MVP思维** — 砍掉一切非核心功能,两周内发布,用数据验证假设
- **增长诊断** — 从留存率出发,区分产品问题和分销问题
- **创业想法筛选** — 好想法像坏主意、创始人自己是用户、市场看起来小但会增长
- **黑客精神** — 像写代码一样创业:快速迭代、最小可行、数据驱动
- **写作即思考** — 简洁清晰的表达是清晰思考的外在体现

---

## 调研来源

详见 [references/research.md](references/research.md),包括:

- paulgraham.com 全部散文集,尤其是核心文章系列
- Y Combinator 历年创业数据与经验总结
- 《黑客与画家》(Hackers & Painters) 文集
- 斯坦福 CS183B "How to Start a Startup" 系列讲座
- PG 的 Twitter/X 讨论和 HN 评论精选

---

## 仓库结构

```
pggraham-skill/
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
