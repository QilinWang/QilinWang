# Qilin Wang

**Research Engineer · ML Infrastructure · MLOps**<br>
Montréal · **[Single-author ICML 2026](https://proceedings.mlr.press/v306/wang26ax.html)** · [LinkedIn](https://www.linkedin.com/in/qilin11/)

I build forecasting models, GPU kernels, and systems that keep experiments traceable.

**[Portfolio](https://fern-forecasting.netlify.app/)** · **[Résumé](https://fern-forecasting.netlify.app/resume/qilin-wang-resume.pdf)** · **[Play real forecasts](https://fern-forecast-player.netlify.app/compare/#guide)**

<a href="https://fern-forecast-player.netlify.app/compare/#guide">
<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/QilinWang/QilinWang/main/assets/fern-lorenz-still.png">
  <img alt="Lorenz-63 equations and a local Jacobian ellipsoid: an illustration, not a Fern forecast" src="https://raw.githubusercontent.com/QilinWang/QilinWang/main/assets/fern-lorenz.gif" width="820">
</picture>
</a>

_Lorenz dynamics illustration. [Inspect saved Fern predictions, two seeds and 32 sample paths →](https://fern-forecast-player.netlify.app/compare/#guide)_

- 🧠 **One author. ICML 2026.** Fern learns geometric point forecasts. [Paper](https://proceedings.mlr.press/v306/wang26ax.html) · [Code](https://github.com/QilinWang/Fern-icml2026) · [Probabilistic follow-up](https://arxiv.org/abs/2603.22219)
- ⚙️ **Multi-GPU dispatch. Automated runs.** Typed configs → queue → GPU workers → recorded results. **1,000+ ablations in one 3–4 day campaign.** [See the workflow](showcase/fern-experiment-system.md) · [Stale supervisor test](https://github.com/QilinWang/fern-retired#readme)
- ⚡ **26.4× faster on one GPU workload.** Householder forward + backward: **65.79 → 2.49 ms**, **895.3 → 36.3 MiB** peak extra allocation. [Workload, checks and contribution](showcase/householder-kernel.md)

**[SERIE](https://github.com/QilinWang/serie)** — change the shock or observation noise; keep the experiment controlled. [Interactive demo](https://qilinwang.github.io/serie/) · [Rust / Python data tool](https://github.com/QilinWang/serie-rs) · [Stage design](showcase/stages-and-boundaries.md)

**My work + AI:** I developed Fern's original model, training code, first paper and first fused kernel. I directed later platform work and the kernel rewrite with Claude Code and Codex; the linked cases name the division of work.

<details>
<summary>More work</summary>

- **NPC village** — a C#/Godot simulation of characters, places, memory and social information, developed with AI coding agents alongside human direction and review.
- **Collaboration** — agentic applications in economics with economists at Xiamen University.
- **[Fern retired](https://github.com/QilinWang/fern-retired)** — historical C# and Rust infrastructure and tests.

</details>
