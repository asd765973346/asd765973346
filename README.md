# 粟泽力 / Zeli Su

## About

I am a master's student in Electronic Information at Minzu University of China and an incoming PhD student at the Data-Centric AI (DCAI) group, Peking University. I am currently looking for research internship opportunities related to LLM post-training, RL for LLMs, and Agent capability construction.

My research focuses on how large language models acquire, improve, and preserve capabilities through post-training. I am interested in reinforcement learning for LLMs, instruction-following robustness, semantic-reward optimization, data and benchmark construction, and Agent capability evaluation. My current focus includes base-model evaluation, Agent CPT, OPD/OPSD distillation, and agentic trajectory synthesis. My recent work studies post-training methods such as GRPO-based semantic reward learning, robustness recovery under distracting instructions, automatic benchmark generation for data-analysis agents, and systematic monitoring of Agent potential in pretraining and midtraining models.

Earlier in my research, I worked extensively on multilingual and low-resource language modeling, including datasets, models, and benchmarks for minority languages in China. I now treat these settings as important testbeds for studying capability expansion, alignment preservation, and post-training reliability.

我是中央民族大学电子信息专业硕士生，即将加入北京大学 Data-Centric AI (DCAI) 课题组攻读博士。目前希望寻找大模型后训练、RL4LLM 与 Agent 能力构建相关的科研实习机会。

我的研究关注大语言模型如何通过后训练获得、提升并保持复杂能力，具体包括 RL for LLM、指令遵循鲁棒性、语义奖励优化、数据与 benchmark 构建，以及 Agent 能力评测。近期重点关注 base-model 评测、Agent CPT、OPD/OPSD 蒸馏和 agentic 轨迹数据合成；近期工作围绕 GRPO 语义奖励强化学习、噪声指令干扰下的鲁棒性恢复、数据分析 Agent benchmark 自动构建，以及 pretrain/midtrain 阶段模型 Agent 潜能监测展开。

早期研究主要集中在多语言与低资源语言建模，包括中国少数民族语言的数据、模型和评测基准建设。现在我更多将这些场景作为研究模型能力扩展、对齐保持与后训练可靠性的实验载体。

## Research Interests

- LLM post-training, RLHF/RLVR, GRPO, and semantic-reward optimization
- Instruction following, robustness, and reliability under noisy or conflicting contexts
- Base-model evaluation, Agent CPT, and Agent capability monitoring
- OPD/OPSD distillation, agentic trajectory synthesis, and automatic benchmark generation
- Multilingual and low-resource capability expansion as post-training testbeds

## Current Experience

- **Data-Centric AI (DCAI) Group, Peking University**, Research Intern / Research Assistant, 2025.09 - Present  
  Working on research and open-source systems related to Data-Centric AI, LLM data systems, Agents, benchmark construction, and AI4Science.

- **Foundation Model Group (Ling), Ant Group**, Research Intern, 2025.10 - Present  
  Working on instruction-following post-training optimization for Ling/Ring foundation models, including failure-mode analysis, training-feedback diagnosis, targeted data construction, and robustness-oriented alignment research.

## Accepted Papers

- **Source-Grounded Semantic Reinforcement Learning for Low-Resource Target-Language Generation**  
  EMNLP 2026 Main, first author. A source-grounded semantic RL framework for reference-free low-resource target-language generation. [[arXiv]](https://arxiv.org/abs/2605.29502)

- **Reinforcement Learning with Semantic Rewards Enables Low-Resource Language Expansion without Alignment Tax**  
  ACL 2026 Findings, first author. A GRPO-based semantic-reward post-training method for capability expansion while preserving general alignment. [[arXiv]](https://arxiv.org/abs/2605.14366)

- **Multilingual Encoder Knows more than You Realize: Shared Weights Pretraining for Extremely Low-Resource Languages**  
  ACL 2025 Main, first author. A shared-weight pretraining framework for adapting multilingual encoders to extremely low-resource generation tasks. [[arXiv]](https://arxiv.org/abs/2502.10852) [[Code/Model]](https://github.com/asd765973346/xlm-swcm)

- **CMHG: A Dataset and Benchmark for Headline Generation of Minority Languages in China**  
  EMNLP 2025 Main, co-first author (advisor first author). A dataset and benchmark for headline generation in Tibetan, Uyghur, and Mongolian. [[arXiv]](https://arxiv.org/abs/2509.09990) [[Dataset]](https://huggingface.co/datasets/KEVVVV/CMHG)

- **FTibSuite: A Comprehensive Resource Suite for Tibetan Vision-Language Modeling**  
  ACL 2026 Findings, co-first and corresponding author. A resource suite for Tibetan vision-language modeling, including data, benchmarks, and baseline models. [[arXiv]](https://arxiv.org/abs/2605.26601)

- **InsightBenchMaker: Towards Generating Evolving and High-Fidelity Benchmarks for Data-Analysis Agents**  
  ACL 2026 Findings, co-first author. An automatic benchmark construction framework for data-analysis agents with heterogeneous data, executable verification, and high-fidelity insight-data alignment.

### Additional Accepted Findings (NLP)

- **SA-Bench: Evaluating Semantic Alignment in LLM-Based Paper Reproduction**  
  EMNLP 2026 Findings, third author. A benchmark for measuring semantic drift between research papers and agent-generated reproduction repositories. [[arXiv]](https://arxiv.org/abs/2608.24252) [[Code]](https://github.com/kernel-14/SA-Bench) [[Dataset]](https://huggingface.co/datasets/kernel-14/SemanticAlign-Bench)

- **ReproAgent: Contract-Guided Paper-to-Code Reproduction**  
  EMNLP 2026 Findings, fifth author. A contract-guided agent framework for preserving paper requirements through planning, code generation, validation, and repair. [[arXiv]](https://arxiv.org/abs/2608.24291) [[Code]](https://github.com/kernel-14/ReproAgent)

- **DataCross: A Unified Benchmark and Agent Framework for Cross-Modal Heterogeneous Data Analysis**  
  EMNLP 2026 Findings, fourth author. A benchmark and collaborative agent framework for insight-driven analysis across structured and visual data sources. [[arXiv]](https://arxiv.org/abs/2601.21403)

## Preprints / Under Review

- **The Curse of Helpfulness: Inverse Scaling Law in Robustness to Distractor Instructions via DistractionIF**  
  A diagnostic benchmark and analysis of instruction-following robustness under distracting pseudo-instructions in reference text, with GRPO-based robustness recovery. [[arXiv]](https://arxiv.org/abs/2605.29491)

- **Base-model Agent-Potential Monitoring: Probing ReAct-like Interaction Ability in Pretrain and Midtrain Models**  
  A framework for monitoring Agent-like interaction ability in base and midtraining models through few-shot reasoning, structured action generation, and real environment interaction.

- **Expert Attention: Routing-Guided Static Pruning for Transformer Encoders**  
  A routing-guided structured pruning method for Transformer encoders. [[arXiv]](https://arxiv.org/abs/2512.20635)

## Open Source

- **Paper2Any**: An open-source system that turns papers, images, and text into editable research figures, technical route diagrams, and presentation materials. I contributed to DrawIO/PPT generation, PPTPolish, and knowledge-enhanced generation modules. [[GitHub]](https://github.com/OpenDCAI/Paper2Any) [![GitHub stars](https://img.shields.io/github/stars/OpenDCAI/Paper2Any?style=social)](https://github.com/OpenDCAI/Paper2Any)

- **Open-NotebookLM**: An open-source document-centered knowledge system supporting semantic retrieval, evidence-grounded QA, AI-assisted note generation, mind maps, slides, podcasts, quizzes, and deep research reports. I contributed to multi-source document ingestion and generation modules for slides, mind maps, DrawIO diagrams, podcasts, quizzes, and deep research reports. [[GitHub]](https://github.com/OpenDCAI/Open-NotebookLM) [![GitHub stars](https://img.shields.io/github/stars/OpenDCAI/Open-NotebookLM?style=social)](https://github.com/OpenDCAI/Open-NotebookLM)

## Contact

- GitHub: [@asd765973346](https://github.com/asd765973346)
- Email: rickamorty@muc.edu.cn
