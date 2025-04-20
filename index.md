---
layout: default
---

<h1 style="white-space: nowrap;">Embodied Agent Interface Challenge @ NeurIPS 2025</h1>

Welcome to the **Embodied Agent Interface (EAI) Challenge**, a NeurIPS 2025 competition that introduces a unified benchmarking framework for evaluating **Large Language Models (LLMs)** in **embodied decision-making tasks**. This competition aims to foster reproducible research and rigorous analysis in embodied AI, bridging the gap between language modeling and robotic planning.

## 🧠 Motivation

Despite increasing interest in using LLMs for robotics and agent reasoning, current evaluations are fragmented and often limited to final task success rates. These approaches fail to reveal specific reasoning failures, limiting scientific understanding and practical progress.

The **Embodied Agent Interface** addresses this gap through a **modular evaluation framework** that standardizes task interfaces and metrics across four core decision-making abilities:

- **Goal Interpretation**  
- **Subgoal Decomposition**  
- **Action Sequencing**  
- **Transition Modeling**

## 🔬 What’s New?

- **Standardized Interface** for embodied reasoning across symbolic and simulation-based tasks.
- **Linear Temporal Logic (LTL)** is used to formally specify both state-based and temporally extended goals.
- **Fine-grained error metrics**, including hallucination rates, precondition violations, and planning logic mismatches.
- Modular benchmarking on two powerful simulation platforms: **BEHAVIOR** and **VirtualHome**.

## 🧪 Benchmark Overview

The benchmark dataset consists of:

- ✅ 338 tasks in **VirtualHome** across 26 categories
- ✅ 100 tasks in **BEHAVIOR** with complex physical goals
- ✅ LTL-annotated goals, symbolic trajectories, and PDDL-style transition models
- ✅ Support for interpretable and reproducible evaluation

All data, annotations, and code will be released through our [GitHub repository](https://github.com/neurips25-eai) and Hugging Face Datasets.

## 🧩 Tasks & Abilities

Participants may compete in one or more of the following modules:

1. **Goal Interpretation**: Translate natural language into formal symbolic goals.
2. **Subgoal Decomposition**: Break down goals into executable substeps.
3. **Action Sequencing**: Generate feasible action trajectories to accomplish goals.
4. **Transition Modeling**: Infer preconditions and effects of symbolic actions.

Each module can be tackled independently, with leaderboards and evaluation scripts provided per module.

## 📊 Evaluation Metrics

We evaluate models on:

- **Symbolic Accuracy** (F1 scores for logic form generation)
- **Trajectory Feasibility** (simulator execution success)
- **Goal Satisfaction** (whether the plan achieves the intended goal)
- **Planner Compatibility** (whether inferred models support planning)

An aggregated **Average Performance** metric summarizes overall model capability across modules.

## 🚀 Baselines & Starter Kit

We provide baseline implementations using open and proprietary LLMs:

- GPT-4o
- Claude 3.5 Sonnet
- Llama 3-70B
- Gemini 1.5 Pro
- Mistral Large

A **comprehensive starter kit** will include:

- Data loaders for BEHAVIOR and VirtualHome
- Evaluation scripts with diagnostic metrics
- Reference code for each module
- Docker support and tutorial notebooks

## 📅 Timeline

| Phase                  | Dates (2025)         |
|------------------------|----------------------|
| Beta Testing           | July                 |
| Competition Launch     | August               |
| Development Phase      | August – Mid-October |
| Final Evaluation       | Mid–Late October     |
| NeurIPS Workshop       | November             |

## 🏆 Awards & Recognition

- Top 3 teams will present at the **NeurIPS 2025 Workshop**
- Co-authorship on the **official competition report**
- **Cash prizes** (pending sponsorship)
- **Travel support** for underrepresented participants

## 📌 How to Participate

- Register via [EvalAI](https://eval.ai/)
- Follow instructions in the [starting kit](https://github.com/neurips25-eai)
- Submit predictions or Docker images
- Track your performance on the public leaderboard

## 📣 Stay Connected

- 💬 Join the community on Discord/Slack (invite link coming soon)
- 🐛 File issues on our [GitHub](https://github.com/neurips25-eai)
- 📧 Contact us at: `TianweiBao@u.northwestern.edu`

**Let’s build the future of intelligent embodied agents — together.**
