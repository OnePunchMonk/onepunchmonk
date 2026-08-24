## Avaya Aggarwal

Optimizers, kernels, quantization, serving. I like the part of the stack where
you can measure whether you were right.

Lately: VLM inference perf, and post-training for diffusion models.

---

### Merged upstream

**[unsloth](https://github.com/unslothai/unsloth)**
* [Q-GaLore optimizer, plus a decoupled embedding LR](https://github.com/unslothai/unsloth/pull/4511)
* [cactus QAT scheme](https://github.com/unslothai/unsloth/pull/4679)
* [Continued pretraining as a training method](https://github.com/unslothai/unsloth/pull/4677)
* [OLMo-3 support](https://github.com/unslothai/unsloth/pull/4678)
* [GGUF flash-attention + tensor-parallel CLI flags](https://github.com/unslothai/unsloth/pull/6561)

**[axolotl](https://github.com/axolotl-ai-cloud/axolotl)**
* [MoE routing for ernie4_5_moe and hunyuan_v1_moe](https://github.com/axolotl-ai-cloud/axolotl/pull/3526)
* [Multiple custom optimizers, with e2e tests](https://github.com/axolotl-ai-cloud/axolotl/pull/3457)
* [Killed some dead SDPA patches that were shadowing upstream attention](https://github.com/axolotl-ai-cloud/axolotl/pull/3488)

**[litgpt](https://github.com/Lightning-AI/litgpt)**
* [Pre-flight checkpoint validation, so a bad checkpoint fails in 2s and not 2h](https://github.com/Lightning-AI/litgpt/pull/2214)

**[sktime](https://github.com/sktime/sktime)**
* [`relative_to=y_pred` for percentage-error metrics](https://github.com/sktime/sktime/pull/8335)

---

### Mine

[**AgentQuant**](https://github.com/OnePunchMonk/AgentQuant) (175 stars)
Give it a list of tickers, it researches and backtests strategies. Has a leakage
auditor bolted on, since that's how most backtests quietly lie to you.

[**Oxidized-Vision**](https://github.com/OnePunchMonk/Oxidized-Vision)
PyTorch vision models to standalone Rust binaries. No Python at runtime. Edge, server, WASM.

[**KoRA**](https://github.com/OnePunchMonk/KoRA)
PEFT where the adapters actually talk to each other through a shared CompositionBlock.

[**vlm-harness**](https://github.com/OnePunchMonk/vlm-harness)
VLM evals with regression testing that knows the difference between a real change
and seed noise.

---

<p align="center">
  <img src="https://github-readme-stats-kappa-orpin.vercel.app/api?username=onepunchmonk&show_icons=true&theme=radical&hide_border=true" height="170"/>
  <img src="https://github-readme-stats-kappa-orpin.vercel.app/api/top-langs?username=onepunchmonk&layout=compact&theme=radical&hide_border=true" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=onepunchmonk&theme=radical&hide_border=true" height="180"/>
</p>

---

Gurugram · [avayaaggarwal.com](https://avayaaggarwal.com) · aggarwal.avaya27@gmail.com
