# 🎮 Game Design Skills

从游戏设计经典书籍中提取的 AI 可调用知识技能，兼容 [OpenClaw](https://github.com/openclaw/openclaw) / Claude Code Skill 系统。

> 把书变成 AI 的"大脑模块"——当你问 AI "帮我设计一个 Boss 战"，它能直接调用这些 Skill 里的方法论来回答。

---

## 📚 Skills 列表

### 1. `game-design-100-principles`
**《游戏设计的100个原理》** — Wendy Despain

| 项目 | 内容 |
|---|---|
| 文件数 | 35（22 专项 + 主文件 + 索引） |
| 覆盖 | 核心设计、机制平衡、角色系统、关卡体验、交互设计、玩家心理、测试管理 |
| 来源 | [pdf2skills](https://github.com/kitchen-engineer42/pdf2skills) + [OrangeViolin Gist](https://gist.github.com/OrangeViolin/53ad898cdbc8734d8bb5c6a6ddf5cec4) |

适合**新手入门**和**设计原则速查**，100 个原理覆盖游戏设计全流程。

---

### 2. `game-design-150-tips`
**《爆款方法论：游戏设计的3大核心与150个技巧》** — 曾宣凯

| 项目 | 内容 |
|---|---|
| 文件数 | 26（主文件 + 索引 + 24 章节参考） |
| 三卷结构 | 第一卷：玩法设计（77 技巧） / 第二卷：市场立项（18 技巧） / 第三卷：用户调优（55 技巧） |
| 覆盖 | 上瘾机制、战斗交互、随机设计、创新方法论、制作模式、用户研究、PVE/PVP、社交系统 |
| 来源 | pdf2skills（AWS Bedrock Claude Opus 4.6） |

适合**中国市场游戏开发者**，从玩法设计到上线运营的完整方法论，150 个技巧可直接落地。

---

### 3. `game-design-236-tips`
**《游戏设计的236个技巧：游戏机制、关卡设计和镜头窍门》** — [日] 大野功二

| 项目 | 内容 |
|---|---|
| 文件数 | 8（主文件 + 索引 + 5 模块参考 + 1 案例库） |
| 五大模块 | 玩家角色 / 敌人角色 / 关卡设计 / 碰撞检测 / 镜头控制 |
| 经典案例 | 《战神》《猎天使魔女》《塞尔达传说》《鬼泣》《黑暗之魂》等 |
| 来源 | pdf2skills（AWS Bedrock Claude Opus 4.6） |

适合 **3D 动作游戏开发者**，236 个技巧深入 3D 游戏的核心技术设计。

---

### 4. `metaverse-marketing`
**《元宇宙营销：认知、方法与实践》** — 栗建

| 项目 | 内容 |
|---|---|
| 文件数 | 12（主文件 + 索引 + 10 章节参考） |
| 核心方法论 | **4A 框架**：Avatar（数字替身）/ Augmentation（增强赋能）/ Always-on（全时互动）/ Alliance（共创共生） |
| 覆盖 | 元宇宙基础、人货场重构、VR/AR 内容设计、品牌数字替身、NFT 设计 |
| 来源 | pdf2skills（AWS Bedrock Claude Opus 4.6） |

适合**游戏营销和品牌运营**，特别是虚拟世界中的品牌策略。

---

## 🚀 使用方法

### OpenClaw
```bash
# 克隆仓库
git clone https://github.com/jasonxu610/game-design-skills.git

# 复制到 skills 目录
cp -r game-design-skills/game-design-100-principles ~/.openclaw/workspace/skills/
cp -r game-design-skills/game-design-150-tips ~/.openclaw/workspace/skills/
cp -r game-design-skills/game-design-236-tips ~/.openclaw/workspace/skills/
cp -r game-design-skills/metaverse-marketing ~/.openclaw/workspace/skills/
```

### Claude Code
```bash
cp -r game-design-skills/game-design-100-principles ~/.claude/skills/
```

### 其他 AI 编码助手
Skill 本质是结构化 Markdown 文件，可以作为任何 AI 工具的上下文参考：
- 放入项目根目录让 AI 自动读取
- 作为 system prompt 的一部分
- 作为 RAG 知识库的来源

---

## 📁 Skill 文件结构

每个 Skill 遵循统一的三层结构：

```
skill-name/
├── SKILL.md          # 主技能文件
│                     # - 方法论框架概述
│                     # - 工作模式（从零设计/专项优化/诊断修复/设计评审）
│                     # - 核心技巧速查表
├── index.md          # 导航索引
│                     # - 按章节/按主题快速跳转
└── references/       # 详细参考文档
    ├── chapter-01.md # 每个文件覆盖一个主题/章节
    ├── chapter-02.md # 包含：核心概念、技巧详解、实操步骤、案例引用
    └── ...
```

---

## 🔧 生成工具

| 工具 | 用途 |
|---|---|
| [pdf2skills](https://github.com/kitchen-engineer42/pdf2skills) | PDF → Skill 转换流水线 |
| AWS Bedrock Claude Opus 4.6 | LLM 知识提取和结构化 |
| PyPDF2 | PDF 文本提取 |
| pdftoppm | 扫描版 PDF 页面转图片 |

---

## 🎯 适用场景

- **独立游戏开发**：从创意到上线的设计指导
- **3D 动作游戏**：战斗系统、关卡设计、镜头控制
- **游戏策划**：方法论框架和设计检查清单
- **游戏营销**：元宇宙时代的品牌策略
- **AI 辅助设计**：让 AI 具备专业游戏设计知识

---

## 📄 License

Skills 内容版权归原书作者所有，仅供个人学习和研究使用。

- 《游戏设计的100个原理》© Wendy Despain
- 《爆款方法论》© 曾宣凯，四川数字出版传媒 / 掌阅科技
- 《游戏设计的236个技巧》© 大野功二，人民邮电出版社
- 《元宇宙营销》© 栗建

---

## ⭐ Star & Contribute

如果觉得有用，欢迎 Star ⭐ 和 Fork！

有新的游戏设计书想转成 Skill？欢迎提 Issue 或 PR。
