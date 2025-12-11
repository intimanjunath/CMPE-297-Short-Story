# Inside LLM Agents: How AI Workers Plan, Remember, and Act in the Real World — Overview

Repository for the analysis and presentation of the survey  
**“Large Language Model Agent: A Survey on Methodology, Applications and Challenges” (Luo et al., 2025)**.  
This repo collects my written summary, presentation slides, and key takeaways about how LLM agents are built, evaluated, and where they can fail.

---

## Paper Description

The Luo et al. survey looks at **LLM agents** not just as clever chatbots, but as systems that can **observe, plan, act with tools, and learn over time**. Instead of treating the model as the whole application, it decomposes an agent into:

- how we **construct** a single agent (profile, memory, planning, action),
- how agents **collaborate** with each other (centralized, decentralized, hybrid),
- and how agents **evolve** (self-learning, co-evolution, external feedback).

The paper also reviews **benchmarks, metrics, tools, and real-world issues** such as security, privacy, and social impact. Overall, it’s a 2025 snapshot of where LLM agents are today and what’s still missing before we can trust them in real workflows.

<img width="681" height="316" alt="Screenshot 2025-12-10 at 11 27 41 PM" src="https://github.com/user-attachments/assets/e335db2f-7efb-4584-970b-8f003e15d987" />

---

## What I Did in This Project

This project turns that dense survey into a compact “short story” for practitioners:

- Framed LLM agents as a simple **loop**: _observe → plan → act → reflect_.
- Highlighted the four core architecture pieces: **profile, memory, planning, tools**.
- Pulled out what **benchmarks and ablation studies** actually say about performance  
  (e.g., what breaks when you remove memory, tools, or explicit planning).
- Summarized **security, privacy, and social impact** issues for agents that can call real tools.
- Created:
  - a **Medium article**,
  - a **slide deck**,
  - and a **video presentation** explaining these ideas.

---

## Architecture at a Glance

- **Agent Construction**
  - *Profile definition* – role and goals of the agent  
  - *Memory mechanism* – short-term context, long-term skills, retrieval (RAG / graphs)  
  - *Planning capability* – task decomposition, search over plans, feedback loops  
  - *Action execution* – tool APIs, code runners, web/DB access, robots/simulators  

- **Agent Collaboration**
  - *Centralized control* – a coordinator agent delegating tasks  
  - *Decentralized collaboration* – peer agents negotiating and sharing work  
  - *Hybrid architectures* – mixes of manager + specialist agents  

- **Agent Evolution**
  - *Self-learning* – reflection, self-correction, prompt and policy updates  
  - *Multi-agent co-evolution* – agents improving each other via debate or feedback  
  - *External resources* – human feedback, new tools, and updated knowledge bases  

These bullets are my distilled version of the taxonomy figure from the survey.

---

## Read / Watch

- **Medium article**  
  _Inside LLM Agents: How AI Workers Plan, Remember, and Act in the Real World_  
  👉 https://medium.com/@manjunatha.inti/inside-llm-agents-how-ai-workers-plan-remember-and-act-in-the-real-world-c68be59836f1

- **Slides (PDF)**  
  👉 `slides/Inside-LLM-Agents-How-AI-Workers-Plan-Remember-and-Act-in-the-Real-World.pdf`

- **Paper (arXiv PDF)**  
  👉 https://arxiv.org/pdf/2503.21460.pdf

- **YouTube presentation (15+ min)**  
  👉 https://youtu.be/inJkg4Rr39w

- **SlideShare deck**  
  👉 [SlideShare link here](https://www.slideshare.net/slideshow/inside-llm-agents-how-ai-workers-plan-remember-and-act-in-the-real-world-pdf/284592635)

---

## Acknowledgments

All technical claims, diagrams, and taxonomy descriptions are based on:

> **Luo, J. et al. (2025). _Large Language Model Agent: A Survey on Methodology, Applications and Challenges._ arXiv:2503.21460.**

I’m grateful to the authors for providing a comprehensive and up-to-date survey of LLM agent research.

---


> Inti, M. (2025). _Inside LLM Agents: How AI Workers Plan, Remember, and Act in the Real World._ Medium article and accompanying slide deck.
