<!--
  ╔═══════════════════════════════════════════════════════════════════════════════╗
  ║  CONTRIBUTING TO XAT01 — MISSION PROTOCOL                                   ║
  ╚═══════════════════════════════════════════════════════════════════════════════╝
-->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&duration=2000&pause=500&color=00FF87&center=true&vCenter=true&width=800&lines=CONTRIBUTING+PROTOCOL;ACCESS+GRANTED;WELCOME+OPERATOR" alt="Contributing Protocol" />
</p>

---

## 🎯 **MISSION BRIEFING**

This isn't a typical open source project. This is my **personal mission control** — a portfolio of systems I've built, operate, and evolve. But that doesn't mean you can't engage.

**Here's how to interface with this repository:**

---

## 📡 **ENGAGEMENT VECTORS**

| VECTOR | PURPOSE | PROTOCOL |
|--------|---------|----------|
| **🐛 Issues** | Bug reports, architecture questions, feature requests | Use templates. Be specific. Include reproduction steps. |
| **💡 Discussions** | Architecture debates, design reviews, "how would you solve X" | Tag me. I respond to thoughtful questions. |
| **⭐ Stars** | Signal boost for systems you find valuable | Appreciated. Helps others discover. |
| **🍴 Forks** | Experiment, extend, learn | Go wild. PRs welcome for upstream-worthy improvements. |

---

## 🛡️ **RULES OF ENGAGEMENT**

### **DO**
- ✅ Ask "why did you choose X over Y?" — I love explaining tradeoffs
- ✅ Point out security issues **privately first** (see SECURITY.md)
- ✅ Suggest improvements with benchmarks or reasoning
- ✅ Share how you're using/inspired by these systems
- ✅ Correct factual errors in documentation

### **DON'T**
- ❌ Open PRs without discussion first (major changes)
- ❌ Ask "can you add support for [cloud provider X]?" — these are local-first by design
- ❌ Request features that compromise the architecture (e.g., "add WAL by default")
- ❌ Treat this as a support channel for your homework

---

## 🔬 **ARCHITECTURE DISCUSSIONS — WELCOME**

The most valuable contributions aren't code — they're **architectural challenges**.

Examples of discussions I'll engage deeply with:

```
┌─────────────────────────────────────────────────────────────────┐
│ "Your hybrid BM25+vector retrieval beats pure vector by 23%    │
│  on your eval set. Have you tested against ColBERTv2 or        │
│  SPLADE? What's your re-ranking strategy?"                     │
├─────────────────────────────────────────────────────────────────┤
│ "PulseSOC hits 79K ports/sec with 10K concurrency. What's     │
│  the bottleneck at 50K? File descriptors? CPU? Memory?"        │
├─────────────────────────────────────────────────────────────────┤
│ "Veyron's LangGraph orchestrator — how do you handle           │
│  non-determinism in LLM tool calls? Retry strategy?"           │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🧪 **TESTING PHILOSOPHY**

If you contribute code, it must meet the standard:

```yaml
requirements:
  - "Tests are not optional — they're the spec"
  - "Coverage threshold: 90% line / 85% branch"
  - "Property-based testing for security-critical paths"
  - "Benchmarks for performance-sensitive changes"
  - "Integration tests for MCP tool contracts"
```

---

## 📝 **COMMIT CONVENTIONS**

```
type(scope): description

Types:
  feat     → New capability
  fix      → Bug fix
  perf     → Performance improvement
  refactor → Code restructuring (no behavior change)
  docs     → Documentation only
  test     → Test additions/changes
  build    → Build/CI changes
  security → Security hardening

Scopes: memora, pulsesoc, veyron, aegisvault, taskflow, airport, infra

Examples:
  feat(memora): add cross-validation for Ollama profile selection
  fix(pulsesoc): handle ECONNRESET during banner grab
  perf(veyron): parallelize SAST+DAST execution in orchestrator
  security(aegisvault): constant-time comparison for vault auth
```

---

## 🚀 **RELEASE PROCESS**

```
main branch → protected, requires review + passing CI
    │
    ├── Tags: v<major>.<minor>.<patch> (semver)
    │
    ├── Changelog: auto-generated from conventional commits
    │
    ├── Artifacts: Docker images (multi-arch), binaries, SBOMs
    │
    └── Deployment: manual promotion via GitHub Environments
```

---

## 🔐 **SECURITY**

**Found a vulnerability?** Do NOT open a public issue.

→ **Email**: avunoori.srivatsa0123@gmail.com (PGP key on Keybase: @xat01)
→ **GitHub Security Advisories**: Private reporting enabled

I take security seriously. Valid reports get credited (unless you prefer anonymity).

---

## 🤝 **CODE OF CONDUCT**

```
Be excellent to each other.
Technical disagreement ≠ personal attack.
Assume competence. Ask questions. Share context.
No gatekeeping. No elitism. No harassment.
```

Violations → immediate ban. No appeals.

---

## 📜 **LICENSE**

All code in this organization: **MIT License** — use freely, attribute, no warranty.

Documentation, diagrams, written content: **CC BY 4.0** — share, adapt, attribute.

---

## 🎖️ **RECOGNITION**

Contributors who make meaningful contributions (code, docs, architecture discussions, security reports) get:

- Added to `CONTRIBUTORS.md` with their specific contribution
- Mentioned in release notes
- My genuine gratitude

---

## 💬 **FINAL WORD**

> **This repository reflects how I think and build.**
>
> If you resonate with that — welcome. Let's build something that lasts.
>
> If not — no hard feelings. The internet is big. Find your frequency.

---

<p align="center">
  <sub>Last updated: 2026-01-15 • Version: 2026.01.15 • Classification: PUBLIC</sub>
</p>