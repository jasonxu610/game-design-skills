# 🎮 Game Design Skills

AI-callable knowledge skills extracted from classic game design books. Compatible with [OpenClaw](https://github.com/openclaw/openclaw) / Claude Code Skill systems.

> Turn books into AI "brain modules" — when you ask AI "help me design a boss fight", it can directly invoke the methodologies in these Skills.

**[中文版 README](./README.md)**

---

## 📚 Skills List

### 1. `game-design-100-principles`
**"100 Principles of Game Design"** — Wendy Despain

| Item | Details |
|---|---|
| Files | 35 (22 specialized + main file + index) |
| Coverage | Core design, mechanic balancing, character systems, level experience, interaction design, player psychology, testing management |

Great for **beginners** and **design principle quick reference**.

---

### 2. `game-design-150-tips`
**"Hit Methodology: 3 Cores & 150 Tips of Game Design"** — Zeng Xuankai

| Item | Details |
|---|---|
| Files | 26 (main + index + 24 chapter references) |
| Structure | Vol.1: Gameplay Design (77 tips) / Vol.2: Market & Production (18 tips) / Vol.3: Player Tuning (55 tips) |
| Coverage | Addiction mechanics, combat interaction, random design, innovation methodology, production modes, user research, PVE/PVP, social systems |

Comprehensive methodology from **gameplay design to live ops**, with 150 actionable tips.

---

### 3. `game-design-236-tips`
**"236 Tips for Game Design: Game Mechanics, Level Design and Camera Tricks"** — Koji Ohno

| Item | Details |
|---|---|
| Files | 8 (main + index + 5 module references) |
| Five Modules | Player Character / Enemy Character / Level Design / Collision Detection / Camera Control |
| Case Studies | God of War, Bayonetta, Zelda, Devil May Cry, Dark Souls, etc. |

Built for **3D action game developers**, diving deep into core technical design.

---

### 4. `metaverse-marketing`
**"Metaverse Marketing: Cognition, Methods and Practice"** — Li Jian

| Item | Details |
|---|---|
| Files | 12 (main + index + 10 chapter references) |
| Core Framework | **4A Model**: Avatar / Augmentation / Always-on / Alliance |
| Coverage | Metaverse basics, people-goods-场 reconstruction, VR/AR content design, brand digital avatars, NFT design |

For **game marketing and brand operations**, especially virtual world brand strategies.

---

## 🚀 Usage

### OpenClaw
```bash
git clone https://github.com/jasonxu610/game-design-skills.git

cp -r game-design-skills/game-design-100-principles ~/.openclaw/workspace/skills/
cp -r game-design-skills/game-design-150-tips ~/.openclaw/workspace/skills/
cp -r game-design-skills/game-design-236-tips ~/.openclaw/workspace/skills/
cp -r game-design-skills/metaverse-marketing ~/.openclaw/workspace/skills/
```

### Claude Code
```bash
cp -r game-design-skills/game-design-100-principles ~/.claude/skills/
```

### Other AI Coding Assistants
Skills are structured Markdown files, usable as context for any AI tool:
- Place in project root for auto-loading
- Use as part of system prompts
- Feed into RAG knowledge bases

---

## 📁 Skill File Structure

Each Skill follows a unified three-layer structure:

```
skill-name/
├── SKILL.md          # Main skill file (framework + work modes + quick reference)
├── index.md          # Navigation index
└── references/       # Detailed reference documents (one per topic/chapter)
```

---

## 🔧 Generation Tools

| Tool | Purpose |
|---|---|
| [pdf2skills](https://github.com/kitchen-engineer42/pdf2skills) | PDF → Skill conversion pipeline |
| AWS Bedrock Claude Opus 4.6 | LLM knowledge extraction |
| PyPDF2 | PDF text extraction |
| pdftoppm | Scanned PDF page-to-image conversion |

---

## 📄 License

Skill content copyrights belong to the original book authors. For personal learning and research use only.

---

## ⭐ Star & Contribute

Found this useful? Star ⭐ and Fork!

Have a game design book you want converted to a Skill? Open an Issue or PR.
