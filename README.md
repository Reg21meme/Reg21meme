<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0369A1,50:0EA5E9,100:38BDF8&height=210&section=header&text=Aarogya%20Regmi&fontSize=54&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=CS%20%2B%20Statistics%20%40%20Harvard%20%7C%20ML%20%26%20Systems%20Engineer&descSize=18&descAlignY=58" />

<a href="https://github.com/Reg21meme">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=720&height=45&lines=CS+%2B+Statistics+%40+Harvard;Building+ML+systems+from+scratch;Low-latency+C%2B%2B+meets+deep+RL;Open+to+SWE+%26+ML+internships" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Harvard%20University-Computer%20Science%20%26%20Statistics-0EA5E9?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MIT-Cross--Registration-38BDF8?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Class%20of-2029-0284C7?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Location-Cambridge%2C%20MA-0EA5E9?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0D1117" />

<br/><br/>

<a href="https://linkedin.com/in/aarogya-r">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>
<a href="mailto:aregmi@college.harvard.edu">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://github.com/Reg21meme">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Reg21meme&style=for-the-badge&color=0EA5E9&label=PROFILE+VIEWS&labelColor=0D1117" />
<img src="https://img.shields.io/github/followers/Reg21meme?style=for-the-badge&logo=github&color=0284C7&labelColor=0D1117&label=FOLLOWERS" />
<img src="https://img.shields.io/github/stars/Reg21meme/microstructure-lab?style=for-the-badge&logo=github&color=38BDF8&labelColor=0D1117&label=STARS" />

</div>

---

## About

I'm a Computer Science & Statistics student at **Harvard University**, cross-registered at **MIT** for machine learning, with a focus on building systems where performance actually matters — from low-latency C++ engines to deep reinforcement learning agents trained from scratch.

My interests sit at the intersection of **machine learning**, **high-performance systems**, and **quantitative engineering**. I like taking a problem down to its fundamentals, building it end to end, and measuring it honestly — whether that's nanosecond-level execution latency, Elo ratings across hundreds of training generations, or the real gap between a model's ideal and realistic behavior.

- Building ML systems and low-latency tooling from the ground up
- Deep interest in reinforcement learning, distributed training, and MLOps
- Comfortable across the stack — C++ engines, PyTorch models, and full-stack web apps
- Driven by correctness, performance, and measurable results

**Open To** — Software Engineering & ML internships · Research opportunities · Open source collaboration

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=cpp,py,java,ts,bash&theme=dark" />

**Machine Learning &amp; Data**

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />

**Web &amp; Backend**

<img src="https://skillicons.dev/icons?i=nextjs,nodejs,django,postgres&theme=dark" />

**Developer Tools**

<img src="https://skillicons.dev/icons?i=git,githubactions,docker,linux,vscode&theme=dark" />

</div>

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|--------|:-----------:|---------|
| Reinforcement Learning | ●●●●○ | AlphaZero-style MCTS/PUCT, self-play, policy-value networks |
| Machine Learning | ●●●○○ | Feature engineering, model training &amp; validation (MIT 6.3900) |
| Distributed Training &amp; MLOps | ●●●○○ | Ray-based self-play, MLflow tracking, Prometheus/Grafana monitoring |
| Data &amp; Feature Engineering | ●●●●○ | Large-scale time-series pipelines with Pandas &amp; NumPy |
| High-Performance Computing | ●●●○○ | Zero-allocation C++, Pybind bridges, latency-critical design |

---

## Featured Projects

<details>
<summary><b>Microstructure Lab — High-Performance Order-Book &amp; ML Execution Engine</b></summary>

<br/>

A C++ order-book replay and execution engine paired with an ML feature pipeline, built to study market microstructure and the gap between idealized and realistic trade execution.

| Aspect | Detail |
|--------|--------|
| **Stack** | C++ · Pybind · Scikit-Learn · NumPy · Pandas · Matplotlib |
| **Scale** | 19.4M tick events replayed · 85,000 time-series feature vectors |
| **Performance** | 34M events/sec · 28.8 ns median latency · zero-allocation critical path |
| **Findings** | Execution simulator revealed a 13x gap between ideal and realistic outcomes |
| **Repository** | [View Source →](https://github.com/Reg21meme/microstructure-lab) |

Built a zero-allocation C++ engine for order-book replay, then bridged it to Python via Pybind to model real-world fees, latency, and queue behavior. An accompanying ML feature pipeline processes tens of thousands of time-series vectors for model training and validation.

</details>

<details>
<summary><b>ConnectZero — AlphaZero-Style Deep Reinforcement Learning Agent</b></summary>

<br/>

A Connect Four agent trained entirely from self-play using an AlphaZero-style approach, with distributed training infrastructure and full experiment tracking.

| Aspect | Detail |
|--------|--------|
| **Stack** | PyTorch · Ray · Docker · Prometheus · Grafana · MLflow |
| **Scale** | 600+ training generations · distributed across 4 Ray workers |
| **Performance** | 100% win rate over 100 games · Elo 1523 · self-play scaled 1.52 → 3.08 games/sec |
| **Approach** | MCTS/PUCT search, policy-value training, replay buffering, Elo eval, checkpoint recovery |
| **Repository** | [View Source →](https://github.com/Reg21meme/connectzero) |

Implemented the full AlphaZero loop from scratch — Monte Carlo Tree Search with PUCT, a policy-value network, and self-play data generation — then scaled it with Ray while tracking queue depth and learner utilization through Prometheus and Grafana.

</details>

<details>
<summary><b>TransitPulse — Real-Time MBTA Transit Tracker &amp; Reliability Pipeline</b></summary>

<br/>

A live transit tracking platform that streams real-time MBTA vehicle positions and measures arrival-prediction reliability at scale.

| Aspect | Detail |
|--------|--------|
| **Stack** | Next.js · Django · Node.js · PostgreSQL · Docker |
| **Scale** | 1.5M+ snapshots ingested · 21,000+ arrivals measured · 7 subway lines |
| **Performance** | Live positions for 80 trains updated every 2 seconds via WebSockets |
| **Reliability** | 50.5% of predicted arrivals landed within 2 minutes of actual |
| **Repository** | [View Source →](https://github.com/Reg21meme/transitpulse) |

Built a Node.js WebSocket service streaming live vehicle positions to a Next.js frontend, backed by a Django/PostgreSQL pipeline that ingests millions of position snapshots and evaluates prediction accuracy across tens of thousands of arrivals.

</details>

---

## Education

### Harvard University
`September 2025 — May 2029` · Cambridge, MA

**B.A. in Computer Science &amp; Statistics**

`Data Structures & Algorithms (CS 1240)` `Linear Algebra (MATH 22A)` `Data Science (CS 1090A/B)` `Probability (STAT 110)`

### Massachusetts Institute of Technology
`September 2026 — December 2026` · Cambridge, MA

**Cross-Registration**

`Introduction to Machine Learning (6.3900)`

---

## GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Reg21meme&show_icons=true&count_private=true&hide_border=true&title_color=38BDF8&icon_color=0EA5E9&text_color=C9D1D9&bg_color=0D1117" />
<img width="49%" src="https://streak-stats.demolab.com/?user=Reg21meme&hide_border=true&background=0D1117&stroke=0EA5E9&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E" />

<img width="60%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Reg21meme&layout=compact&hide_border=true&title_color=38BDF8&text_color=C9D1D9&bg_color=0D1117&langs_count=8" />

</div>

---

## GitHub Trophies

<div align="center">

<img width="100%" src="https://github-profile-trophy.vercel.app/?username=Reg21meme&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" />

</div>

---

## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Reg21meme&bg_color=0D1117&color=38BDF8&line=0EA5E9&point=FFFFFF&area=true&hide_border=true" />

</div>

---

## Contribution Graph

<div align="center">

<img width="100%" src="https://raw.githubusercontent.com/Reg21meme/Reg21meme/output/snake.svg" />

</div>

---

## Current Focus

```yaml
current_focus:
  learning:
    - Machine Learning (MIT 6.3900)
    - Probability & statistical modeling (STAT 110)
  building:
    - Low-latency systems & market microstructure tooling
    - Deep reinforcement learning agents
  exploring:
    - Distributed training & MLOps pipelines
    - Quantitative research & execution modeling
  open_to:
    - Software Engineering / ML internships
    - Research & open source collaboration
```

---

## Connect

<div align="center">

<a href="mailto:aregmi@college.harvard.edu">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://linkedin.com/in/aarogya-r">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://github.com/Reg21meme">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
</a>

</div>

---

<div align="center">

> *"Fast, correct, and built to scale — one system at a time."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,50:0EA5E9,100:0369A1&height=120&section=footer" />

</div>
