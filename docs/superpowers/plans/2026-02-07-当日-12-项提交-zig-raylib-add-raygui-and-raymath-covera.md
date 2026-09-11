# zig-skills 历史任务：当日 12 项提交（zig-raylib: Add raygui and raymath coverage, and mistakes section to SKILL.md 等）（2026-02-07）

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.
> **本计划为历史任务回填**：依据 git 提交记录还原，全部任务已完成，复选框均为 `- [x]`。

**Goal:** 本日完成 12 项提交：

1. zig-raylib: Add raygui and raymath coverage, and mistakes section to SKILL.md
2. zig: Correct some build system code to use new API
3. zig-raylib: Improve API coverage
4. zig-sdl3-bindings: Fix a *ton* of hallucinations after verifying vs src and docs
5. Update README.md to reflect current directory structure
6. zig-raylib: Move to zig-raylib directory since Claude Chat won't install skills with a . in the name
7. zig-sdl3-bindings: Destructure tuples
8. zig-sdl3-bindings: Fix a lot of ArrayList usage and other issues
9. zig-raylib: Fix some minor inaccuracies with examples
10. zig: Fix some inaccuracies (one dangling pointer) and expand code-review
11. zig: Shorten code review
12. Rename zig-0.15 skill to zig Claude Chat doesn't like the period and won't install it otherwise

**Architecture:** 仓库元数据与文档维护、技能内容更新（SKILL.md）、技能参考/示例资料更新。

**Tech Stack:** Markdown。

**Spec:** 无独立规格文档；依据提交 `824184a`, `af619f9`, `4896d47`, `96c6658`, `f1058fc`, `cbbaf95`, `a178b31`, `7a1231d`, `8a7884d`, `5cbdb6d`, `573fcbb`, `dc21422` 还原。

## Global Constraints

- 本计划依据 git 历史回填，仅记录已完成工作（12 个提交均已落地）
- 不含未完成或计划中的工作；步骤复选框全部为已完成状态

---

### Task 1: zig-raylib: Add raygui and raymath coverage, and mistakes section to SKILL.md

**Files:**
- `skills/zig-raylib/SKILL.md`
- `skills/zig-raylib/references/api-3d.md`
- `skills/zig-raylib/references/api-audio.md`
- `skills/zig-raylib/references/api-core.md`
- `skills/zig-raylib/references/api-math-gl.md`
- `skills/zig-raylib/references/api-raygui.md`
- `skills/zig-raylib/references/examples.md`

- [x] **Step 1: 完成「zig-raylib: Add raygui and raymath coverage, and mistakes section to SKILL.md」（Austin Rude）**
- [x] **Step 2: 提交** — `824184a` zig-raylib: Add raygui and raymath coverage, and mistakes section to SKILL.md

---

### Task 2: zig: Correct some build system code to use new API

**Files:**
- `skills/zig-0.15/SKILL.md`
- `skills/zig-0.16/references/std-build.md`

- [x] **Step 1: 完成「zig: Correct some build system code to use new API」（Austin Rude）**
- [x] **Step 2: 提交** — `af619f9` zig: Correct some build system code to use new API

---

### Task 3: zig-raylib: Improve API coverage

**Files:**
- `skills/zig-raylib/references/api-3d.md`
- `skills/zig-raylib/references/api-audio.md`
- `skills/zig-raylib/references/api-core.md`
- `skills/zig-raylib/references/api-drawing.md`
- `skills/zig-raylib/references/api-resources.md`

- [x] **Step 1: 完成「zig-raylib: Improve API coverage」（Austin Rude）**
- [x] **Step 2: 提交** — `4896d47` zig-raylib: Improve API coverage

---

### Task 4: zig-sdl3-bindings: Fix a *ton* of hallucinations after verifying vs src and docs

**Files:**
- `skills/zig-sdl3-bindings/SKILL.md`
- `skills/zig-sdl3-bindings/references/allocator-integration.md`
- `skills/zig-sdl3-bindings/references/audio.md`
- `skills/zig-sdl3-bindings/references/binding-patterns.md`
- `skills/zig-sdl3-bindings/references/camera.md`
- `skills/zig-sdl3-bindings/references/clipboard.md`
- `skills/zig-sdl3-bindings/references/events.md`
- `skills/zig-sdl3-bindings/references/filesystem-io.md`
- `skills/zig-sdl3-bindings/references/gamepad-joystick.md`
- `skills/zig-sdl3-bindings/references/getting-started.md`
- `skills/zig-sdl3-bindings/references/gpu.md`
- `skills/zig-sdl3-bindings/references/image.md`
- `skills/zig-sdl3-bindings/references/keyboard.md`
- `skills/zig-sdl3-bindings/references/log-errors.md`
- `skills/zig-sdl3-bindings/references/mouse.md`
- …等共 24 个文件

- [x] **Step 1: 完成「zig-sdl3-bindings: Fix a *ton* of hallucinations after verifying vs src and docs」（Austin Rude）**
- [x] **Step 2: 提交** — `96c6658` zig-sdl3-bindings: Fix a *ton* of hallucinations after verifying vs src and docs

---

### Task 5: Update README.md to reflect current directory structure

**Files:**
- `README.md`

- [x] **Step 1: 完成「Update README.md to reflect current directory structure」（Austin Rude）**
- [x] **Step 2: 提交** — `f1058fc` Update README.md to reflect current directory structure

---

### Task 6: zig-raylib: Move to zig-raylib directory since Claude Chat won't install skills with a . in the name

**Files:**
- `skills/zig-raylib/SKILL.md`
- `skills/zig-raylib/references/api-3d.md`
- `skills/zig-raylib/references/api-audio.md`
- `skills/zig-raylib/references/api-core.md`
- `skills/zig-raylib/references/api-drawing.md`
- `skills/zig-raylib/references/api-resources.md`
- `skills/zig-raylib/references/examples.md`

- [x] **Step 1: 完成「zig-raylib: Move to zig-raylib directory since Claude Chat won't install skills with a . in the name」（Austin Rude）**
- [x] **Step 2: 提交** — `cbbaf95` zig-raylib: Move to zig-raylib directory since Claude Chat won't install skills with a . in the name

---

### Task 7: zig-sdl3-bindings: Destructure tuples

**Files:**
- `skills/zig-sdl3-bindings/SKILL.md`
- `skills/zig-sdl3-bindings/references/audio.md`
- `skills/zig-sdl3-bindings/references/camera.md`
- `skills/zig-sdl3-bindings/references/gamepad-joystick.md`
- `skills/zig-sdl3-bindings/references/image.md`
- `skills/zig-sdl3-bindings/references/keyboard.md`
- `skills/zig-sdl3-bindings/references/mouse.md`
- `skills/zig-sdl3-bindings/references/ttf.md`
- `skills/zig-sdl3-bindings/references/video-windows.md`

- [x] **Step 1: 完成「zig-sdl3-bindings: Destructure tuples」（Austin Rude）**
- [x] **Step 2: 提交** — `a178b31` zig-sdl3-bindings: Destructure tuples

---

### Task 8: zig-sdl3-bindings: Fix a lot of ArrayList usage and other issues

**Files:**
- `skills/zig-sdl3-bindings/references/allocator-integration.md`
- `skills/zig-sdl3-bindings/references/audio.md`
- `skills/zig-sdl3-bindings/references/camera.md`
- `skills/zig-sdl3-bindings/references/clipboard.md`
- `skills/zig-sdl3-bindings/references/events.md`
- `skills/zig-sdl3-bindings/references/filesystem-io.md`
- `skills/zig-sdl3-bindings/references/image.md`
- `skills/zig-sdl3-bindings/references/init-lifecycle.md`
- `skills/zig-sdl3-bindings/references/keyboard.md`
- `skills/zig-sdl3-bindings/references/mouse.md`
- `skills/zig-sdl3-bindings/references/net.md`
- `skills/zig-sdl3-bindings/references/storage.md`
- `skills/zig-sdl3-bindings/references/threading.md`
- `skills/zig-sdl3-bindings/references/touch-pen.md`
- `skills/zig-sdl3-bindings/references/ttf.md`
- …等共 16 个文件

- [x] **Step 1: 完成「zig-sdl3-bindings: Fix a lot of ArrayList usage and other issues」（Austin Rude）**
- [x] **Step 2: 提交** — `7a1231d` zig-sdl3-bindings: Fix a lot of ArrayList usage and other issues

---

### Task 9: zig-raylib: Fix some minor inaccuracies with examples

**Files:**
- `skills/zig-raylib/SKILL.md`
- `skills/zig-raylib/references/api-3d.md`
- `skills/zig-raylib/references/api-core.md`
- `skills/zig-raylib/references/api-drawing.md`
- `skills/zig-raylib/references/api-resources.md`

- [x] **Step 1: 完成「zig-raylib: Fix some minor inaccuracies with examples」（Austin Rude）**
- [x] **Step 2: 提交** — `8a7884d` zig-raylib: Fix some minor inaccuracies with examples

---

### Task 10: zig: Fix some inaccuracies (one dangling pointer) and expand code-review

**Files:**
- `skills/zig-0.16/references/code-review.md`

- [x] **Step 1: 完成「zig: Fix some inaccuracies (one dangling pointer) and expand code-review」（Austin Rude）**
- [x] **Step 2: 提交** — `5cbdb6d` zig: Fix some inaccuracies (one dangling pointer) and expand code-review

---

### Task 11: zig: Shorten code review

**Files:**
- `skills/zig-0.16/references/code-review.md`

- [x] **Step 1: 完成「zig: Shorten code review」（Austin Rude）**
- [x] **Step 2: 提交** — `573fcbb` zig: Shorten code review

---

### Task 12: Rename zig-0.15 skill to zig Claude Chat doesn't like the period and won't install it otherwise

**Files:**
- `skills/zig-0.15/SKILL.md`
- `skills/zig-0.16/references/builtins.md`
- `skills/zig-0.16/references/c-interop.md`
- `skills/zig-0.16/references/code-review.md`
- `skills/zig-0.16/references/comptime.md`
- `skills/zig-0.16/references/language.md`
- `skills/zig-0.16/references/patterns.md`
- `skills/zig-0.16/references/std-allocators.md`
- `skills/zig-0.16/references/std-array-hash-map.md`
- `skills/zig-0.16/references/std-arraylist.md`
- `skills/zig-0.16/references/std-ascii.md`
- `skills/zig-0.16/references/std-atomic.md`
- `skills/zig-0.16/references/std-base64.md`
- `skills/zig-0.16/references/std-bit-set.md`
- `skills/zig-0.16/references/std-buf-map.md`
- …等共 56 个文件

- [x] **Step 1: 完成「Rename zig-0.15 skill to zig Claude Chat doesn't like the period and won't install it otherwise」（Austin Rude）**
- [x] **Step 2: 提交** — `dc21422` Rename zig-0.15 skill to zig Claude Chat doesn't like the period and won't install it otherwise
