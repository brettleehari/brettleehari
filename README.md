### Hariprasad Sudharshan

I build AI systems for places where a wrong answer is expensive, and I care most about how we measure whether they can be trusted.

I started in QA in 2008 and have kept the same habit since: find the system-level levers that reduce variance in the output. Today I am a Sr Product Manager for AI & API at 1FINITY (a Fujitsu company), working inside R&D on language models and agents for optical network operations. Most of that work is proprietary. This page is what I build in the open.

#### What I work on

| Area | Project | What it is |
|---|---|---|
| Evaluation | [PairwisePM](https://github.com/brettleehari/PairwisePM) | A mechanical pairwise judge for GenAI product decisions, built to take noise out of LLM-judged comparisons. [Explainer on Hugging Face](https://huggingface.co/spaces/brettleehari/PairwisePM-explained). |
| Agent safety | [agent-crucible](https://github.com/brettleehari/agent-crucible) | An adversarial fitness gate for autonomous agents: a floor of deterministic villains an agent must survive before deployment. A pass means no tripwire sprang, not that the agent is safe. |
| Fine-tuning | [cricketmind](https://github.com/brettleehari/cricketmind) | Nemotron-Mini-4B fine-tuned with QLoRA and response distillation. 29.8% to 67.5% on CricketBench v0.1, a 20-question benchmark I wrote, from about 170 examples and 35 minutes of GPU time. [Model](https://huggingface.co/brettleehari/cricketmind-nemotron-mini) and [dataset](https://huggingface.co/datasets/brettleehari/cricketbench-v1) are on Hugging Face. |
| On-device models | [arivu](https://github.com/brettleehari/arivu) | A language model that runs entirely on a phone (iOS and Android). The model ships inside the app, works offline, and shows what each reply cost in tokens. |
| Inference economics | [tokencalci](https://github.com/brettleehari/tokencalci) | A live-priced planner for self-hosting an open model versus renting it from a neocloud API, with break-even. [Live](https://tokencalci.onrender.com). |
| Code analysis | [grasprepo](https://github.com/brettleehari/grasprepo) | A Tree-sitter engine that surfaces code churn and structural complexity in a repository. [Live](https://grasprepo.onrender.com/). |

I also contribute to NITA (NEST Interactive Toy Arena), an AI toy safety testing platform in the Foundation for Agentic Networks, where my focus is LLM-judge reliability and measuring adversarial scenario coverage.

#### Open source since 2017

My public history has a quiet stretch in the middle, because the work in those years was inside the company.

- **2017.** Part of the team that open-sourced [Warrior Framework](https://github.com/warriorframework/warriorframework), a Python test automation framework, with [10 merged pull requests](https://github.com/warriorframework/warriorframework/pulls?q=is%3Apr+author%3Abrettleehari+is%3Amerged) of my own.
- **2018 to 2024.** Built an internal developer platform at Fujitsu Network Communications for 250+ developers, and the metrics behind it (TAQI, DDF, Merge Conflict Coefficient). The code is proprietary. The public traces are an [InfluxDays 2021 talk demo](https://github.com/pitchdarkdata/InfluxDays2021_Demo) and the paper [The Hidden Cost of Early Branching](https://www.researchgate.net/publication/391274585_The_Hidden_Cost_of_Early_Branching_A_Quantitative_Model_of_Complexity_Effort_and_Risk_in_Parallel_Development).
- **2024.** A merged fix to the Bitbucket loader in [LlamaIndex (#15311)](https://github.com/run-llama/llama_index/pull/15311), after reporting the bug.
- **2024 onwards.** The projects above.

Some of this was done from my second account, [@pitchdarkdata](https://github.com/pitchdarkdata), including the LlamaIndex fix, the InfluxDays demo and [Smart-review](https://github.com/pitchdarkdata/MVP1), an early code review analytics app.

#### Research, patents and talks

- **Papers.** [Right at Diagnosis, Wrong at Action: Can Your Agent Manage a Live Network That Keeps Changing?](https://www.researchgate.net/publication/418214321_Right_at_Diagnosis_Wrong_at_Action_Can_Your_Agent_Manage_a_Live_Network_That_Keeps_Changing) (OFC Demo Zone). Synchronous Forward Propagation of Commits in N Parallel Git Branches, with a [visual companion](https://brettleehari.github.io/SyncForwardProp/). More on [Google Scholar](https://scholar.google.com/citations?hl=en&user=0ifJK1sAAAAJ).
- **Patents.** 3 granted U.S. patents as primary inventor in network protocol design (G.8032 ring protection, MSTP migration, loop prevention). 2 filed on context engineering for network applications.
- **Talks.** AI Engineer NYC 2026, Google DevFest Chennai 2026, AWS User Group Dallas 2026, InfluxDays 2021.
- **Hackathon.** Runner-up as a solo participant at the MIT Media Lab NANDAHack, with a [red-team of the agent coordination layer](https://github.com/brettleehari/nandatown).

#### Elsewhere

[Hugging Face](https://huggingface.co/brettleehari) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=0ifJK1sAAAAJ) · [LinkedIn](https://linkedin.com/in/haripm4ai) · [Personal site](https://brettleehari.github.io/Hari.me/) · [Visual Learning](https://brettleehari.github.io/Visuallearning/), where I explain LLM ideas through analogies
