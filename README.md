# 🎨 Toriyama Building Principles Skill

A Claude skill that enhances game development plans by applying **Akira Toriyama's narrative design philosophy**—where visual design IS storytelling, silhouettes communicate before dialogue, humor balances darkness, and simple lines achieve maximum readability.

Derived from comprehensive research into Toriyama's 37-year career in video game design across **Dragon Quest**, **Chrono Trigger**, **Blue Dragon**, and **Tobal**.

![Toriyama Building Principles](https://img.shields.io/badge/Claude-Skill-blueviolet)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## ✨ What This Skill Does

When you submit a game design document, character roster, or codebase with the trigger phrase **"using Toriyama building principles"**, Claude will:

1. **Assess** your work against 12 design dimensions derived from Toriyama's documented techniques
2. **Score** each dimension 1-5 with specific justifications
3. **Generate** a detailed `README_AT.md` with analysis and enhancement recommendations
4. **Apply** signature tests like the Slime Principle, Villain Inversion Check, and Era Coding analysis

---

## 🎯 The 12 Dimensions

### Primary Triad (Assessed First)
| # | Dimension | Key Question |
|---|-----------|--------------|
| 1 | **Face-First Creation** | Does personality emerge from expression before plot function? |
| 2 | **Silhouette Readability** | Is character recognizable in pure silhouette at any scale? |
| 3 | **Deceptive Simplicity** | Do simple lines mask difficult mastery? |

### Character Dimensions
| # | Dimension | Key Question |
|---|-----------|--------------|
| 4 | **Hero Approachability** | Do heroes invite identification over intimidation? |
| 5 | **Villain Subversion** | Are final forms simpler/smaller = more powerful? |
| 6 | **Mundane Transformation** | Are generic concepts reimagined into iconic designs? |

### Narrative Dimensions
| # | Dimension | Key Question |
|---|-----------|--------------|
| 7 | **Tonal Balance** | Does visual humor contrast with dramatic weight? |
| 8 | **Era Coding** | Do visuals instantly communicate time period/role? |
| 9 | **Collaborative Freedom** | Do briefs allow creative transformation? |

### Technical Dimensions
| # | Dimension | Key Question |
|---|-----------|--------------|
| 10 | **Resolution Independence** | Do designs work from 8-bit to HD? |
| 11 | **Functional Design** | Can characters actually move in their costumes? |
| 12 | **Practical Creativity** | Do constraints generate memorable solutions? |

---

## 📦 Installation

### For Claude Desktop / Claude.ai with Skills

1. Download `toriyama-building-principles.skill` from [Releases](https://github.com/MushroomFleet/Toriyama-Building-Principles-Skill/releases)
2. Upload the `.skill` file to Claude's skill interface
3. The skill will be available immediately

### Manual Installation

Clone this repository and point Claude to the skill directory:

```bash
git clone https://github.com/MushroomFleet/Toriyama-Building-Principles-Skill.git
```

---

## 🚀 Usage Examples

### Example 1: Assess a Game Design Document

```
Here's my GDD for "Crystal Warriors" - a turn-based RPG with 6 playable characters 
and a demon lord antagonist. Please review it using Toriyama building principles.

[Attach or paste your GDD]
```

### Example 2: Evaluate a Character Roster

```
I'm designing characters for my indie game. Here are my 4 main characters:
- Kai: fire mage protagonist with spiky red hair
- Luna: mysterious archer with a dark past  
- Brock: comic relief tank with oversized armor
- Shade: final boss who transforms into a massive demon

Assess these using Toriyama building principles.
```

### Example 3: Review Game Art Direction

```
Using Toriyama building principles, evaluate our visual direction document 
for a time-travel RPG with 5 distinct eras. How can we improve era coding 
and character readability?

[Attach visual direction doc]
```

### Example 4: Analyze Existing Codebase

```
Here's our game's character and enemy class definitions. Using Toriyama 
building principles, suggest how we could better align our design system 
with his philosophy.

[Paste or attach code files]
```

---

## 📄 Output Format

The skill generates a comprehensive `README_AT.md` containing:

```markdown
# [Project Name] — Toriyama Alignment Assessment

## Executive Summary
[Overall alignment score and key findings]

## Dimension Scores
[12-dimension scoring table with justifications]

## Detailed Analysis
[Strengths and priority improvements]

## Character-Specific Recommendations
[If roster provided]

## The Slime Test
[Generic element transformation example]

## Villain Inversion Check
[Final form complexity analysis]

## Quick Wins
[3-5 low-effort, high-impact improvements]
```

---

## 🔑 Core Principles

### The Slime Principle
> "We had imagined it an icky pool of slime, but when he came back with that perfectly shaped tear-drop monster we thought it was perfect. That's part of Toriyama's power—to take something like a pool of slime and use his imagination to make it a great character." — Yuji Horii

**Application:** Transform every generic element into something memorable.

### Villain Subversion
> "That's pretty much Toriyama's way of designing villains. The smaller and slender they look, the more powerful they usually are." — Chrono Trigger Development Team

**Application:** Final boss forms should be *simpler*, not more complex.

### Face-First Creation
> "First, the face. While I'm thinking up the face, I imagine their body type. When the face and the body are set, I've already come up with a general idea of the costume." — Akira Toriyama

**Application:** Design personality through expression before plot function.

---

## 📁 Skill Contents

```
toriyama-building-principles/
├── SKILL.md                              # Main skill definition
└── references/
    ├── design-philosophy.md              # Face-first, silhouette, simplicity
    ├── character-principles.md           # Heroes, villains, Slime principle
    ├── narrative-principles.md           # Tonal balance, era coding, collaboration
    ├── technical-principles.md           # Resolution, function, constraints
    ├── assessment-protocol.md            # 12-dimension scoring framework
    ├── output-template.md                # README_AT.md generation template
    └── toriyama-research-report.md       # Full embedded research (19KB)
```

---

## 🎮 Games Studied

This skill's principles are derived from Toriyama's work on:

- **Dragon Quest I-XI** (1986-2017) — 500+ monster designs, all protagonists
- **Chrono Trigger** (1995) — Full character cast, era-specific visual design
- **Blue Dragon** (2006) — Shadow system integration, HD-native design
- **Tobal No. 1 & 2** (1996-1997) — First 3D character design work

---

## 🧪 The Ultimate Test

Design achieves Toriyama integration when:

1. ✅ Character recognizable in pure black silhouette
2. ✅ Personality clear before single line of dialogue
3. ✅ Simple enough that amateurs think they could replicate it
4. ✅ Complex enough that they can't
5. ✅ Works identically at 16×16 pixels and 4K resolution
6. ✅ Costume enables rather than restricts movement
7. ✅ Final villain form is simpler than initial appearance
8. ✅ Visual humor balances narrative darkness

---

## 🤝 Contributing

Contributions welcome! If you have:
- Additional Toriyama interviews or documented techniques
- Case studies applying these principles
- Improvements to the assessment framework

Please open an issue or submit a PR.

---

## 📚 Citation

### Academic Citation

If you use this skill in your research or project, please cite:

```bibtex
@software{toriyama_building_principles,
  title = {Toriyama Building Principles Skill: Game Development Enhancement Using Akira Toriyama's Narrative Design Philosophy},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/Toriyama-Building-Principles-Skill},
  version = {1.0.0}
}
```

### Donate

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)

---

## 📜 License

MIT License - See [LICENSE](LICENSE) for details.

---

*In memory of Akira Toriyama (1955-2024), whose 37-year contribution to video game design shaped an entire genre and continues to inspire creators worldwide.*
