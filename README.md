# SpyneJS

SpyneJS is a behavior-first frontend framework and structure built around a **View–Behavior–Logic (VBL) architecture**.
VBL mirrors the natural language structure used to describe applications: what exists (View), when things happen (Behavior), and why decisions are made (Logic).

---
## Core
- **[spyne](https://github.com/spynejs/spyne)**  
  The SpyneJS framework runtime
- **[spyne-cli](https://github.com/spynejs/spyne-cli)**  
  Application scaffolding and structured generation of ViewStream, Channel, and SpyneTrait modules
---
## AI & Knowledge Layer
- **[grammar](https://github.com/spynejs/grammar)**  
  The SpyneJS Generative Grammar (`@spynejs/grammar`, formerly `@spynejs/kb`) — the rules an AI
  agent reads to write well-formed SpyneJS code: operation cards, construction records, a mental
  model, and task trees that route an agent to only what the task needs.
  `AGENTS.md` is the entry point and takes precedence over the model's prior knowledge of the framework.
  Ships inside every application template and is read from `node_modules`, so agents work from the
  current release, not stale training data.
  Versioned with framework releases and measured against a public multi-model benchmark:
  [benchmark-protocol](https://github.com/relevantcontext/benchmark-protocol)
---
## CMS & Authoring
- **[@spynejs/cms](https://github.com/spynejs/cms)**  
  CMS runtime plugin for structured JSON authoring inside SpyneJS applications
- **[@spynejs/cms-adapter](https://github.com/spynejs/cms-adapter)**  
  Local development adapter for safe, deterministic JSON persistence
---
## Design System & Theming
- **[design.spynejs.com](https://design.spynejs.com)**  
  A token-based design system for SpyneJS applications.
  It provides structured design primitives—spacing, typography, color, layout, and component-level controls—that can be safely customized without breaking application architecture.
  The system is intentionally evolving and designed to support:
  - Custom themes
  - Controlled visual variation
  - Design changes that remain compatible with AI-assisted generation and long-lived applications
  Design tokens act as a stable interface between visual intent and application structure.
---
## Developer Tools & Plugins
- **[spyne-plugin-console](https://github.com/spynejs/spyne-plugin-console)**  
  Live visualization of channel streams and outputs for inspecting, creating, and capturing application behavior
- **[plugin-starter](https://github.com/spynejs/plugin-starter)**  
  Starter template for building SpyneJS plugins
---
## Documentation & Resources
- **[Documentation](https://spynejs.com)**
- **[Design System](https://design.spynejs.com)**
- **[AI & Architecture Rationale](https://spynejs.ai)**
