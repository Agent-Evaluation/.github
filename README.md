# Multi-Agent Systems Evaluation

Evaluating LLM-based multi-agent systems across planning, consensus, and web navigation domains.

---

## Evaluations

| Status | Benchmark | Domain |
|---|---|---|
| ✅ Done | [`plancraft`](https://github.com/AbhimanyuAryan/plancraft) | Sequential planning |
| 🔄 In Progress | [`web-navigation-eval`](https://github.com/AbhimanyuAryan/web-navigation-eval) | Web navigation & information synthesis |
| 🔄 In Progress | [`ThesisConsensus`](https://github.com/AbhimanyuAryan/ThesisConsensus) | Consensus mechanisms |
| ⏳ Coming Soon | More evaluations | — |

---

### ✅ [`plancraft`](https://github.com/AbhimanyuAryan/plancraft)

Minecraft-based benchmark evaluating **planning in LLM agents** (COLM 2025). Agents craft target items from an initial inventory using move and smelt actions, with an oracle RAG retriever available.

- Multimodal environment (symbolic + image observations), standard Gym API
- Dataset of crafting tasks across varying complexity and recipe types
- Baselines reproduced from [Dagan et al. 2024](https://arxiv.org/abs/2412.21033)

---

### 🔄 [`web-navigation-eval`](https://github.com/AbhimanyuAryan/web-navigation-eval)

Evaluating multi-agent architectures on **web navigation and information synthesis** using the BrowseComp-Plus benchmark (Chen et al. 2025) and the scaling framework from Kim et al. (2025).

- 5 canonical architectures: Single-Agent, Independent, Centralized, Decentralized, Hybrid
- 100 web browsing tasks requiring multi-website information synthesis
- LLM-as-judge evaluation (Qwen3-32B)

---

### 🔄 [`ThesisConsensus`](https://github.com/AbhimanyuAryan/ThesisConsensus)

Evaluating **consensus mechanisms** in heterogeneous multi-agent systems — how autonomous agents with conflicting objectives coordinate decisions reliably.

- 15 specialised agent types, hierarchical coordination layers
- Protocols: adaptive, Byzantine fault-tolerant, privacy-preserving, human-AI hybrid
- Novel metrics: Semantic Consensus Quality (SCQ), Byzantine Resilience Index, Consensus Velocity
