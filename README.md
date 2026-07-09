<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0EA5E9&height=200&section=header&text=Aarogya%20Regmi&fontSize=50&fontColor=FFFFFF&fontAlignY=40&animation=fadeIn" /><br/><br/>
<a href="https://github.com/Reg21meme"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=5000&pause=1500&color=0EA5E9&center=true&vCenter=true&width=720&height=45&lines=CS+%2B+Statistics+%40+Harvard;Fast%2C+optimized+systems+for+machine+learning;Open+to+SWE+%26+ML+internships" alt="Typing SVG" /></a><br/><br/>
<img src="https://img.shields.io/badge/Harvard%20University-Computer%20Science%20%26%20Statistics-0EA5E9?style=for-the-badge&labelColor=0D1117" /> <img src="https://img.shields.io/badge/Class%20of-2029-0EA5E9?style=for-the-badge&labelColor=0D1117" /> <img src="https://img.shields.io/badge/Location-Cambridge%2C%20MA-0EA5E9?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0D1117" /><br/><br/>
<a href="https://www.linkedin.com/in/aarogya-r-6739ab291/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="mailto:aregmi@college.harvard.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a> <a href="https://github.com/Reg21meme"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a><br/><br/>
<img src="https://komarev.com/ghpvc/?username=Reg21meme&style=for-the-badge&color=0EA5E9&label=PROFILE+VIEWS&labelColor=0D1117" /> <img src="https://img.shields.io/github/followers/Reg21meme?style=for-the-badge&logo=github&color=0EA5E9&labelColor=0D1117&label=FOLLOWERS" /> <img src="https://img.shields.io/github/stars/Reg21meme/microstructure-lab?style=for-the-badge&logo=github&color=0EA5E9&labelColor=0D1117&label=STARS" />
</div>

## About

I'm a sophomore at **Harvard** studying computer science and statistics. My interests sit at the intersection of **machine learning**, **high-performance systems**, and **full-stack development**. I like taking a problem down to its fundamentals, building it end to end, and getting accurate results.

**Open To** — Software Engineering & ML internships · Research opportunities · Open source collaboration

## Featured Projects

<details>
<summary><b>Microstructure Lab — High-Performance Order-Book &amp; ML Execution Engine</b></summary>

<br/>

A C++/Python limit-order-book simulator that models realistic latency, fees, and queue behavior for honest market-microstructure research.

| Aspect | Detail |
|--------|--------|
| **Stack** | C++ · Pybind · Scikit-Learn · NumPy · Pandas · Matplotlib |
| **Scale** | 19.4M tick events replayed · 85,000 time-series feature vectors |
| **Performance** | 34M events/sec · 28.8 ns median latency · zero-allocation critical path |
| **Findings** | Execution simulator revealed a 13x gap between ideal and realistic outcomes |
| **Repository** | [View Source →](https://github.com/Reg21meme/microstructure-lab) |

Bridged the C++ replay engine to Python via Pybind to model fees, latency, and queue behavior, with an ML feature pipeline that processes tens of thousands of time-series vectors for training and validation.

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
| **Repository** | [View Source →](https://github.com/Reg21meme/ConnectZero) |

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

**Developer Tools &amp; Observability**

<img src="https://skillicons.dev/icons?i=git,githubactions,docker,linux,prometheus,grafana,vscode&theme=dark" />

</div>

## Education

### Harvard University

September 2025 – May 2029 | Cambridge, MA

**B.A. in Computer Science &amp; Statistics**

`Data Structures & Algorithms (CS 1240)` `Linear Algebra (MATH 22A)` `Data Science (CS 1090A/B)` `Probability (STAT 110)`

### Massachusetts Institute of Technology

September 2026 – December 2026 | Cambridge, MA

**Cross-Registration**

`Introduction to Machine Learning (6.3900)`

## GitHub Analytics

<div align="center">

<img width="60%" src="https://streak-stats.demolab.com/?user=Reg21meme&hide_border=true&background=0D1117&stroke=0EA5E9&ring=0EA5E9&fire=0EA5E9&currStreakLabel=0EA5E9&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E" />

</div>

## Current Focus

```yaml
current_focus:
  learning:
    - Machine Learning (6.3900)
    - Probability & statistical modeling (STAT 110)
    - Data Science (CS 1090A)
  learnimg:
    - ML/MLOps 
    - AWS
    - Linux
    - Django
  open_to:
    - Software Engineering / ML internships
    - Research & open source collaboration
```

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0EA5E9&height=120&section=footer" />

</div>
