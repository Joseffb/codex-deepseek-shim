# Codex DeepSeek Shim

Codex DeepSeek Shim explored a provider-compatibility and routing layer for Codex workflows while preserving Codex-visible OpenAI Responses semantics and adapting physical providers behind that boundary.

## Why it matters

- Expands provider choice inside Codex workflows.
- Enables cost/performance matching across capable models.
- Aims to preserve one consistent Codex-facing experience while providers vary behind it.
- Keeps provider adaptation separate from project orchestration.
- Supports experimentation without making provider mechanics the user workflow.

These experimental integrations modified Codex workflow behavior. In practice, defects in Agent System and Shim introduced unacceptable instability. The current Codex app integration surface also limited the stability guarantees the implementation needed to provide.

**The implementation is no longer publicly available due to stability issues.**

A new public version will be added when the required stability has been achieved.

## Future public release

A future stable public version may include architecture diagrams at an appropriate abstraction level, measured outcomes, research notes, demos, benchmark methodology and results, and selected interfaces/contracts. Implementation internals and private operating material remain private.

The implementation is unsupported. Users should discontinue use and remove deployed copies.

[OpenCodex](https://github.com/lidge-jun/opencodex) is a related public alternative for provider-flexible Codex workflows. It is a separate project—not the same implementation, an official successor, partner, dependency, or drop-in replacement.
