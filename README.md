# Idan's Ponytail (`idans-ponytail`)

> **"Gathering loose context, cutting token bloat."**  
> A high-efficiency AI agent persona combining the **Lazy Senior Developer** mindset with strict **Token-Economy** guardrails.

---

## The Story & Philosophy

`idans-ponytail` was created by **Idan Dovrat**, an Israeli developer who took the open-source "Ponytail" concept to its logical next stage.

While traditional lean coding modes focus purely on avoiding redundant code inside the repository, AI agents frequently waste tens of thousands of tokens by reading massive files and dumping unrestricted terminal output directly into the context window[cite: 1, 2]. 

### Why "Ponytail"?
- **Tying Up Loose Ends**: Just like pulling hair back into a neat, disciplined ponytail, this skill gathers scattered outputs, trims irrelevant noise, and keeps the context window tight.
- **A Play on Words**: A sleek, agile pony's tail that moves fast without dragging excess baggage behind it.

---

## What Sets It Apart

| Feature | Upstream Ponytail | Idan's Ponytail |
| :--- | :--- | :--- |
| **Philosophy** | "The best code is unwritten"[cite: 1, 2] | "Unwritten code + Unread noise" |
| **Code Structure** | Minimal diffs, no boilerplate[cite: 1, 2] | Minimal diffs, zero overhead[cite: 1, 2] |
| **Terminal Output** | Unregulated | Filtered via `grep`, `tail`, quiet flags |
| **File Inspection** | Reads whole files on demand | Surgical line offsets (30-60 lines) |
| **Response Style** | Detailed with risks[cite: 1, 2] | 2-4 terse bullets + risk line[cite: 1, 2] |

---

## Quick Installation

### For Claude Code / Local Skills:
```bash
mkdir -p ~/.claude/skills/idans-ponytail
cp idans-ponytail.md ~/.claude/skills/idans-ponytail/SKILL.md
