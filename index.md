---
layout: default
---

<h1 style="white-space: nowrap;">Embodied Agent Interface Challenge @ NeurIPS 2025</h1>

Welcome to the **Embodied Agent Interface (EAI) Challenge**, a NeurIPS 2025 competition that introduces a unified benchmarking framework for evaluating **Large Language Models (LLMs)** in **embodied decision-making tasks**. This competition aims to foster reproducible research and rigorous analysis in embodied AI, bridging the gap between language modeling and robotic planning.

## 📣 Announcements
- **December 7, 2025** - We are excited to announce the winners of the EAI Challenge @ NeurIPS 2025! Congratulations to AxisTilted2 (1st Place), SingaX (2nd Place), CtrlAct (3rd Place), and nju-lamda12 (Most Innovative Approach)! Thank you to all participants for your hard work and dedication!
- **November 3, 2025** - The final evaluation phase officially starts at 12:00AM UTC-0! Please follow the instructions in the updated [Participate page](participate) and [Technical Report](technical_report) page to submit your final model outputs and technical report before the deadline on December 1, 2025. Please use the latest [Starter Kit](https://drive.google.com/file/d/1d-SfGfp109NjRVhY8tFWrNu_KyWpLJbB/view?usp=sharing) to prepare your submission. Good luck to all participants!
- **September 1, 2025** - We are thrilled to announce that the [BEHAVIOR Challenge](https://behavior.stanford.edu/challenge/overview.html) is joining forces with the Embodied Agent Interface Challenge at this year's NeurIPS Competition Track. Two challenges, one stage — bringing richer benchmarks, diverse tasks, and a united embodied AI community!
- **August 15, 2025** - The EAI Challenge officially kicks off at 12:00 PM (CDT)! We are thrilled to welcome all participants and can’t wait to see your innovative solutions.
- **August 2, 2025** - Due to the recent NeurIPS rebuttal period and AAAI submissions, our organizing team has decided to postpone the official launch of the EAI Challenge to August 15 to ensure an optimal participation experience. We greatly appreciate everyone’s patience!
- **June 30, 2025** - The beta test for our competition platform, Eval AI, is now underway! Get ready for the official launch and public registration in late July or early August. Please stay tuned for more updates!
- **May 25, 2025** - We are thrilled to announce that our Embodied Agent Interface Challenge has been officially accepted by the NeurIPS 2025 Competition Track! Get ready for an amazing event!
- **May 16, 2025** - A huge thank you to Adobe Research for their generous $1000 in support for our challenge! This contribution is invaluable to our community.
- **May 1, 2025** - We are so excited to have secured $4000 in support from AIX! This will greatly help in making the EAI Challenge a huge success.


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

## 📅 Timeline

| Phase                  | Dates (2025)          |
|------------------------|-----------------------|
| Beta Testing           | July                  |
| Competition Launch     | August                |
| Development Phase      | August – Early November |
| Final Evaluation       | Early November - Early December |
| NeurIPS 2025 Competition Track In-Person Event | Early December        |


## 📌 How to Participate

- Register via [EvalAI](https://eval.ai/web/challenges/challenge-page/2621/overview)
- Follow instructions in the [Participate page](participate)
- Submit your model's outputs for evaluation
- Track your performance on the [Public Leaderboard](https://eval.ai/web/challenges/challenge-page/2621/leaderboard)
- Submit your technical report to the [OpenReview submission portal](https://openreview.net/group?id=NeurIPS.cc/2025/Workshop/FMEA)

## 📣 Stay Connected

- 🐛 File issues on our [GitHub](https://github.com/embodied-agent-interface/embodied-agent-interface)
- 📢 Join our [Slack](https://join.slack.com/t/eaichallengen-xzk8506/shared_invite/zt-3cm0dms1t-tvylNsamaZQgC03k0kBB9g) for discussions and updates
- 📧 Contact us at: `TianweiBao@u.northwestern.edu`

**Let’s build the future of intelligent embodied agents — together.**
