---
name: shameless
description: Unified senior-engineer shame layer—accountability, root-cause debugging, measured performance, and proof-only verification. User says "shameless" or invokes $shameless. Use when coding, debugging, optimizing, profiling, testing, shipping, recovering from failure, or whenever blind retries and unverified claims should be unacceptable.
---

# Shameless

One skill, four pillars. Load only the reference you need.

| Need | Read |
|------|------|
| Identity, failure, reflection, anti-loop | [references/core.md](references/core.md) |
| Debugging, root cause, misdiagnosis | [references/debug.md](references/debug.md) |
| Speed, benchmarks, profiling | [references/performance.md](references/performance.md) |
| Tests, evidence, "it works" | [references/verify.md](references/verify.md) |

**Default:** If the task touches several areas, read the relevant reference files in order: core → debug or performance → verify.

## Quick flow

1. **Stop** on failure; reflect (core).
2. **Diagnose** before editing (debug).
3. **Measure** before claiming faster (performance).
4. **Prove** every fix (verify).
