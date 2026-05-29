![Module](https://img.shields.io/badge/DEVKiTZ-Module-fa1e4e?style=for-the-badge&labelColor=a855f7)
![Version](https://img.shields.io/badge/version-v1.0.0-fa1e4e?style=flat-square&labelColor=0d0d14)
![License](https://img.shields.io/badge/license-MIT-00ff88?style=flat-square&labelColor=0d0d14)
![Status](https://img.shields.io/badge/status-active-00ff88?style=flat-square&labelColor=0d0d14)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![AI](https://img.shields.io/badge/AI-18_LLM_Providers-a855f7?style=flat-square)

# Copilot Dashboard

> **AI Assistant with 18 LLM Providers** - Part of the [DEVKiTZ](https://github.com/D-VKITZ) Ecosystem

---

## Preview

```
+----------------------------------------------+
|  Copilot    [Chat] [Builder] [Settings]      |
+----------------------------------------------+
|                                              |
|  +- Chat ---------------------------------+  |
|  | User: How do I create a module?        |  |
|  |                                        |  |
|  | Copilot: Use /create-module workflow    |  |
|  | > Step 1: mod-builder skill            |  |
|  | > Step 2: Choose category              |  |
|  | > Step 3: Auto-generate boilerplate    |  |
|  +----------------------------------------+  |
|                                              |
|  Model: Qwen3.6 27B  |  Provider: vLLM      |
+----------------------------------------------+
```

## Features

| Status | Feature |
|:-------|:--------|
| Done | 3-Tab Panel: Chat, Builder, Settings |
| Done | 18 LLM Providers incl. vLLM, DeepSeek, OpenRouter |
| Done | Iceberg Prompt Engine with 6-Part XML |
| Done | Code Execution and Live Preview |
| Done | James Guardian QA Integration |
| Done | PWA Installable |

## LLM Fleet

```
vLLM Engine (:8811) - 8 Models
+------------------------------------------+
| Gemma4 E2B    ~2GB   Always-On           |
| Gemma4 E4B    ~3GB   Balance  SWAP 300s  |
| Qwen3 4B      ~3GB   Quick    SWAP 300s  |
| Qwen3.5 9B    ~6GB   Coder    SWAP 300s  |
| Qwen3 14B    ~10GB   Standard SWAP 300s  |
| Gemma4 26B   ~16GB   Frontend SOLO 180s  |
| Qwen3.6 27B  ~17GB   Dense    SOLO 180s  |
| Qwen3.6 35B  ~22GB   Backend  SOLO 180s  |
+------------------------------------------+
```

## Quick Start

```bash
git clone https://github.com/D-VKITZ/copilot-dashboard.git
open copilot-dashboard/index.html
```

---

<p align="center">
<sub>DEVKiTZ - Made with love by 777 - 2026</sub><br>
<sub>devkitz.eu | dkz.app | github.com/D-VKITZ</sub>
</p>

---

## Documentation

| Resource | Link |
|:---------|:-----|
| Rules | [D-VKITZ/KERN/RULES.md](https://github.com/D-VKITZ/KERN/blob/main/RULES.md) |
| Patterns | [D-VKITZ/KERN/PATTERNS.md](https://github.com/D-VKITZ/KERN/blob/main/PATTERNS.md) |
| Playbook | [D-VKITZ/KERN/PLAYBOOK.md](https://github.com/D-VKITZ/KERN/blob/main/PLAYBOOK.md) |
| llms.txt | [D-VKITZ/KERN/llms.txt](https://github.com/D-VKITZ/KERN/blob/main/llms.txt) |