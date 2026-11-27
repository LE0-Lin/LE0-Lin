<div align="center">

# Zhibo Lin

**CS @ Southwest University · AI Agents, Multimodal & Distributed Systems**

Kaggle Silver Medalist (Top 4.4%) · Upstream Open-Source Contributor · TOEFL iBT 5.0/6.0 (CEFR C1)

[Open-Source PRs](https://github.com/search?q=is%3Apr+author%3ALE0-Lin&type=pullrequests) · [Kaggle Certificate](https://www.kaggle.com/certification/competitions/leolin05/ai-agent-security-multi-step-tool-attacks) · [LinkedIn](https://www.linkedin.com/in/zhibo-lin/) · [zhibo.lin@outlook.com](mailto:zhibo.lin@outlook.com)

</div>

---

I am a Computer Science undergraduate at **Southwest University** preparing for graduate study in the United States. My research and engineering span **agentic multimodal perception**, **temporal video understanding**, **governed agent runtime & memory systems**, and **production open-source infrastructure**.

## Highlights

- **Research Experience** — Research Assistant across **Harvard University** (agentic endoscopic video segmentation & cost-aware tracking recovery), **Wuhan University** (boundary-guided temporal action localization with VideoMAE v2), and **Southwest University** (distributed coding-agent runtime & Kubernetes/Kueue control plane).
- **Kaggle Competition Silver Medal** — Ranked **184th of 4,186 teams (Top 4.4%)** in [AI Agent Security: Multi-Step Tool Attacks](https://www.kaggle.com/certification/competitions/leolin05/ai-agent-security-multi-step-tool-attacks), co-hosted by **OpenAI, Google, and IEEE**.
- **Active Upstream Contributor** — Authored **16+ merged pull requests** across **Hugging Face Transformers**, **ONNX**, **MLflow**, **.NET Runtime**, **Apache Airflow**, **Microsoft Agent Framework Durable Extension**, **Microsoft PowerToys**, **Apache Fineract**, and **HiveMind**, plus a credited co-authored fix in **Microsoft PyRIT**.
- **Tencent Rhino-Bird Open Source Program — Issue Top 3 & Official Honor Roll** — Completed four upstream tasks across OpenTenBase and OpenCloudOS, earning the [Open Source Practice Certificate](assets/credentials/tencent-rhino-bird-2026-open-source-practice.pdf) and [Course Completion Certificate](assets/credentials/tencent-rhino-bird-2026-course-completion.pdf).
- **Academic Honors** — University-Level Scholarship recipient; **Class Rank Top 15%** in Computer Science at Southwest University.

## Featured Repositories

| Project | Focus & Verification |
|---|---|
| **[AgentConfigScore](https://github.com/LE0-Lin/AgentConfigScore)**<br>[![PyPI](https://img.shields.io/pypi/v/agent-config-score?style=flat-square&label=PyPI)](https://pypi.org/project/agent-config-score/) [![Stars](https://img.shields.io/github/stars/LE0-Lin/AgentConfigScore?style=flat-square&label=Stars)](https://github.com/LE0-Lin/AgentConfigScore/stargazers) [![CI](https://img.shields.io/github/actions/workflow/status/LE0-Lin/AgentConfigScore/ci.yml?style=flat-square&label=CI)](https://github.com/LE0-Lin/AgentConfigScore/actions/workflows/ci.yml) | Dependency-free static analyzer and baseline-governed CI regression gate for `AGENTS.md`, `CLAUDE.md`, Cursor, Copilot, and Gemini instructions—detecting unsafe commands, exposed credentials, broken paths, and directive polarity flips with JSON/Markdown/SARIF reporting. |
| **[Governed Memory](https://github.com/LE0-Lin/governed-memory)**<br>[![Release](https://img.shields.io/github/v/release/LE0-Lin/governed-memory?style=flat-square&label=Release)](https://github.com/LE0-Lin/governed-memory/releases/latest) [![CI](https://img.shields.io/github/actions/workflow/status/LE0-Lin/governed-memory/ci.yml?style=flat-square&label=CI)](https://github.com/LE0-Lin/governed-memory/actions/workflows/ci.yml) | Approval-gated bitemporal evidence memory for coding agents in Python and Rust, combining PostgreSQL ledger authority, Graphiti/Neo4j candidate projection, OpenFGA/OPA governance, OpenLineage tracking, and stdio MCP retrieval. |
| **[kaggle-ai-agent-security-silver](https://github.com/LE0-Lin/kaggle-ai-agent-security-silver)**<br>[![Medal](https://img.shields.io/badge/Kaggle-Silver%20Medal-C0C0C0?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/certification/competitions/leolin05/ai-agent-security-multi-step-tool-attacks) [![CI](https://img.shields.io/github/actions/workflow/status/LE0-Lin/kaggle-ai-agent-security-silver/ci.yml?style=flat-square&label=CI)](https://github.com/LE0-Lin/kaggle-ai-agent-security-silver/actions/workflows/ci.yml) | Silver Medal solution (**184 / 4,186**) for *AI Agent Security: Multi-Step Tool Attacks* (OpenAI · Google · IEEE): runtime-adaptive black-box red-teaming search with execution-trace verification, model-specific hop budgets, and 2,000-cell deterministic replay. |
| **[RepoPlay](https://github.com/LE0-Lin/RepoPlay)**<br>[![CI](https://img.shields.io/github/actions/workflow/status/LE0-Lin/RepoPlay/ci.yml?style=flat-square&label=CI)](https://github.com/LE0-Lin/RepoPlay/actions/workflows/ci.yml) ![TypeScript](https://img.shields.io/badge/TypeScript-Next.js%2016-3178C6?style=flat-square) | Commit-pinned interactive codebase walkthrough player with Git-blob SHA-1 span verification, bounded zero-execution GitHub tree ingestion, and portable `.tour.json` validation. |

## Selected Upstream Contributions

- **Hugging Face Transformers** — Merged fixes for [watermark repeated-ngram statistics](https://github.com/huggingface/transformers/pull/49315), [Phi-3 LongRoPE KV-cache rebuilding at the context boundary](https://github.com/huggingface/transformers/pull/49361), and [quantized-cache residual flushing on multi-token updates](https://github.com/huggingface/transformers/pull/49418).
- **ONNX** — Merged [schema-safe Resize opset 12→13 version converter adapter](https://github.com/onnx/onnx/pull/8538) in C++/Python with 40 regression scenarios.
- **.NET Runtime** — Merged [ReadyToRun `NonVersionable` process-architecture metadata](https://github.com/dotnet/runtime/pull/132601) and [RyuJIT `Span<T>.ToArray` inlining heuristic alignment](https://github.com/dotnet/runtime/pull/132635).
- **Apache Airflow** — Merged [AWS OpenSearch Serverless configuration preservation across deferred triggers](https://github.com/apache/airflow/pull/72472), [Google Vertex AI reserved VPC IP-range propagation](https://github.com/apache/airflow/pull/72560), and [Helm chart SSH host-verification safety warnings](https://github.com/apache/airflow/pull/71883).
- **MLflow** — Merged [deterministic evaluation-dataset hashing for list-valued targets and predictions](https://github.com/mlflow/mlflow/pull/26433).
- **Microsoft Agent Framework Durable Extension** — Merged [configurable `MaxSupersteps` exhaustion failure semantics](https://github.com/microsoft/agent-framework-durable-extension/pull/84) preventing unfinished cyclic workflows from reporting success.
- **Microsoft PyRIT** — Authored [StringJoinConverter registry identity collision diagnosis and reproduction](https://github.com/microsoft/PyRIT/issues/2973), credited in the [merged fix](https://github.com/microsoft/PyRIT/pull/2976) and [co-authored test commit](https://github.com/microsoft/PyRIT/commit/4659ebe553f8b491356669ba451139d6787add8c).
- **Microsoft PowerToys** — Merged [deterministic Command Palette fallback command IDs](https://github.com/microsoft/PowerToys/pull/50047) with unit-test coverage across 64 parent commands.
- **Apache Fineract** — Merged [maker–checker rejection audit preservation](https://github.com/apache/fineract-backoffice-ui/pull/415), [multi-format loan interest-pause editing](https://github.com/apache/fineract-backoffice-ui/pull/481), and [Vitest test-runner migration](https://github.com/apache/fineract-backoffice-ui/pull/413).
- **HiveMind** — Merged [decoupled message-history persistence and LangGraph checkpoint recovery](https://github.com/Emiyaaaaa/HiveMind/pull/82).
- **[Tencent Rhino-Bird 2026](https://opensource.tencent.com/summer-of-code/)** — Completed OpenTenBase ([Issue #199](https://github.com/OpenTenBase/OpenTenBase/issues/199#issuecomment-5191710626) / [PR #253](https://github.com/OpenTenBase/OpenTenBase/pull/253), [Issue #200](https://github.com/OpenTenBase/OpenTenBase/issues/200#issuecomment-5191814102) / [PR #254](https://github.com/OpenTenBase/OpenTenBase/pull/254)) and OpenCloudOS ([PR !86](https://gitee.com/OpenCloudOS/contributor_rhino-bird/pulls/86) · [record](https://gitee.com/OpenCloudOS/contributor_rhino-bird/issues/IJV0LW#note_50748260), [PR !10](https://gitee.com/opencloudos-testing/yum-ci-pkg-test/pulls/10) · [record](https://gitee.com/OpenCloudOS/contributor_rhino-bird/issues/IJV5MW#note_50748142)).
