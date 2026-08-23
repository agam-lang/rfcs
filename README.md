# 📜 Agam Request for Comments (RFCs)

> Part of the [agam-lang](https://github.com/agam-lang) organization.  
> The formal design proposal process for substantial changes, new syntax features, standard library modules, and architectural evolutions to **Agam**.

---

## 🏛️ RFC Lifecycle

```
  ┌──────────────┐      ┌───────────────┐      ┌───────────────┐
  │ 1. Draft RFC │ ───► │ 2. Active RFC │ ───► │  3. Accepted  │
  └──────────────┘      └───────────────┘      └───────┬───────┘
                                                       │
                                                       ▼
  ┌──────────────┐      ┌───────────────┐      ┌───────────────┐
  │ 6. Stabilized│ ◄─── │5. Implemented │ ◄─── │4. Under Devel │
  └──────────────┘      └───────────────┘      └───────────────┘
```

1. **Draft**: Initial exploration in a branch or PR.
2. **Active**: Open for community and core team review.
3. **Accepted**: Consensus reached; approved by language design team.
4. **Under Development**: Implemented in compiler branches (`crates/middle/` or `crates/backends/`).
5. **Implemented**: Shipped in nightly compiler release.
6. **Stabilized**: Promoted to official language standard specification.

---

## 📂 Active & Implemented RFCs

| RFC Number | Title | Status | Primary Area |
| :--- | :--- | :--- | :--- |
| **RFC 001** | [Dual-Profile Syntax (`@lang.base` & `@lang.advance`)](text/0001-dual-syntax-profiles.md) | **Stabilized** | Frontend / Parser |
| **RFC 002** | [Shape-Aware Multi-Dimensional Tensors](text/0002-shape-aware-tensors.md) | **Implemented** | Type System / ML |
| **RFC 003** | [Algebraic Effects & Resumable Continuations](text/0003-algebraic-effects.md) | **Implemented** | Semantics / MIR |
| **RFC 004** | [Hardware Tile & SPIR-V Cooperative Matrix (`@gpu`)](text/0004-gpu-tile-kernels.md) | **Implemented** | Codegen / GPU |
| **RFC 005** | [Chāṇakya Durdharṣa Sandboxed Agent Execution](text/0005-durdharsa-sandbox.md) | **Accepted** | Security / VM |

---

## ✍️ How to Submit an RFC

1. Copy the official template: `0000-template.md`.
2. Fill in the motivation, guide-level explanation, reference-level explanation, and alternatives.
3. Submit a pull request to `agam-lang/rfcs`.

---

## 📜 License

Dual-licensed under [MIT](LICENSE-MIT) and [Apache 2.0](LICENSE-APACHE).
