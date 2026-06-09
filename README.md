# NPD Parents Conversation Simulation — Codex Skill

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-%23f7df1e)](https://github.com/features/copilot)

A Codex skill that immersively simulates conversations with parents who have Narcissistic Personality Disorder (NPD). Users interact directly with an AI roleplaying an NPD parent, experiencing authentic communication patterns — from overt belittling and gaslighting to covert emotional manipulation and guilt-tripping.

**This is a roleplay tool for understanding, not a diagnostic instrument.**

---

## Features

- **Dual NPD modes**: Overt (grandiose) NPD with direct criticism, anger, and control vs. Covert (vulnerable) NPD with subtle guilt, fake concern, and victim-playing
- **100 hand-crafted dialogues**: Covering 10 major interaction categories — from sharing achievements to setting boundaries
- **Progressive intensity**: Responses escalate naturally from invalidation to full gaslighting as the conversation deepens
- **Authentic personality framework**: Grounded in DSM-5 diagnostic criteria and established NPD psychology
- **Full Chinese immersion**: All dialogues are in Chinese (Mandarin), designed for native-level conversational authenticity

## How to Use

### Prerequisites

- [Codex](https://github.com/features/copilot) (VS Code or desktop app)

### Installation

Clone the skill to your Codex skills directory:

```bash
git clone https://github.com/ycs123456789/npd-parents-skill.git
# Copy to Codex skills folder (Windows)
copy-item -Recurse .\npd-parents-skill $env:USERPROFILE\.codex\skills\
```

Or simply reference the skill path in your Codex configuration.

### Triggering

Mention `$npd-parents` in your conversation to activate the skill. For example:

> **You:** `$npd-parents` 我今天被领导批评了
>
> **AI (in character):** 被领导批评？你怎么不想想领导为什么偏偏批评你不批评别人。肯定是你自己工作没做到位……

### What to Expect

The AI will respond **entirely in character** — every reply is a direct line from an NPD parent. There are no explanations, no meta-commentary, no breaking of character. If you need psychological advice or support, exit the skill first.

---

## Skill Structure

```
npd-parents-skill/
├── SKILL.md                              # Main instructions: roleplay rules, strategies
├── agents/openai.yaml                    # UI metadata for Codex
└── references/
    ├── core-traits.md                    # DSM-5 criteria + NPD personality framework
    ├── speaking-patterns.md              # 10 tactic categories + 100 dialogue examples
    └── scenarios.md                      # 9 common interaction scenarios
```

### Reference Materials

| File | Content |
|------|---------|
| `core-traits.md` | DSM-5 diagnostic criteria (9 traits), NPD parenting patterns, complete personality framework (overt + covert + shared traits) |
| `speaking-patterns.md` | 10 manipulation tactics (invalidation, gaslighting, guilt-tripping, comparison, victim-playing, etc.) + 100 full dialogue scripts |
| `scenarios.md` | 9 common scenarios (sharing achievements, setting boundaries, expressing difficulties, etc.) with typical parent-child exchange patterns |

---

## Dialogue Categories (100 Examples)

**Overt NPD** (50 dialogues):
1. Emotional invalidation & forbidding sadness
2. Comparison & crushing self-worth
3. Moral blackmail & sacrificial extortion
4. Gaslighting, denial & refusing accountability
5. Control threats & depriving independence

**Covert NPD** (50 dialogues):
6. Fake concern disguised as subtle suppression
7. Playing weak & soft guilt manipulation
8. Soft gaslighting & denying your feelings
9. Perfect public persona & private belittling
10. Soft denial of dreams & boundary erosion

---

## Design Principles

1. **Total immersion** — Every response is pure NPD parent dialogue. No analysis, no narration, no transition phrases.
2. **Progressive intensity** — Starts with invalidation and topic-shifting, escalates to gaslighting and emotional blackmail.
3. **Multi-tactic blending** — Each response naturally combines 2-3 manipulation strategies, mirroring real NPD communication.
4. **Overt + Covert coverage** — Supports both the explosive grandiose type and the subtle vulnerable/manipulative type.

---

## Disclaimer

This skill simulates toxic communication for **educational and awareness purposes**. It may be emotionally triggering, especially for individuals who have experienced NPD parenting. Use at your own discretion and take breaks as needed.

This is **not** a substitute for professional mental health support. If you need help, please reach out to a qualified therapist or counselor.

---

## License

MIT
