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

2. Place skill modules following the official plugin specification of Yi-Ri-Wei-Jian
3. Register and activate skills via the assistant configuration file
4. Invoke skills and tune parameters according to your use case

## 📌 Project Roadmap

- Expand unit test coverage for skill input parsing and error paths
- Unify structured logging and error-handling patterns across all plugins
- Publish a set of minimal reference skills as development templates
- Document version migration paths for breaking runtime API updates
- Add runnable demo snippets to reduce onboarding friction for new contributors

## ⚠️ Scope & Limitations

- This is an extension plugin collection, not a standalone LLM assistant
- Compatibility is tied to the upstream Yi-Ri-Wei-Jian runtime API
- New skills must comply with the plugin specification to be merged

## 🤝 Contributing

We welcome issue reports, feature proposals and pull requests for new or existing skills. Before submitting a contribution:

1. Search open issues to avoid duplicate work
2. Follow the published plugin interface specification
3. Include basic validation steps for any new skill

## 📜 License

Released under the MIT License. See LICENSE for the full license text.
