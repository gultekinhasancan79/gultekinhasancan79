# Hasancan Gültekin

**I build environments and graders that test whether AI agents complete real-world tasks.**

RL environments · tool-use and computer-use evaluation · coding-agent verification

**Open to remote contracts** · Türkiye (UTC+3) · 30+ hours/week · [Email](mailto:gultekinhasancan79@gmail.com) · [LinkedIn](https://www.linkedin.com/in/can79/) · [Hugging Face](https://huggingface.co/gultekinhasancan79)

## Start here: [beancount-ledger](https://github.com/gultekinhasancan79/beancount-ledger)

An accounting environment where agents inspect business records, repair Beancount ledgers, and account for how customer payments are applied.

- **Deterministic evaluation:** inspectable scoring criteria for task completion and the consistency of delivered artifacts.
- **Environment engineering:** reproducible episode contracts, keyed task generation, and adversarial scorer tests, built on Prime Intellect's `verifiers`.
- **Published research:** a fixed-panel study of four Mistral models (three open-weight) on six generated bank-reconciliation tasks, with 138 valid episodes across three episode-contract arms. The report states the measured version and limitations; no policy was trained in this study.

[Try the local scorer](https://github.com/gultekinhasancan79/beancount-ledger#quickstart) · [Evaluation study](https://github.com/gultekinhasancan79/beancount-ledger/blob/main/reviews/arms_confirm1v4.md) · [Technical reference](https://github.com/gultekinhasancan79/beancount-ledger/blob/main/docs/REFERENCE.md) · [Replay recorded rollouts](https://huggingface.co/spaces/gultekinhasancan79/beancount-ledger-replay)

## Coding-agent evaluation: [swe-rl-envs](https://github.com/gultekinhasancan79/swe-rl-envs)

Two small environments test whether a code patch restores the intended behavior: shared state across Python calls, and pagination that must follow the cursor even after a short page.

33 visible tests + 22 held-out tests · nine verification gates per environment · isolated, pinned Docker execution · [v0.1.0 release](https://github.com/gultekinhasancan79/swe-rl-envs/releases/tag/v0.1.0)

## Experience

**Fleet AI — computer-use task authoring and QA review.** Authored and reviewed multi-step enterprise workflows, including NetSuite tasks. Inspected instructions, environment state, agent trajectories, and grading behavior to diagnose task, model, and evaluator failures.

The projects here are independent public work samples; proprietary Fleet tasks and client data are excluded.

**Tools:** Python · SQL · Docker · Pytest · APIs · GitHub Actions

**How I work:** I build with AI coding agents (Codex, Claude Code) under a [documented builder/reviewer workflow](https://github.com/gultekinhasancan79/beancount-ledger/blob/main/AGENTS.md); I set the design and approve every merge.

## Other work

- [Product analytics case study](https://github.com/gultekinhasancan79/product-analytics-case-study) — **synthetic-data case study** with 12,000 simulated signups, A/B analysis, executable SQL, and reproducible reports.
- [MediaClean](https://github.com/gultekinhasancan79/MediaClean) — desktop media review with keyboard navigation and undo.
