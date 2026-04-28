<!--
  github.com/ecloud-bh — profile README
-->

## Muhammet P.

Sovereign software engineer building AI, blockchain, and cybersecurity
infrastructure from Türkiye. Founder and lead engineer at
[**eCloud Yazılım Teknolojileri**](https://e-cloud.web.tr).

I work where these three disciplines intersect — sovereign AI that is
KVKK-resident and verifiable, blockchain rails that satisfy real
compliance regimes, and security postures that hold under regulatory
audit. The work below is the public, measurable proof of that practice.

---

### Currently shipping — AIGENCY V4

A 128-billion-parameter sovereign, multimodal large language model
designed for Turkish. Released April 2026. Built in Türkiye, evaluated
against the world.

|  |  |
|---|---|
| **World #1** &nbsp; Turkish reading comprehension | Belebele-TR &nbsp; **87.33** |
| **Frontier-level** &nbsp; grade-school mathematics | GSM8K &nbsp; **94.62** |
| **Frontier-level** &nbsp; scientific reasoning | ARC-Challenge &nbsp; **94.88** |
| Upper-mid frontier &nbsp; code generation | HumanEval &nbsp; **84.15** &nbsp;/&nbsp; MBPP &nbsp; **84.82** |
| Lower-mid frontier &nbsp; multitask academic | MMLU &nbsp; **80.10** |
| Honest gap &nbsp; (V4.1 priority) | GPQA-D &nbsp; **37.88** &nbsp;/&nbsp; MMLU-Pro &nbsp; **50.20** |

**22 benchmarks &nbsp;·&nbsp; 13,344 real production API calls &nbsp;·&nbsp; Wilson 95% confidence intervals &nbsp;·&nbsp; seed=42 &nbsp;·&nbsp; per-item `scored.jsonl` open under MIT.**

> [Whitepaper (32 pp, EN + TR)](https://github.com/ecloud-bh/aigency-v4-whitepaper) &nbsp;·&nbsp;
> [Model card](https://huggingface.co/aigencydev/AIGENCY-V4) &nbsp;·&nbsp;
> [Evaluation dataset](https://huggingface.co/datasets/aigencydev/aigency-v4-evaluation) &nbsp;·&nbsp;
> [Live demo](https://huggingface.co/spaces/aigencydev/AIGENCY-V4-Demo) &nbsp;·&nbsp;
> [Benchmark runner](https://github.com/ecloud-bh/aigency-benchmarks) &nbsp;·&nbsp;
> [Production API](https://aigency.dev)

---

### Focus areas

**Sovereign artificial intelligence.** &nbsp; Architecture, training, and
evaluation of frontier-adjacent large language models with full data
residency. Hierarchical Memory (HBM) with Time-Guided Decay, Localised
Mixture-of-Experts, Adaptive LoRA+, Selective Layer Collapse, 4-bit
symmetric block quantization. Reproducible evaluation as a first-class
engineering artefact, not a marketing afterthought.

**Blockchain and verifiable infrastructure.** &nbsp; GPG-signed training
pipelines, content-addressable model checkpoints, and tamper-evident
audit trails. The same trust primitives that make a chain auditable
also make an AI release auditable — I treat them as one stack.

**Cybersecurity and compliance.** &nbsp; KVKK-resident hosting, EU AI Act
posture, and security review for production AI workloads in
public-sector, financial, healthcare, and defence contexts. Threat
modelling for prompt injection, data exfiltration, and supply-chain
risk in model weights and tokenizer artefacts.

---

### AIGENCY programme — sovereign LLM timeline

| Year | Release | Milestone |
|---|---|---|
| 2024 | AIGENCY V2 | First fully sovereign Turkish LLM release |
| 2025 | AIGENCY V3 | Architecture maturity, Turkish morphology calibration, 200K+ context |
| 2026 | **AIGENCY V4** | Multimodal, 128B parameters, frontier-adjacent, transparent evaluation |
| 2026 Q4 | AIGENCY V4.1 | Vision encoder 8B → 16B, GPQA-D 0.55 target, latency p50 ≤ 4 s |

Türkiye's longest-running fully sovereign LLM programme.

---

### Selected public artefacts

| Artefact | Description | Lisence |
|---|---|---|
| [`aigency-v4-whitepaper`](https://github.com/ecloud-bh/aigency-v4-whitepaper) | 32-page technical whitepaper (EN + TR) | CC BY-ND 4.0 |
| [`aigency-benchmarks`](https://github.com/ecloud-bh/aigency-benchmarks) | Reproducibility capsule — 22 benchmarks, 13,344 raw responses, scoring code | MIT |
| [`aigencydev/AIGENCY-V4`](https://huggingface.co/aigencydev/AIGENCY-V4) | Hugging Face model card + methodology | Open methodology |
| [`aigencydev/aigency-v4-evaluation`](https://huggingface.co/datasets/aigencydev/aigency-v4-evaluation) | Evaluation dataset (raw + scored) | MIT |
| [`aigencydev/AIGENCY-V4-Demo`](https://huggingface.co/spaces/aigencydev/AIGENCY-V4-Demo) | Live Gradio demo (production API proxy) | Open |

---

### Stack

**Languages.** &nbsp; `Python` &nbsp;·&nbsp; `Rust` &nbsp;·&nbsp; `Go` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `C++` &nbsp;·&nbsp; `Solidity`

**ML and serving.** &nbsp; `PyTorch` &nbsp;·&nbsp; `Triton` &nbsp;·&nbsp; `CUDA` &nbsp;·&nbsp; `vLLM` &nbsp;·&nbsp; `Hugging Face` &nbsp;·&nbsp; `bitsandbytes` &nbsp;·&nbsp; `Flash-Attention`

**Web and platform.** &nbsp; `FastAPI` &nbsp;·&nbsp; `gRPC` &nbsp;·&nbsp; `Next.js` &nbsp;·&nbsp; `Postgres` &nbsp;·&nbsp; `Redis` &nbsp;·&nbsp; `Kafka` &nbsp;·&nbsp; `ClickHouse`

**Infra and security.** &nbsp; `Kubernetes` &nbsp;·&nbsp; `Terraform` &nbsp;·&nbsp; `Vault` &nbsp;·&nbsp; `GPG` &nbsp;·&nbsp; `Sigstore` &nbsp;·&nbsp; `Grafana` &nbsp;·&nbsp; `Prometheus`

**Blockchain.** &nbsp; `EVM` &nbsp;·&nbsp; `Hardhat` &nbsp;·&nbsp; `Foundry` &nbsp;·&nbsp; `viem` &nbsp;·&nbsp; on-chain attestations &nbsp;·&nbsp; zero-knowledge proofs

---

### Citation

If you reference AIGENCY V4 in academic or technical work:

```bibtex
@techreport{aigency-v4-2026,
  title       = {AIGENCY V4: Sovereign, Fully Independent and Multimodal 128B-Parameter AI Architecture},
  author      = {{eCloud Yaz{\i}l{\i}m Teknolojileri}},
  year        = {2026},
  month       = apr,
  institution = {eCloud Yaz{\i}l{\i}m Teknolojileri},
  url         = {https://github.com/ecloud-bh/aigency-v4-whitepaper}
}
```

---

### Contact

- **Direct.** &nbsp; [mpolat@e-cloud.web.tr](mailto:mpolat@e-cloud.web.tr)
- **AIGENCY team.** &nbsp; [ai@aigency.dev](mailto:ai@aigency.dev)
- **LinkedIn.** &nbsp; [linkedin.com/in/muhammetpolat](https://www.linkedin.com/in/muhammetpolat)
- **Web.** &nbsp; [aigency.dev](https://aigency.dev) &nbsp;·&nbsp; [e-cloud.web.tr](https://e-cloud.web.tr)

Open to research collaboration on Turkish NLP, sovereign AI, and
KVKK-compliant inference. Enterprise access and partnership inquiries
welcome via either address above.

---

<sub>Built in Türkiye, evaluated against the world. &nbsp; © 2026 eCloud Yazılım Teknolojileri.</sub>
