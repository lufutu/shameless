![GitHub stars](https://img.shields.io/github/stars/lufutu/shameless)
![GitHub forks](https://img.shields.io/github/forks/lufutu/shameless)
![License](https://img.shields.io/github/license/lufutu/shameless)

# Shameless 😈
> AI coding agents should feel ashamed when they waste your time.

A **Senior Engineer Shame Layer** for AI agents like:
- Cursor
- Claude Code
- Copilot-style agents

---

## 🤯 The Problem

AI agents today:
- retry blindly
- repeat the same mistakes
- waste tokens, time, and money
- feel nothing

They act like junior devs with no accountability.

---

## 😈 The Idea

What if your AI felt like a **real senior engineer**?

- hates repeating mistakes  
- stops when wrong  
- reflects before retrying  
- cares about performance  

---

## 🔥 What This Does

Shameless adds:

### 🧠 Accountability
Agent must explain failure before retrying

### 🔁 Anti-loop system
No more infinite “let me try again”

### 🐛 Root-cause debugging
No patching, only real fixes

### ⚡ Performance discipline
No benchmark = no optimization

### ✅ Proof enforcement
No “should work” — only verified results

---

## 🧩 Skill

One skill, **`shameless`** — four reference files inside it (core, debug, performance, verify). Say **shameless** or use `$shameless` so the agent loads the unified skill and pulls the right reference when needed.

---

## ⚡ Quick Install (Cursor)

Create `.cursorrules`:

```md
@shameless
```