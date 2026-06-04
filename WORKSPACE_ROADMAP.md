# 🧬 Dual-Repository Ecosystem Workspace Roadmap
**Current Status & Backlog Tracking**

This document maps out the "Top 20" strategic backlog items for both the main **Hermes Agent** and its companion optimizer **Hermes Agent Self-Evolution**.

---

## 🚀 Status Summary

- **Completed Tasks:** 10 / 20
- **Current Active Focus:** Phase 2 Planning & Optimization selections
- **Ecosystem Base:** 100% operational (Venv, Pytest suite, Cron, Kanban scheduler, and Report generation active)

---

## 📋 The "Top 20" Backlog

| ID  | Task Name                                                      | Repository                   | Scope          | Status      | Details / Verification |
|-----|----------------------------------------------------------------|------------------------------|----------------|-------------|-------------------------|
| 1   | Initialize joint developer sandbox workspace                  | both                         | Infrastructure | **Done**    | Venvs compiled, workspace boundaries mapped, dual AGENTS.md paths reconciled. |
| 2   | Sync dev dependencies and pin packages under standard protocol | both                         | Configuration  | **Done**    | Bound ranges configured (`httpx`, `reportlab`, etc.). Hashes locked in `uv.lock`. |
| 3   | Configure pytest timezone isolation & temp-dir override        | hermes-agent-self-evolution  | Testing        | **Done**    | Win32 permissions issue bypassed with explicit `--basetemp` in tests. |
| 4   | Draft and synchronize PULL_REQUEST_TEMPLATE.md                 | both                         | CI/CD          | **Done**    | Quality checklists, formatter lints, and benchmark steps synchronized. |
| 5   | Build custom synthetic dataset generator and check schema       | hermes-agent-self-evolution  | Datasets       | **Done**    | Standard inputs mapping and validation rubrics tested. |
| 6   | Connect OpenRouter / MiniMax M2.5 LLM endpoints                | hermes-agent-self-evolution  | LLM API        | **Done**    | Endpoints tested; keys verified securely; test integrations validated. |
| 7   | Run end-to-end multi-round DSPy evolution loop                 | hermes-agent-self-evolution  | Optimizers     | **Done**    | Ran over `arxiv` skill with +39.5% completion quality improvement. |
| 8   | Establish GitHub Workflows security & PR template compliance   | both                         | CI/CD          | **Done**    | Secure workflow guidelines established; PR templates aligned with core rules. |
| 9   | Set up local secure script execution for Cron/Kanban dispatch   | hermes-agent                 | Cron/Kanban    | **Done**    | `C:\Users\k\.hermes\scripts\kanban_dispatch.py` active; added to `hermes cron` loop. |
| 10  | Review GEPA Integration Metrics and compile/run PDF reports   | hermes-agent-self-evolution  | Reports        | **Done**    | `generate_report.py` executes; PDF published to `reports/phase1_validation_report.pdf`. |
| 11  | Select Phase 2 Evolve target skill: `github-code-review`      | hermes-agent-self-evolution  | Optimizers     | *Next Up*   | Setup dataset for automated PR reviews. |
| 12  | Optimize `search_files` tool description schema               | hermes-agent                 | Tools          | Planned     | Improve agent classification choice over raw command run. |
| 13  | Fine-tune agent persona system prompt components              | hermes-agent                 | System Prompts| Planned     | Ensure zero cache-breaking mutations; off-line evaluation. |
| 14  | Integrate TBLite / YC-Bench metrics into self-evolution gate  | hermes-agent-self-evolution  | Benchmarks     | Planned     | Automated benchmarking check prior to PR proposal. |
| 15  | Implement file size and structural guardrails check post-run   | hermes-agent-self-evolution  | Guardrails     | Planned     | Lock down rules on skill size growth (<15KB or <20% growth). |
| 16  | Scale dataset generator to cover golden master sessions        | hermes-agent-self-evolution  | Datasets       | Planned     | Programmatic mining from `SessionDB` (`~/.hermes/sessions.db`). |
| 17  | Setup Multi-agent Dispatch routing over local Kanban board   | hermes-agent                 | Kanban         | Planned     | Dispatcher handling multi-profile loads asynchronously. |
| 18  | Standardize skin engine color configuration defaults           | hermes-agent                 | Themes/Skins   | Planned     | Enable easy CLI/TUI color-branding overrides. |
| 19  | Evolve tool execution code implementations (Darwinian Phase 4)| hermes-agent-self-evolution  | Code Evolution | Planned     | Secure patch-matching optimization using Genetic Organisms. |
| 20  | Conduct full end-to-end integration safety dry-runs            | both                         | Verification   | Planned     | Secure validation of candidate code edits. |

---

## 📈 Next Action Plans

1. **Phase 2 Selection:** Review exact parameters of the `github-code-review` skill or other high-priority skills.
2. **Golden Session Mining:** Begin parsing local `sessions.db` to extract highly accurate, multi-turn trajectories rather than pure synthetic examples.
3. **Guardrails Enforcement:** Ensure all automated PR proposals require full test suites (`pytest tests/`) to pass 100% on Windows environments with `--basetemp` override.
