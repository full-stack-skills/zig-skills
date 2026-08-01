<div align="center">

# zig-skills

**Zig language skills — 0.16.0, raylib, SDL3, code review, Tiger Style**

[![GitHub](https://img.shields.io/badge/github-full--stack--skills%2Fzig-skills-green.svg)](https://github.com/full-stack-skills/zig-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) · [Install](#-install) · [Skills](#-skills) · [Repository Layout](#-repository-layout) · [Relationship](#-relationship--migration) · [Official Sources](#-official-sources) · [Supported Agents](#-supported-agents) · [Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**Zig Skills** is a curated collection of Agent Skills for AI coding agents focused on the [Zig programming language](https://ziglang.org) and its ecosystem, part of the [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) ecosystem maintained by [PartMe.AI](https://github.com/partme-ai).

This package includes **15 skills** organized into five layers: **Core Language**, **Project Engineering**, **Java Migration**, **Domain Specialized**, and **Quality & Style**. Each skill is a self-contained package that AI agents load on demand.

## 📦 Install

```bash
npx skills add full-stack-skills/zig-skills
```

Or install specific skills: `npx skills add full-stack-skills/zig-skills --skill <skill-name>`

## 🎯 Skills (15) by Layer

```
┌──────────────────────────────────────────────────────────────┐
│              Layer 1: Core Language                         │
│                                                              │
│  zig-0.16 ──────── Primary skill, full language + std lib    │
│  zig-0.15 ──────── Legacy compatibility (0.15.x)            │
├──────────────────────────────────────────────────────────────┤
│              Layer 2: Project Engineering                    │
│                                                              │
│  zig-project-structure  Project scaffolding + spec checks    │
│  zig-build-system ────── Build.zig, modules, cross-compile   │
├──────────────────────────────────────────────────────────────┤
│              Layer 3: Java Migration                         │
│                                                              │
│  zig-java-migration ───── lossless Java contract migration   │
│  zig-java-migration-testing  full test/assets/diff parity    │
├──────────────────────────────────────────────────────────────┤
│              Layer 4: Domain Specialized                     │
│                                                              │
│  HTTP        zig-http ─────── std.http, WebSocket            │
│  Crypto      zig-crypto ───── std.crypto, hash, AEAD         │
│  Data        zig-json ─────── std.json, std.zon              │
│  Concurrency zig-concurrency  std.Thread, std.atomic         │
│  Testing     zig-testing ──── std.testing, std.debug         │
│  Graphics    zig-raylib ───── raylib 5.5 game dev            │
│  Multimedia  zig-sdl3-bindings  SDL3 multimedia              │
├──────────────────────────────────────────────────────────────┤
│              Layer 5: Quality & Style                        │
│                                                              │
│  zig-code-review  Code review for style & correctness        │
│  zig-tiger-style  TigerStyle coding guidelines               │
└──────────────────────────────────────────────────────────────┘
```

## 📚 Repository Layout

```text
zig-skills/
├── skills/
│   ├── zig-0.15/                   # Previous aggregate skill (0.15.x)
│   ├── zig-0.16/                   # Current primary skill (0.16.0)
│   │   ├── examples/               # Offline quick-start examples
│   │   └── references/             # 40+ std lib & language references
│   ├── zig-build-system/           # Build system specialization
│   ├── zig-code-review/            # Code review skill
│   ├── zig-concurrency/            # Concurrency & threading
│   ├── zig-crypto/                 # Cryptography & security
│   ├── zig-http/                   # HTTP networking
│   ├── zig-json/                   # JSON & ZON data handling
│   ├── zig-project-structure/      # Scaffolding & spec checker
│   ├── zig-java-migration/         # Lossless Java-to-Zig migration
│   ├── zig-java-migration-testing/ # Source tests/assets and differential parity
│   ├── zig-testing/                # Testing & debugging
│   ├── zig-tiger-style/            # Tiger Style guidelines
│   ├── zig-raylib/                 # raylib-zig ecosystem skill
│   └── zig-sdl3-bindings/          # zig-sdl3 ecosystem skill
├── scripts/
│   └── create_zig_016_skill.py     # Generator for zig-0.16 skill
├── README.md
└── README.zh-CN.md
```

## 🧭 Relationship & Migration

`skills/zig-0.16/` is the **preferred main skill** for current Zig work because it:

- Updates guidance to **Zig 0.16.0** (the latest stable release)
- Keeps the same aggregate-skill shape the repository originally used
- Adds strong **official source mapping** (language reference, std index, introduction)
- Maintains a complete offline `references/` set and local `examples/` so the skill works without live fetching

`skills/zig-0.15/` is retained as a **previous-generation aggregate skill** (Zig 0.15.x) and as the source of the local reference corpus. It remains useful for compatibility with older codebases and as supplemental reference material.

The `zig-java-migration` and `zig-java-migration-testing` pair applies the same lossless source-contract and complete differential rules as the Rust migration pair while loading Zig-specific language, build, testing, allocator, target, and review skills. This naming profile is also reserved for future `kotlin-java-*` and `swift-java-*` pairs in their own target-language packages.

The `zig-code-review`, `zig-tiger-style`, `zig-project-structure`, and `zig-build-system` skills cover project quality and engineering; `zig-http`, `zig-crypto`, `zig-json`, `zig-concurrency`, and `zig-testing` are domain-specific standard library deep-dives; while `zig-raylib` and `zig-sdl3-bindings` cover the leading Zig graphics/game development ecosystem libraries.

## 📖 Official Sources

The `zig-0.16` main skill is grounded in these official documentation sources:

- [Zig Language Reference 0.16.0](https://ziglang.org/documentation/0.16.0/)
- [Zig Introduction](https://ziglang.org/documentation/0.16.0/#Introduction)
- [Standard Library Index 0.16.0](https://ziglang.org/documentation/0.16.0/std/)
- [Zig 中文主页](https://ziglang.org/zh-CN/)
- [Build System Guide](https://ziglang.org/learn/build-system/)
- [0.16.0 Release Notes](https://ziglang.org/download/0.16.0/release-notes.html)

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

### Claude Code Installation

**Option 1: npx skills CLI (Recommended)**

```bash
npx skills add full-stack-skills/zig-skills
```

**Option 2: Manual Installation**

```bash
git clone https://github.com/full-stack-skills/zig-skills.git
cp -r zig-skills/skills/* .claude/skills/
```

For more details, see the [Claude Code Skills Guide](https://code.claude.com/docs/en/skills) and [Agent Skills Spec](https://agentskills.io/).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **All Skill Groups** | [github.com/full-stack-skills](https://github.com/full-stack-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
