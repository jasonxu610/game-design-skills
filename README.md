# 🎮 Game Design Skills

从游戏设计书籍中提取的 AI 可调用知识技能，兼容 OpenClaw / Claude Code Skill 系统。

## 📚 Skills 列表

### 1. game-design-100-principles
**《游戏设计的100个原理》** (Wendy Despain)
- 22 个专项技能 + 1 个主技能文件
- 覆盖：核心设计、机制平衡、角色系统、关卡体验、交互设计、玩家心理、测试管理
- 来源：[pdf2skills](https://github.com/kitchen-engineer42/pdf2skills) + 人工整合

### 2. game-design-150-tips
**《爆款方法论：游戏设计的3大核心与150个技巧》** (曾宣凯)
- 游戏设计方法论框架 + 150 个实战技巧
- 覆盖：玩法设计、市场立项、用户需求、产品优化
- 来源：pdf2skills (Bedrock Claude Opus 4.6)

### 3. metaverse-marketing
**《元宇宙营销：认知、方法与实践》** (栗建)
- 4A 方法论：Avatar / Augmentation / Always-on / Alliance
- 覆盖：元宇宙基础、营销重构、VR/AR 内容设计、NFT 设计
- 来源：pdf2skills (Bedrock Claude Opus 4.6)

## 🚀 使用方法

### OpenClaw
```bash
# 复制到 skills 目录
cp -r game-design-100-principles ~/.openclaw/workspace/skills/
cp -r game-design-150-tips ~/.openclaw/workspace/skills/
cp -r metaverse-marketing ~/.openclaw/workspace/skills/
```

### Claude Code
```bash
cp -r game-design-100-principles ~/.claude/skills/
```

## 📖 Skill 结构

每个 Skill 包含：
- `SKILL.md` — 主技能文件（框架概述 + 工作流程 + 速查表）
- `index.md` — 导航索引
- `references/` — 各章节详细参考文档

## 🔧 生成工具

- [pdf2skills](https://github.com/kitchen-engineer42/pdf2skills) — PDF → Skill 转换流水线
- LLM: AWS Bedrock Claude Opus 4.6
- PDF 文本提取: PyPDF2

## 📄 License

Skills 内容版权归原书作者所有，仅供个人学习使用。
