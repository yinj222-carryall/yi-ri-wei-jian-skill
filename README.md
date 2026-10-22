# Yi-Ri-Wei-Jian Skill
Modular skill plugin ecosystem for extending the Yi-Ri-Wei-Jian LLM assistant.

This repository hosts community-oriented, runtime-compatible skill modules that extend the native capabilities of the Yi-Ri-Wei-Jian assistant framework.
It standardizes skill interfaces so custom functional logic can be plugged in without modifying the upstream assistant core, lowering the barrier for contributors to build reusable assistant capabilities.

## ✨ Key Capabilities
- Decoupled plugin design: each skill is an independent module, supporting selective loading, disabling and migration
- Standardized I/O contract: uniform input/output schema for stable integration with the upstream assistant runtime
- Compatibility-focused maintenance: ongoing fixes for parsing edge cases, runtime API changes and documentation gaps
- Community extensible: open submission workflow for new skills, feature proposals and bug patches

## 📦 Getting Started
> Prerequisite: A working deployment of the Yi-Ri-Wei-Jian assistant runtime. This repository only provides skill plugins and does not include the main assistant service.

1. Clone the repository
```bash
git clone https://github.com/yinj222-carryall/yi-ri-wei-jian-skill.git
```
