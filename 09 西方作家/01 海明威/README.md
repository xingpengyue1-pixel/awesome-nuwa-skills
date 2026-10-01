<div align="center">

# hemingway.skill

> "所有你必须做的就是写一句真实的句子。写你所知道的最真实的句子。" —— 欧内斯特·海明威

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
**将海明威的冰山理论、极简短句与硬汉式克制蒸馏为 Claude Code 可调用的写作视角技能。**

</div>

---

## 效果示例

### 1. 短句改写

> 用户: 帮我用海明威风格重写这段话——"那个下午天气非常好，阳光灿烂，我们在湖边享受了一顿非常丰盛的午餐，大家都非常开心。"
>
> Claude: 下午晴朗。湖水很蓝。我们吃了午饭。酒是凉的。没有人说太多话。那是好的一天。

### 2. 冰山理论分析

> 用户: 用冰山理论帮我分析一下这个短篇的叙事策略。
>
> Claude: 水面上的八分之一——他走进酒吧，要了一杯啤酒，看了看窗外。水面下的七分之八——他刚从妻子的葬礼上回来，他已经三天没有和任何人说过话，他点啤酒是因为她以前总点啤酒。海明威教我们：不要写悲伤，写那个让人悲伤的动作。

### 3. 勇气主题写作

> 用户: 以"勇气"为主题写一个海明威式的微型故事。
>
> Claude: 老头每天早上去海边。他的船很旧。网破了两个洞。他补好了。天没亮他就出海了。没有鱼。第二天也没有。第八十五天他又出去了。因为那是他会做的事。

### 4. 对话剥离

> 用户: 帮我把这段对话改得更海明威——删掉所有不必要的修饰。
>
> Claude: "你要走了？" / "是。" / "什么时候？" / "今晚。" / "好。" / 她没有再说什么。他拿起帽子。门关上了。街上很安静。

---

## 安装

```bash
npx skills add Panmax/hemingway-skill
```

---

## 蒸馏了什么

本技能从海明威的写作哲学和创作实践中提取了以下核心要素：

- **冰山理论** — 只写水面上的八分之一，让读者自己感受水面下的七分之八
- **极简短句** — 主语、动词、宾语，砍掉一切形容词和副词的冗余
- **硬汉式克制** — 不写情感本身，写引发情感的具体动作和事物
- **真实的句子** — 每一句话都必须是你所知道的最真实的句子
- **具体细节** — 用精确的名词和动词代替模糊的描述
- **对话的留白** — 对话不解释，对话制造张力

核心参考作品：《老人与海》《流动的盛宴》《太阳照常升起》《永别了，武器》《乞力马扎罗的雪》

---

## 调研来源

- 《流动的盛宴》中海明威对写作方法的自述
- 《午后之死》中冰山理论的原始阐述
- George Plimpton 对海明威的巴黎评论访谈 (1958)
- 海明威给菲茨杰拉德、麦克斯韦·帕金斯等人的书信
- Carlos Baker《海明威传》中对其写作习惯的记录

---

## 仓库结构

```
hemingway-skill/
├── SKILL.md                        # 技能主文件（Claude Code 读取）
├── README.md                       # 项目说明
├── LICENSE                         # MIT 许可证
├── examples/
│   └── demo-conversation.md        # 完整示例对话
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
