<div align="center">

# Hey, I'm Samvit 👋

### I build AI systems, developer tools, and things that usually start with "what if..."

<p>
  <a href="https://github.com/samvitgersappa">
    <img src="https://komarev.com/ghpvc/?username=samvitgersappa&label=Profile%20Views&color=6366f1&style=flat-square" alt="Profile Views" />
  </a>
  <a href="https://linkedin.com/in/samvit-gersappa">
    <img src="https://img.shields.io/badge/LinkedIn-Samvit%20Gersappa-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:samvit.gersappa@gmail.com">
    <img src="https://img.shields.io/badge/Email-Let's%20Talk-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=AI+Systems+%26+Developer+Tools;Multimodal+Models+%26+Local+LLMs;Distributed+Data+Infrastructure;Building+things+to+understand+how+they+work." alt="Typing SVG" />

</div>

---

## `whoami`

I'm a software engineer at **Dell Technologies** and a Computer Science graduate from **RV College of Engineering, Bengaluru**.

I'm interested in the messy space between **AI research and real systems**.

I like taking research-heavy ideas and figuring out how to make them actually work — whether that's a vision-language model reasoning over satellite imagery, a tool that catches documentation drifting away from code, or experiments with running and evaluating LLMs locally on constrained hardware.

Most of my projects start with me wanting to understand something deeply enough to build my own version of it.

```python
samvit = {
    "building": ["AI-native developer tools", "LLM systems"],
    "researching": ["multimodal AI", "quantization", "agentic systems"],
    "exploring": ["distributed systems", "quant research", "open source"],
    "hardware": "MacBook Air M4 · 16 GB · somehow still alive",
    "philosophy": "build it to understand it",
}
```

---

## 🚀 Things I've been building

### 🔭 DriftLens

> **When code changes but the docs don't.**

An AI-native developer tool for detecting **semantic drift between source code and documentation**.

Instead of simply comparing text, DriftLens extracts semantic claims from documentation and validates them against the actual structure of a codebase.

The system combines AST-level analysis with LLM-based semantic reasoning to catch documentation that is technically valid text but no longer describes what the code actually does.

**Built with**

`Rust` · `tree-sitter` · `Python` · `AST Analysis` · `LLMs` · `Semantic Validation`

---

### 🌍 EcoVisionNet

> **Multimodal reasoning over the Earth's surface.**

A multi-task **vision-language model for geospatial pixel reasoning**, combining remote-sensing imagery with natural-language representations.

Built around a **Swin Transformer V2 + FPN vision stack**, CLIP-based text representations, and cross-modal transformer fusion.

The model explores multiple geospatial tasks through a shared multimodal representation:

* 🗺️ Semantic segmentation
* 📍 Anchor-free object detection
* 🔄 Siamese change detection
* 🛰️ Vision-language alignment

Trained across a curated collection of remote-sensing datasets covering land-cover classification and multi-temporal satellite imagery.

**Built with**

`PyTorch` · `Swin Transformer V2` · `CLIP` · `Transformers` · `Remote Sensing`

---
### 🧪 Local LLM & Quantization Research

I've been experimenting with running **quantized language models locally on Apple Silicon** and exploring a question I find particularly interesting:

> What capabilities — and alignment behaviours — quietly change when we compress a model?

I'm building evaluation experiments around **quantization-induced behavioural and safety regressions** across models, parameter sizes, and quantization levels.

A lot of this work involves figuring out how far consumer hardware can realistically be pushed before model behaviour begins changing in unexpected ways.

**Working with**

`Ollama` · `llama.cpp` · `Apple Silicon` · `LLM Evaluation` · `Quantization`

---

### ⚙️ Distributed Data Infrastructure

I've worked on scaling **Apache Airflow from single-node infrastructure towards horizontally scalable deployments** using container orchestration.

This involved exploring the actual systems problems hidden underneath "just scale Airflow":

* Distributed task scheduling
* Celery and Kubernetes execution models
* DAG deployment and GitSync
* Worker scaling and failure recovery
* CI/CD for data infrastructure
* Centralised logging and observability

**Working with**

`Apache Airflow` · `OpenShift` · `Kubernetes` · `Docker` · `Jenkins` · `Celery`

---

## 🔬 Currently exploring

```text
samvit/
│
├── llms/
│   ├── building-from-fundamentals
│   ├── local-inference
│   └── quantization-behaviour
│
├── agents/
│   ├── tool-using-models
│   └── agentic-workflows
│
├── systems/
│   ├── distributed-infrastructure
│   └── ai-native-devtools
│
├── research/
│   ├── multimodal-ai
│   ├── geospatial-vision
│   └── quantitative-systems
│
└── probably-overthinking/
    └── everything
```

I tend to learn by going slightly too deep into things.

---

## 🧰 Tech I work with

<div align="center">

### AI / ML

<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn" />
</p>

<p>
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM_Evaluation-6366F1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Computer_Vision-8B5CF6?style=for-the-badge" />
</p>

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,rust,c,cpp,java,js" />
</p>

### Infrastructure & Systems

<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,git,github,jenkins" />
</p>

<p>
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white" />
</p>

### Data & Experimentation

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql" />
</p>

<p>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge" />
</p>

</div>

---

## 📊 GitHub, according to GitHub

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=samvitgersappa&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=samvitgersappa&layout=compact&hide_border=true&theme=transparent&langs_count=8" />

</div>

<br />

<div align="center">

<img src="https://streak-stats.demolab.com?user=samvitgersappa&theme=transparent&hide_border=true" alt="GitHub Streak" />

</div>

---

## 📈 Contribution graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=samvitgersappa&theme=github-compact&hide_border=true&area=true" width="95%" alt="Contribution Graph" />

</div>

---

## 🐍 Contributions, but make it a snake

<div align="center">

<img src="https://raw.githubusercontent.com/samvitgersappa/samvitgersappa/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />

</div>

> The snake animation requires a GitHub Actions workflow. See the setup note below.

---

## 💭 A few things I believe

```text
→ Build things to understand them.
→ A working prototype teaches more than another saved paper.
→ Local models are going to get much more interesting.
→ Good developer tools should feel obvious after you use them.
→ If an idea sounds slightly unreasonable, it's probably worth testing.
```

---

## 🤝 Find me

I'm always interested in talking about **LLMs, AI systems, developer tooling, distributed infrastructure, geospatial AI, or weird project ideas**.

If you're building something interesting, feel free to reach out.

<div align="center">

<a href="https://linkedin.com/in/samvit-gersappa">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="mailto:samvit.gersappa@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Say_hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br />
<br />

<sub>probably building something that does not need to exist yet.</sub>

</div>
