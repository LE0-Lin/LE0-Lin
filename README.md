# Zhibo Lin

Computer Science undergraduate at **Southwest University**, working on agent reliability, developer tools, and backend systems.

[Merged contributions](https://github.com/search?q=is%3Apr+is%3Amerged+author%3ALE0-Lin&type=pullrequests) · [Kaggle](https://www.kaggle.com/leolin05) · [LinkedIn](https://www.linkedin.com/in/zhibo-lin/) · [Email](mailto:zhibo.lin@outlook.com)

I am interested in what happens when software changes: whether an agent's instructions lose a constraint, a workflow stops reporting failures, or a cache returns the wrong result at a boundary. My projects and upstream contributions explore ways to make those failures reproducible and testable.

## Projects

### [AgentConfigScore](https://github.com/LE0-Lin/AgentConfigScore)

Local static analysis and baseline-governed CI checks for coding-agent instructions, including `AGENTS.md`, `CLAUDE.md`, Cursor, Copilot, and Gemini.

- Compare instruction changes against a baseline and enforce the baseline's policy in CI.
- Report deterministic rule findings with rule IDs and source locations where available; export SARIF for GitHub code scanning.
- Run locally without model API calls or third-party runtime dependencies. Available as a Python CLI and a GitHub Action.

[Quick start and limitations](https://github.com/LE0-Lin/AgentConfigScore#readme) · [Documentation](https://github.com/LE0-Lin/AgentConfigScore/tree/main/docs)

[![PyPI](https://img.shields.io/pypi/v/agent-config-score?style=flat-square&label=PyPI)](https://pypi.org/project/agent-config-score/)
[![CI](https://img.shields.io/github/actions/workflow/status/LE0-Lin/AgentConfigScore/ci.yml?style=flat-square&label=CI)](https://github.com/LE0-Lin/AgentConfigScore/actions/workflows/ci.yml)

### [Kaggle AI Agent Security — Silver Medal Solution](https://github.com/LE0-Lin/kaggle-ai-agent-security-silver)

**184th of 4,186 teams** in AI Agent Security: Multi-Step Tool Attacks. A budgeted probe–select–expand algorithm searches for replayable tool-use failures using exported execution traces. The repository includes the evaluated notebook, a technical walkthrough, and offline contract tests.

[Official certificate](https://www.kaggle.com/certification/competitions/leolin05/ai-agent-security-multi-step-tool-attacks) · [Method](https://github.com/LE0-Lin/kaggle-ai-agent-security-silver/blob/main/docs/solution-walkthrough.md) · [Reproduction and scope](https://github.com/LE0-Lin/kaggle-ai-agent-security-silver/blob/main/docs/reproducibility.md)

## Selected merged contributions

| Project | Change |
| --- | --- |
| Hugging Face Transformers | [Rebuild Phi3 LongRoPE caches at the context boundary](https://github.com/huggingface/transformers/pull/49361). |
| ONNX | [Handle incompatible Resize inputs during opset 12→13 conversion](https://github.com/onnx/onnx/pull/8538), with Python and C++ regression tests. |
| Apache Airflow | [Preserve OpenSearch Serverless hook configuration across deferred execution](https://github.com/apache/airflow/pull/72472). |
| MLflow | [Make evaluation-dataset hashing stable for list-valued targets and predictions](https://github.com/mlflow/mlflow/pull/26433). |
| Microsoft Agent Framework Durable Extension | [Fail workflows explicitly when the superstep limit is exceeded](https://github.com/microsoft/agent-framework-durable-extension/pull/84). |

For Microsoft PyRIT, my [StringJoin converter diagnosis and reproduction](https://github.com/microsoft/PyRIT/issues/2973) were credited in the [merged fix](https://github.com/microsoft/PyRIT/pull/2976), with [co-author credit](https://github.com/microsoft/PyRIT/commit/4659ebe553f8b491356669ba451139d6787add8c).

[More upstream work and completion records](docs/upstream-work.md)

## Background

- **Tencent Rhino-Bird 2026 — Issue Top 3.** Completed four open-source practice tasks across OpenTenBase and OpenCloudOS. [Task records](docs/upstream-work.md) · [Practice certificate](assets/credentials/tencent-rhino-bird-2026-open-source-practice.pdf) · [Course certificate](assets/credentials/tencent-rhino-bird-2026-course-completion.pdf).
- I also build academic and personal backend systems with Python, Java/Spring, TypeScript, SQL, and Docker.

<details>
<summary>Contribution activity</summary>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LE0-Lin/LE0-Lin/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LE0-Lin/LE0-Lin/output/github-contribution-grid-snake.svg" />
  <img alt="LE0-Lin contribution grid snake animation" src="https://raw.githubusercontent.com/LE0-Lin/LE0-Lin/output/github-contribution-grid-snake.svg" />
</picture>

</details>
