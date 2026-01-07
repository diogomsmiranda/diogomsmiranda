<div align="center">

<!-- Header / Intro -->
<h1 align="left">Diogo Miranda</h1>
<h3 align="left">Master’s student @ Instituto Superior Técnico (Lisbon) • ML / Model Merging • Portugal 🇵🇹</h3>

<!-- Links -->
<p align="left">
  <a href="https://www.linkedin.com/in/diogomsmiranda/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:diogomsmiranda@tecnico.ulisboa.pt"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

</div>

---

## About Me

- I'm **22** years old
- Final year **Master’s in Computer Science** @ **Instituto Superior Técnico (Lisbon)**
- Research: **Model Merging**, specifically **On-Policy Distillation** solutions on **Knowledge Distillation-based fusion**
- Currently passionate with the full model creation pipeline: **data → training -> post-training → evaluation → deployment → monitoring**
- Based in **Portugal** 🇵🇹

---

## Research Snapshot

**Current theme:** _Moving Model Fusion from Static Imitation to Dynamic Exploration_

I am investigating **On-Policy Multi-Teacher Fusion**, a framework designed to fix the "exposure bias" limitation in current methods like FuseLLM and InfiFusion. Instead of training a student to passively mimic static teacher logits (Off-Policy), I force the student to generate its own rollouts and receive dynamic feedback from an ensemble of experts.

**Key Hypotheses:**
* **Dynamic vs. Static:** Training on student-induced distributions (On-Policy) allows the model to learn error-recovery strategies that static distillation misses.
* **Consensus Stability:** Using **Generalized Jensen-Shannon Divergence ($JS_\pi$)** creates a bounded, symmetric loss landscape, preventing gradient explosions when the student explores "long-tail" trajectories.
* **Expert Allocation:** Applying **Max-Margin Ensemble Aggregation** enables the student to dynamically attend to the most confident domain expert (e.g., Math vs. Code teacher) for every token it generates.

**Keywords:** `multi-teacher distillation` • `on-policy learning` • `jensen-shannon divergence` • `model fusion` • `max-margin aggregation`

> Currently reading through **[this](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications)** repository for Model Merging / Model Fusion literature.

---

## What I’m Working On

* **Core Algorithms:**
    * Implementing **Generalized Jensen-Shannon Divergence** to replace standard Reverse KL for stable on-policy updates.
    * Building **Max-Margin Aggregation** kernels to dynamically re-weight teacher's confidence based on real-time confidence scores.
* **Baselines & Replication:**
    * **Track A (General):** Replicating the **FuseLLM** setup (Llama-2/MPT/OpenLLaMA) to benchmark general knowledge transfer.
    * **Track B (Reasoning):** Replicating the **InfiFusion** setup (Qwen-Math/Qwen-Coder/Mistral) to test expert routing in complex reasoning tasks.

## Tech Stack

### ML / Data
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

### .NET / Backend
![C%23](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=flat&logo=dotnet&logoColor=white)

### Web Dev
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

### DevOps / Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### Languages (General)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C%2B%2B](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)

---

## Featured Projects
<!-- Pin your best work here. Replace links and descriptions -->
- 🧊 **[CUBOS](https://github.com/GameDevTecnico/cubos)** — It is open source and free to use game engine for any purpose. Written in modern C++ (20) and with data-oriented design in mind, its goal is to be both performant and highly flexible.  
- 🧪 **[LEMAC-Website](https://github.com/SysAdmin-IST-DEM/lemac-website)** — Website for the laboratory LEMAC (Computer Assisted Mechanical Engineering Laboratory).

## Course Projects

- 💻 **[Operative Systems](https://github.com/diogomsmiranda/SO-proj)** - Operating System's course Project: TécnicoFS, simplified file system in user mode.

---

## (Not so Important)* Github  Stats 📈

<div align="center">

<!-- Streaks -->
<img height="190" src="https://streak-stats.demolab.com?user=diogomsmiranda" />

</div>

## Let’s Connect

If you’re into **model merging**, **distillation**, or **practical ML**, I’d love to chat.

- 💼 LinkedIn: https://www.linkedin.com/in/diogomsmiranda/
- 📫 Email: diogomsmiranda@tecnico.ulisboa.pt

---
