# Qilin Wang

**Research Engineer · ML Infrastructure · MLOps**<br>
Montréal · **[Single-author ICML 2026](https://proceedings.mlr.press/v306/wang26ax.html)** · [LinkedIn](https://www.linkedin.com/in/qilin11/)

I build forecasting models, GPU kernels, and systems that keep experiments traceable.

**[Portfolio](https://fern-forecasting.netlify.app/)** · **[Résumé](https://fern-forecasting.netlify.app/resume/qilin-wang-resume.pdf)** · **[Fern ↗](https://fern-forecasting.netlify.app/research/)**

<a href="https://fern-forecasting.netlify.app/research/">
<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/QilinWang/Fern-icml2026/74e2ca1879c2a6ff40a40e8c16b8aa7ef0a12e94/assets/lorenz-forecast-still.png">
  <img alt="Real saved Lorenz-63 forecasts from a later NLL plus Huber checkpoint: ochre truth, blue prediction and 32 sample paths" src="https://raw.githubusercontent.com/QilinWang/Fern-icml2026/74e2ca1879c2a6ff40a40e8c16b8aa7ef0a12e94/assets/lorenz-forecast.gif" width="820">
</picture>
</a>

_Real saved Lorenz forecasts · 32 samples · later NLL + Huber checkpoint. [Play & inspect →](https://fern-forecasting.netlify.app/research/)_

- 🧠 **One author. ICML 2026.** [Fern](https://fern-forecasting.netlify.app/research/) learns geometric point forecasts with Huber loss. [Paper](https://proceedings.mlr.press/v306/wang26ax.html) · [Code](https://github.com/QilinWang/Fern-icml2026) · [Probabilistic follow-up](https://arxiv.org/abs/2603.22219)
- ⚙️ **Multi-GPU dispatch. Automated runs.** Typed configs → queue → GPU workers → recorded results. **1,000+ ablations in one 3–4 day campaign.** [See the workflow](showcase/fern-experiment-system.md) · [Stale supervisor test](https://github.com/QilinWang/fern-retired#readme)
- ⚡ **26.4× faster on one GPU workload.** Householder forward + backward: **65.79 → 2.49 ms**, **895.3 → 36.3 MiB** peak extra allocation. [Workload, checks and contribution](showcase/householder-kernel.md)

**[SERIE](https://github.com/QilinWang/serie)** — change the shock or observation noise; keep the experiment controlled. [Interactive demo](https://qilinwang.github.io/serie/) · [Rust / Python data tool](https://github.com/QilinWang/serie-rs) · [Stage design](showcase/stages-and-boundaries.md)

**My work:** Fern's original model, training code, ICML paper and first fused Triton kernel.<br>
**AI collaboration:** I directed later platform development and the kernel rewrite with Claude Code and Codex; the linked cases name the roles.

<details>
<summary>More work</summary>

- **NPC village** — a C#/Godot simulation of characters, places, memory and social information, developed with AI coding agents alongside human direction and review.
- **Collaboration** — agentic applications in economics with economists at Xiamen University.
- **[Fern retired](https://github.com/QilinWang/fern-retired)** — historical C# and Rust infrastructure and tests.

</details>
