## About me 👋

I'm an ML researcher in Montréal working on time-series forecasting,
uncertainty, and evaluation under changing conditions. I like building both
models and the tools that make their behavior easier to inspect.

**Start here:** [Fern paper and code](https://github.com/QilinWang/Fern-icml2026) ·
[SERIE demo](https://qilinwang.github.io/serie/) ·
[GPU kernel case study](showcase/householder-kernel.md) ·
[Experiment system case study](showcase/fern-experiment-system.md) ·
[Retired infrastructure](https://github.com/QilinWang/fern-retired)

### Research and projects

- **[Fern](https://fern-forecasting.netlify.app/)** — a geometric approach to
  time-series forecasting. My single-author paper,
  [Ellipsoidal Time Series Forecasting](https://arxiv.org/abs/2505.17370),
  appeared at ICML 2026. The paper evaluates point forecasts; the
  [Noise Titration preprint](https://arxiv.org/abs/2603.22219) studies
  probabilistic forecasting and evaluation.
- **[SERIE](https://github.com/QilinWang/serie)** — a Python toolkit for
  exploring time-series data under controlled changes and observation noise.
  Explore the [attractor demo](https://qilinwang.github.io/serie/).
- **[Fern: retired implementations](https://github.com/QilinWang/fern-retired)**
  — archived C# and Rust research infrastructure, with notes on what replaced
  it and which tests need external dependencies.
- **NPC village** — a simulation project with a C# world and a Godot client,
  exploring characters, places, memory and social information. Development
  uses AI coding agents alongside human direction and review.

### GPU engineering: a measured optimization

[![Householder transform microbenchmark comparing a PyTorch loop and Triton rotations](assets/householder-microbenchmark.png)](showcase/householder-kernel.md)

I wrote Fern's first fused Triton kernel and directed an AI-assisted rewrite.
On one recorded RTX 4070 Laptop microbenchmark, the PyTorch loop and revised
Triton rotations took **65.79 ms vs 2.49 ms** for the measured forward and
backward operation. [See the workload, memory comparison, numerical check and
AI contribution](showcase/householder-kernel.md). The numbers describe that
operator workload, not full-model training.

### Experiment system: from a card to accepted results

[![A real Fern study from configuration to two accepted result documents](assets/fern-experiment-flow.png)](showcase/fern-experiment-system.md)

[Follow one actual study](showcase/fern-experiment-system.md) through its
configuration, recorded compilation, scheduling, execution and result
acceptance, with my contribution and the AI collaboration stated separately.
Acceptance records a result state; scientific interpretation is a separate step.

### Collaborations

- Collaboration with economists at Xiamen University on agentic applications
  in economics.

### Tools and interests

My research uses Python and PyTorch. The projects also include Gleam/Erlang
experiment infrastructure, C#/Godot simulation, and archived Rust tools.
I'm continuing to learn about Rust, GPU kernels and agentic systems.

[Fern website](https://fern-forecasting.netlify.app/) ·
[LinkedIn](https://www.linkedin.com/in/qilin11/)
