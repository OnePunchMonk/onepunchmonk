## Avaya Aggarwal

I work on the layer between a model and the hardware it runs on — optimizers,
kernels, quantization, and serving — mostly for vision and multimodal models,
where that layer is least well trodden.

---

### Shipped into production training stacks

Eight changes merged into frameworks other teams train on daily.

**[unsloth](https://github.com/unslothai/unsloth)** — memory-efficient finetuning

Added [Q-GaLore](https://github.com/unslothai/unsloth/pull/4511) (low-rank gradient projection with
INT4 statistics) and a decoupled embedding learning rate; [cactus QAT](https://github.com/unslothai/unsloth/pull/4679);
[continued pretraining](https://github.com/unslothai/unsloth/pull/4677) as a first-class training method;
[OLMo-3 support](https://github.com/unslothai/unsloth/pull/4678); and
[GGUF flash-attention with tensor-parallel CLI options](https://github.com/unslothai/unsloth/pull/6561).

**[axolotl](https://github.com/axolotl-ai-cloud/axolotl)** — post-training framework

Built [custom MoE routing for ernie4_5_moe and hunyuan_v1_moe](https://github.com/axolotl-ai-cloud/axolotl/pull/3526),
[multi-optimizer support with end-to-end tests](https://github.com/axolotl-ai-cloud/axolotl/pull/3457),
and [removed dead SDPA patches](https://github.com/axolotl-ai-cloud/axolotl/pull/3488) that were
silently shadowing upstream attention kernels.

**[litgpt](https://github.com/Lightning-AI/litgpt)** — [checkpoint pre-flight validation](https://github.com/Lightning-AI/litgpt/pull/2214),
catching malformed checkpoints before a multi-hour run wastes the GPU.

**[sktime](https://github.com/sktime/sktime)** — [`relative_to=y_pred` support for percentage-error metrics](https://github.com/sktime/sktime/pull/8335).

---

### Built

**[AgentQuant](https://github.com/OnePunchMonk/AgentQuant)** · 175 stars

Turns a stock list into backtested strategies via an agent pipeline over market data.
Includes a data-leakage auditor, because most backtest results are wrong for the same few reasons.

**[Oxidized-Vision](https://github.com/OnePunchMonk/Oxidized-Vision)**

Compiles PyTorch vision models to standalone Rust binaries — no Python runtime, no
framework dependency — targeting edge, server, and WASM.

**[KoRA](https://github.com/OnePunchMonk/KoRA)**

Parameter-efficient finetuning where adapters exchange information through a shared
CompositionBlock instead of training in isolation.

**[vlm-harness](https://github.com/OnePunchMonk/vlm-harness)**

VLM evaluation with statistical regression testing — flags when a change moves a metric
beyond run-to-run noise, rather than reporting single-seed deltas.

---

### Analytics

<p align="center">
  <img src="https://github-readme-stats-kappa-orpin.vercel.app/api?username=onepunchmonk&show_icons=true&theme=radical&hide_border=true" height="170"/>
  <img src="https://github-readme-stats-kappa-orpin.vercel.app/api/top-langs?username=onepunchmonk&layout=compact&theme=radical&hide_border=true" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=onepunchmonk&theme=radical&hide_border=true" height="180"/>
</p>

---

Gurugram, India · [avayaaggarwal.com](https://avayaaggarwal.com) · aggarwal.avaya27@gmail.com
