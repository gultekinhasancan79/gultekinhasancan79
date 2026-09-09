<div align="center">

# Hasancan Gültekin

### RL Environment & Agent Evaluation Engineer

I build **reproducible environments for tool-using and coding agents**, design deterministic graders, and investigate failures in agent behavior, tasks, and evaluation systems.

**Available for remote contracts · Türkiye (UTC+3) · 30+ hours/week · Immediate start**

<p>
  <a href="https://www.linkedin.com/in/can79/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:gultekinhasancan79@gmail.com"><img src="https://img.shields.io/badge/Email-3B82F6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

## Start Here: [beancount-ledger](https://github.com/gultekinhasancan79/beancount-ledger)

**An RL environment where an agent handles a small company's bookkeeping, and a deterministic scorer checks the result.**

Built on Prime Intellect's `verifiers` and published on the Environments Hub. The environment covers bookkeeping workflows including bank reconciliation, accounts payable, payroll, and month-end close, with tool-based interaction and rewards derived from ledger state rather than an LLM judge.

- **Evaluation design:** keyed task generation, explicit evaluation boundaries, reproducible episode contracts, and an exploit-test corpus.
- **Published evidence:** a fixed-panel evaluation of four open-weight models with 138 valid episodes. This is an evaluation study, not a claim that an RL policy was trained.
- **Review workflow:** a local desktop app runs and replays episodes, showing ledger changes and scorer feedback.

[Code & quickstart](https://github.com/gultekinhasancan79/beancount-ledger) · [Evaluation report](https://github.com/gultekinhasancan79/beancount-ledger/blob/main/reviews/arms_confirm1v4.md) · [Technical reference](https://github.com/gultekinhasancan79/beancount-ledger/blob/main/docs/REFERENCE.md)

---

## Relevant Experience

**Fleet AI — computer-use task authoring and QA review**

- Authored and reviewed multi-step tasks in simulated enterprise software environments, including NetSuite workflows.
- Checked task instructions, environment state, agent trajectories, and grader behavior to distinguish model failures from task or evaluation issues.
- Documented edge cases and revised tasks and grading logic for clearer, more reliable evaluation.

The public projects below are independent work samples. They do not publish proprietary Fleet tasks or client data.

---

## What I Can Contribute

- **Computer-use & tool-use evaluation:** task authoring, trajectory review, failure analysis, and structured feedback.
- **RL environment & grader engineering:** Python tooling, deterministic scoring, held-out tests, and reproducible evaluation setups.
- **Agentic coding QA:** behavioral testing, verifier debugging, and assessment of candidate patches.
- **Supporting engineering:** Python, SQL, APIs, automation, and data-quality checks.

---

## Core Stack

**Languages & Data**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-2563EB?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/NumPy-4D77CF?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
</p>

**Evaluation & Analytics**

<p>
  <img src="https://img.shields.io/badge/LLM%20Evaluation-7C3AED?style=for-the-badge" alt="LLM Evaluation" />
  <img src="https://img.shields.io/badge/Agent%20Evaluation-6D28D9?style=for-the-badge" alt="Agent Evaluation" />
  <img src="https://img.shields.io/badge/A%2FB%20Testing-0891B2?style=for-the-badge" alt="A/B Testing" />
  <img src="https://img.shields.io/badge/Product%20Analytics-0F766E?style=for-the-badge" alt="Product Analytics" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=111827" alt="Power BI" />
</p>

**Engineering**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/REST%20APIs-334155?style=for-the-badge" alt="REST APIs" />
</p>

---

## More Selected Work

### 🧪 [swe-rl-envs](https://github.com/gultekinhasancan79/swe-rl-envs)
**Reproducible evaluation environments for agentic coding benchmarks.**

A benchmark suite with two distinct agentic coding environments: `runlog-rollup` for process-lifetime state leakage and `cursor-pagination` for cursor-protocol reasoning. Both use held-out acceptance tests, network-isolated digest-pinned containers, layered anti-gaming verification, auditable golden evidence, and matrix CI.

**Evidence:** 33 visible tests · 22 held-out tests · 55 combined tests across two 9-gate environments.

`Agent Evaluation` · `Python` · `Docker` · `Pytest` · `Reproducibility`

<br>

### 📊 [Product Analytics Case Study](https://github.com/gultekinhasancan79/product-analytics-case-study)
**Reproducible onboarding A/B experiment with experiment-integrity, event-analytics, and advanced experimentation layers.**

A deterministic 12,000-user experiment with SRM and pre-treatment balance checks, power/MDE planning, formal treatment × device interaction inference, CUPED-style sensitivity analysis, a 41,209-row product-event fact table, event-level data-quality gates, executable funnel/cohort SQL, and a reviewer Jupyter walkthrough that is executed in CI on the tested analysis path.

**Evidence:** activation +2.13 pp · p = 0.0193 · SRM p = 0.6613 · realized 80%-power MDE ≈ 2.55 pp · planning power at observed lift ≈ 64.8% · CUPED-style variance reduction 1.47%.

`Product Analytics` · `Experimentation` · `A/B Testing` · `Python` · `SQL` · `Statistics` · `Jupyter`

<br>

### ✨ [Prompt Enhancer](https://github.com/gultekinhasancan79/Oto_prompt_Engineer)
**Browser extension for improving prompts directly inside AI applications.**

Supports ChatGPT, Gemini, Claude, Perplexity, and other AI interfaces with iterative enhancement, undo history, language preservation, keyboard shortcuts, and local API-key storage.

`JavaScript` · `Chrome Extension` · `Groq API` · `Prompt Engineering`

<br>

### 🗂️ [MediaClean](https://github.com/gultekinhasancan79/MediaClean)
**Keyboard-driven desktop utility for reviewing and cleaning large media folders quickly.**

Supports image and video previews, fast keyboard navigation, safe moves to a local `_trash` directory, and undo functionality instead of permanent deletion.

`Python` · `Desktop Automation` · `Pillow` · `OpenCV`

---

## Engineering Principles

> **Reproducible runs, inspectable evidence, and clearly stated limitations.**

I care about building systems that are easy to inspect, test, reproduce, and explain — whether that means an evaluation harness, an analytics workflow, or a small utility solving a concrete problem.

---

## Current Focus

- Building and evaluating **tool-use and agentic coding environments**
- Improving **grader reliability, trajectory review, and failure analysis**
- Making evaluation evidence easier to inspect and reproduce

---

<div align="center">

### Connect

<a href="https://www.linkedin.com/in/can79/">LinkedIn</a> · <a href="mailto:gultekinhasancan79@gmail.com">Email</a>

</div>
