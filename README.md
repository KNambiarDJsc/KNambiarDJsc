# Karthik Nambiar

AI/ML engineer at [Psyflo](https://www.psyflo.com/), a Cornell-based startup. I build tools that make AI systems cheaper to run and easier to trust.

## What I'm building

| Project | What it does |
|---|---|
| [**Ration**](https://github.com/KNambiarDJsc/Ration) | Shows where your Claude Code quota went, and replays your own sessions to find a cheaper auto-compact window. Runs locally and makes no model calls. |
| [**Shrink**](https://github.com/KNambiarDJsc/Shrink) | A local MCP gateway, written in Rust, that compacts verbose JSON tool schemas into dense signatures and cuts discovery tokens by up to 87%. |
| [**Ferret**](https://github.com/KNambiarDJsc/Ferret) | Correctness checks for model training and fine-tuning. Catches what a loss curve hides: a label mask that ignores every token, a LoRA adapter that never attaches, a checkpoint that reloads differently. |
| [**Second Thought**](https://github.com/KNambiarDJsc/second-thought) | Answers whether a model's confidence number means anything: calibration measurement, a dashboard and drift monitoring for typed decisions. |
| [**Jev Reactor**](https://github.com/KNambiarDJsc/Jev-Reactor) | An open-source runtime for real-time typed decisions. The model makes the semantic judgments; ordinary code handles policy, control flow and side effects. |
| [**Meridian**](https://github.com/KNambiarDJsc/meridian-releases) | Compliance intelligence for teams building AI systems, as a CLI and an MCP server. The source is private; the installers are public. |

## Open source

- [**huggingface/Repo2RLEnv**](https://github.com/huggingface/Repo2RLEnv/pulls?q=is%3Apr+author%3AKNambiarDJsc): 10 merged pull requests. Most make it work on Windows (paths, UTF-8 decoding, process handling); one adds task-aware `validate --deep` and `--oracle` checks.
- [**huggingface/OpenEnv**](https://github.com/huggingface/OpenEnv/pull/1203): an open pull request that reports execution budgets in the `tbench2_env` reset observation.

## Also

- [**OmniSearch**](https://github.com/KNambiarDJsc/omnisearch): local-first search over your own files, combining multimodal embeddings, BM25 and reranking.
- [**GO.AI**](https://github.com/KNambiarDJsc/GO_Agents_repo): a multi-agent real-estate intelligence system on LangGraph and FastAPI.

## Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,rust,ts,js,java,cpp,fastapi,django,flask,nodejs,react,nextjs" alt="Python, Rust, TypeScript, JavaScript, Java, C++, FastAPI, Django, Flask, Node.js, React, Next.js" />
</p>
<p align="left">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,postgres,mysql,mongodb,supabase,kafka,docker,aws,gcp" alt="PyTorch, TensorFlow, PostgreSQL, MySQL, MongoDB, Supabase, Kafka, Docker, AWS, Google Cloud" />
</p>

Agents and tooling: LangGraph, CrewAI, Google ADK, Model Context Protocol (MCP).

## Contact

Open to collaborating on ML research, real-time systems and AI infrastructure.

Reach me: **knambiardjs@gmail.com**
