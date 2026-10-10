<div align="center">

# Zhibo Lin

**Computer Science @ Southwest University · Reliable AI & Software Systems**

Transformers, ONNX & MLflow contributor · AgentConfigScore creator · Kaggle Silver Medalist

[Contribution portfolio](CONTRIBUTIONS.md) · [Merged upstream PRs](https://github.com/search?q=is%3Apr+is%3Amerged+author%3ALE0-Lin+-user%3ALE0-Lin+-repo%3AOpenTenBase%2FOpenTenBase&type=pullrequests) · [LinkedIn](https://www.linkedin.com/in/zhibo-lin/) · [Email](mailto:zhibo.lin@outlook.com)

</div>

I work on the reliability of AI and software systems: inference and cache correctness, reproducible evaluation, durable agent workflows, and developer tooling. My contributions span Python, C#/.NET, C++, TypeScript, and Linux tooling.

## Selected upstream contributions

As of **October 10, 2026**, I have **16 merged pull requests across 9 upstream repositories**, plus a separate merged co-authored contribution to PyRIT. The links below point to accepted work; [my portfolio](CONTRIBUTIONS.md) also records proposals under review.

| Project | Accepted contribution |
| --- | --- |
| **[Hugging Face Transformers](https://github.com/huggingface/transformers)** | Three correctness fixes: [watermark repeated-ngram statistics](https://github.com/huggingface/transformers/pull/49315), [Phi3 LongRoPE cache rebuilding at the context boundary](https://github.com/huggingface/transformers/pull/49361), and [quantized-cache flushing for multi-token updates](https://github.com/huggingface/transformers/pull/49418). |
| **[ONNX](https://github.com/onnx/onnx)** | [Resize opset 12→13 conversion](https://github.com/onnx/onnx/pull/8538): reject a removed coordinate mode and handle incompatible inputs while preserving shared tensors. |
| **[MLflow](https://github.com/mlflow/mlflow)** | [Stable evaluation-dataset hashing](https://github.com/mlflow/mlflow/pull/26433) for list-valued targets and predictions, with regression coverage for repeatability and distinct content. |
| **[Microsoft Agent Framework Durable Extension](https://github.com/microsoft/agent-framework-durable-extension)** | [Fail workflows at the configured superstep limit](https://github.com/microsoft/agent-framework-durable-extension/pull/84), instead of returning successful partial results. |
| **[Apache Airflow](https://github.com/apache/airflow)** | Three merged patches: [preserve AWS configuration across deferred execution](https://github.com/apache/airflow/pull/72472), [Vertex AI pipeline reserved IP ranges](https://github.com/apache/airflow/pull/72560), and [Helm SSH host-verification warnings](https://github.com/apache/airflow/pull/71883). |
| **[.NET Runtime](https://github.com/dotnet/runtime)** | [ProcessArchitecture metadata for ReadyToRun inlining](https://github.com/dotnet/runtime/pull/132601) and [remove forced inlining from Span&lt;T&gt;.ToArray](https://github.com/dotnet/runtime/pull/132635). |

Further merged work includes [Apache Fineract's backoffice UI](https://github.com/apache/fineract-backoffice-ui/pull/481), [HiveMind's LangGraph message and checkpoint handling](https://github.com/Emiyaaaaa/HiveMind/pull/82), and [PowerToys Command Palette command identity](https://github.com/microsoft/PowerToys/pull/50047). My PyRIT [bug report and reproduction](https://github.com/microsoft/PyRIT/issues/2973) were credited in the [merged StringJoin fix](https://github.com/microsoft/PyRIT/pull/2976); its [merge commit](https://github.com/microsoft/PyRIT/commit/4659ebe553f8b491356669ba451139d6787add8c) retains my co-author credit.

## Projects I maintain

### [AgentConfigScore](https://github.com/LE0-Lin/AgentConfigScore)

A deterministic regression gate for AI coding-agent instructions, including `AGENTS.md`, `CLAUDE.md`, Cursor, Copilot, and Gemini files. It compares changes with a Git baseline, preserves baseline policy so a PR cannot weaken its own checks, and produces line-addressable findings, SARIF, and GitHub Actions results.

[![PyPI](https://img.shields.io/pypi/v/agent-config-score?style=flat-square&label=PyPI)](https://pypi.org/project/agent-config-score/)
[![Stars](https://img.shields.io/github/stars/LE0-Lin/AgentConfigScore?style=flat-square&label=Stars)](https://github.com/LE0-Lin/AgentConfigScore/stargazers)
[![CI](https://img.shields.io/github/actions/workflow/status/LE0-Lin/AgentConfigScore/ci.yml?style=flat-square&label=CI)](https://github.com/LE0-Lin/AgentConfigScore/actions/workflows/ci.yml)

The project includes a CLI, reusable GitHub Action, release validation, cross-platform checks, and reproducible benchmarks. Its documented evaluation limits remain explicit; comparative accuracy against AI review has not been established.

### [Kaggle AI Agent Security — Silver Medal Solution](https://github.com/LE0-Lin/kaggle-ai-agent-security-silver)

An open-source competition solution that uses runtime-adaptive probing and tool traces to search for replayable failures in tool-using agents. It finished **184th of 4,186 teams (top 4.4%)** in **AI Agent Security — Multi-Step Tool Attacks** and earned a **[Kaggle Competition Silver Medal](https://www.kaggle.com/certification/competitions/leolin05/ai-agent-security-multi-step-tool-attacks)**.

The MIT-licensed release includes the evaluated notebook, technical walkthrough, reproducibility records, offline contract tests, and CI. The result describes the competition sandbox and scoring rules.

## OpenCloudOS & recognition

Through the **Tencent Rhino-Bird Open Source Program**, I completed two OpenCloudOS tasks that the community marked **completed and awarded**:

- **[Parallel chroot package testing](https://gitee.com/opencloudos-testing/yum-ci-pkg-test/pulls/10)** — bounded concurrency, per-package isolation, timeouts, process and mount cleanup, and auditable reports. [Completion record](https://gitee.com/OpenCloudOS/contributor_rhino-bird/issues/IJV5MW#note_50748142).
- **[OpenCloudOS Security Skill](https://gitee.com/OpenCloudOS/contributor_rhino-bird/pulls/86)** — deterministic command prechecks, confirmation bound to command fingerprints, and OpenClaw/Hermes integration. [Completion record](https://gitee.com/OpenCloudOS/contributor_rhino-bird/issues/IJV0LW#note_50748260).

The two Gitee PRs remain open as of the snapshot date; program completion is recorded separately from upstream merge status.

I received **Issue Top 3 recognition**, an [Open Source Practice Certificate](assets/credentials/tencent-rhino-bird-2026-open-source-practice.pdf), and an [Open Source Course Completion Certificate](assets/credentials/tencent-rhino-bird-2026-course-completion.pdf). I am also a university scholarship recipient, ranked in the **top 20%** of my Computer Science cohort, with **TOEFL iBT 5.0/6.0 (CEFR C1)**.

## About

I am a Computer Science undergraduate at **Southwest University**, preparing for graduate study in the United States. I am interested in how AI systems can be evaluated, integrated, and operated reliably, from model inference to agent orchestration and data infrastructure.

My broader engineering work includes Java/Spring backends, TypeScript/React and Vue applications, SQL databases, Docker, automated testing, and CI/CD. Earlier public projects include a [health-data analytics system](https://github.com/LE0-Lin/health_bigdata_system_v4) and a [Java/Vue course-management system](https://github.com/LE0-Lin/SWUSmartCourseManagement).

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LE0-Lin/LE0-Lin/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LE0-Lin/LE0-Lin/output/github-contribution-grid-snake.svg" />
  <img alt="LE0-Lin contribution grid snake animation" src="https://raw.githubusercontent.com/LE0-Lin/LE0-Lin/output/github-contribution-grid-snake.svg" />
</picture>
