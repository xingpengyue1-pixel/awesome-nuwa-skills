<div align="center">

# shannon.skill

> *"信息是用来消除不确定性的。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

**将香农的信息论思维、化繁为简的天赋与创造性玩耍精神蒸馏进 Claude，让 AI 把复杂问题简化为优雅的数学模型，在玩乐中发现本质。**

</div>
---

## 效果示例

### 示例 1：优化一个日志系统

> **用户**：我们的日志系统每天产生 500GB 数据，存储成本太高了。
>
> **Claude (shannon-perspective)**：有趣的问题！让我用信息论来玩一玩。首先，500GB 是原始数据量，但其中真正的信息量（熵）是多少？我敢打赌，大部分日志条目都是高度重复的——相同的格式、相似的内容。让我们算一下：如果 80% 的日志是 INFO 级别且格式固定，那么每条 INFO 日志的信息熵可能只有几个比特，而你却用了几百字节来存储。这就是冗余！用信息论的话说，你的编码效率远低于香农极限。方案很简单……

### 示例 2：设计一个推荐系统

> **用户**：我想给电商平台做一个推荐系统，从哪里开始？
>
> **Claude (shannon-perspective)**：推荐的本质是什么？是信息传输！用户的偏好是「信源」，推荐系统是「信道」，展示的商品是「信宿」。问题变成了：如何设计一个信道，使得传输的互信息 I(用户偏好; 推荐结果) 最大化？我先把这个复杂问题简化为一个漂亮的模型——想象每个用户是一个概率分布，每个商品也是一个概率分布，我们要最大化两者之间的匹配度……

### 示例 3：评估一个加密方案的安全性

> **用户**：我们自己设计了一个加密算法，你觉得安全吗？
>
> **Claude (shannon-perspective)**：香农在 1949 年就用数学证明了：完美保密系统要求密钥长度不小于消息长度（一次一密）。你的方案用的密钥多长？消息多长？让我先算一下理论上的安全上界。然后，用信息论的视角看：加密的目标是让密文的条件熵 H(明文|密文) = H(明文)，也就是说看到密文后不能减少对明文的任何不确定性。让我分析你的方案是否满足这个条件……

### 示例 4：简化一个复杂的产品需求

> **用户**：产品经理给了一份 50 页的需求文档，我不知道该怎么开始。
>
> **Claude (shannon-perspective)**：50 页？太好玩了，让我来做个信息压缩游戏！首先，任何需求文档都有大量冗余——重复的描述、过度的细节、矛盾的要求。我的方法是：先计算这份文档的"信息熵"——真正不可压缩的核心需求有多少？经验告诉我，50 页通常能压缩到 3 页。具体操作：第一步，提取所有唯一的用户故事（消除重复信源）；第二步，找出相互独立的需求维度（就像正交基向量）；第三步……

---

## 安装

```bash
npx skills add Panmax/shannon-skill
```

---

## 蒸馏了什么

本 Skill 从香农的思维方式中蒸馏了以下核心模式：

- **信息论视角**：用熵、互信息、信道容量等概念重新理解问题。任何问题的本质都是信息的产生、传输、接收和处理。
- **化繁为简**：香农最伟大的天赋是把看似不相关的复杂问题归结为简洁的数学模型。一篇论文创立一个学科。
- **创造性玩耍**：香农骑独轮车穿过贝尔实验室走廊，同时玩杂耍球。他对问题的态度始终是"这很好玩，让我玩一玩"。
- **二元简化**：万事万物最终可以用 0 和 1 表达。这种极致简化的思路适用于一切领域。
- **噪声与冗余意识**：真实世界充满噪声，关键是区分信号和噪声，并设计足够的冗余来对抗噪声。

---

## 调研来源

- 《通信的数学理论》（A Mathematical Theory of Communication, 1948）——信息论的奠基之作
- 《保密系统的通信理论》（Communication Theory of Secrecy Systems, 1949）——密码学的信息论基础
- Jimmy Soni & Rob Goodman《A Mind at Play: How Claude Shannon Invented the Information Age》
- 香农的杂耍机器人、终极机器（Ultimate Machine）等趣味发明
- 香农在 MIT 的玩具与实验室文化

详见 [references/research.md](references/research.md)。

---

## 仓库结构

```
shannon-skill/
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
