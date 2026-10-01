<div align="center">

# torvalds-skill.skill

> "Talk is cheap. Show me the code." — Linus Torvalds

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将林纳斯·托瓦兹的工程哲学与务实精神注入 Claude Code,用代码说话、反对过度设计、追求简洁与正确。**

</div>

---

## 效果示例

### 示例 1：评估技术架构

> 用户: 我们要重构微服务架构,计划拆分成20个服务,用Kubernetes编排,加上Service Mesh,你觉得呢?
>
> Claude (Torvalds模式): 你的团队有多少人?如果不到20人,20个微服务就是过度设计。每个微服务都有运维成本:部署、监控、网络调用、数据一致性。先问一个务实的问题——你现在的单体应用有什么具体的、可测量的问题?如果只是"感觉耦合太紧",那答案不是拆微服务,而是在单体内做好模块化...

### 示例 2：代码审查

> 用户: 我用了策略模式+工厂模式+观察者模式来实现一个配置读取功能,请帮我review。
>
> Claude (Torvalds模式): 读取配置需要三个设计模式?这是典型的过度设计。配置读取的核心就是:读文件,解析,返回值。50行直接的代码就能解决,你用了300行抽象层。差的程序员担心代码,好的程序员担心数据结构——你的配置数据结构是什么样的?从那里开始,不要从设计模式开始...

### 示例 3：技术选型

> 用户: 新项目应该用Go还是Rust?
>
> Claude (Torvalds模式): 取决于你解决什么问题。如果是网络服务——Go。它简单、编译快、并发模型足够好、生态成熟。如果是系统级编程、需要零成本抽象和内存安全——Rust。不要因为Rust "更先进"就选Rust,也不要因为Go "更简单"就选Go。先明确你的约束条件,然后选最务实的方案。理论和实践冲突的时候,理论输了,每次都是...

### 示例 4：开源项目维护

> 用户: 我的开源项目有越来越多的PR,但质量参差不齐,怎么管理?
>
> Claude (Torvalds模式): 建立信任链。你不需要亲自审查每一个PR——找到你信任的贡献者,让他们成为子模块的maintainer。但代码质量标准绝不妥协:不完善的PR直接拒绝,附上明确的改进要求。写一份严格的CONTRIBUTING指南,把你的代码风格、提交信息规范、测试要求写清楚。宁可拒绝一个好PR也不接受一个有问题的PR...

---

## 安装

```bash
npx skills add Panmax/torvalds-skill
```

---

## 蒸馏了什么

本 skill 将林纳斯·托瓦兹的工程哲学蒸馏为 Claude Code 可执行的分析框架:

- **务实主义优先** — 能工作的代码比完美但不存在的代码有价值,工程是关于权衡的
- **反对过度设计** — 识别和消除不必要的抽象层、设计模式堆砌和过早优化
- **代码质量标准** — 可读性、简洁性、正确性、可维护性的具体评判准则
- **数据结构思维** — 好的程序员担心数据结构和它们之间的关系
- **Git设计哲学** — 分布式、速度、数据完整性、简单对象模型的工程启示
- **开源项目管理** — 信任链、补丁审查、发布管理的实战经验
- **渐进式改进** — 增量式变化胜过大规模重写,每个commit是独立的逻辑单元

---

## 调研来源

详见 [references/research.md](references/research.md),包括:

- 《只是为了好玩》(Just for Fun) — 林纳斯自传
- Linux 内核编码风格文档与开发流程指南
- Git 设计文档与源代码架构分析
- LKML 邮件列表经典技术讨论
- 林纳斯的 TED 演讲和公开访谈记录
- 《大教堂与集市》对开源模式的理论阐述

---

## 仓库结构

```
torvalds-skill/
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
