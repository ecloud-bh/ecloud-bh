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

Programme founded **2021**. Türkiye's longest-running fully sovereign
LLM line.

| Year | Release | Milestone |
|---|---|---|
| 2021 | Programme founded | Sovereign-AI research charter; Turkish-first tokenizer studies; data residency roadmap |
| 2022 | Foundational research | Sovereign training infrastructure; Turkish morphology calibration; first internal LLM prototypes |
| 2023 | AIGENCY V1 | First fully sovereign Turkish LLM milestone (early-access cohort) |
| 2024 | AIGENCY V2 | First public sovereign release; Turkish-NLP baseline established |
| 2025 | AIGENCY V3 | Architecture maturity, 200K+ context, hierarchical memory primitives |
| 2026 | **AIGENCY V4** | Multimodal, 128B parameters, frontier-adjacent, transparent evaluation |
| 2026 Q4 | AIGENCY V4.1 | Vision encoder 8B → 16B, GPQA-D 0.55 target, latency p50 ≤ 4 s |

---

### Selected public artefacts

| Artefact | Description | Licence |
|---|---|---|
| [`aigency-v4-whitepaper`](https://github.com/ecloud-bh/aigency-v4-whitepaper) | 32-page technical whitepaper (EN + TR) | CC BY-ND 4.0 |
| [`aigency-benchmarks`](https://github.com/ecloud-bh/aigency-benchmarks) | Reproducibility capsule — 22 benchmarks, 13,344 raw responses, scoring code | MIT |
| [`aigencydev/AIGENCY-V4`](https://huggingface.co/aigencydev/AIGENCY-V4) | Hugging Face model card and methodology | Open methodology |
| [`aigencydev/aigency-v4-evaluation`](https://huggingface.co/datasets/aigencydev/aigency-v4-evaluation) | Evaluation dataset (raw + scored) | MIT |
| [`aigencydev/AIGENCY-V4-Demo`](https://huggingface.co/spaces/aigencydev/AIGENCY-V4-Demo) | Live Gradio demo (production API proxy) | Open |

---

### Stack

**Languages.** &nbsp; `Python` &nbsp;·&nbsp; `Rust` &nbsp;·&nbsp; `Go` &nbsp;·&nbsp; `C++` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `Solidity` &nbsp;·&nbsp; `Move` &nbsp;·&nbsp; `Vyper` &nbsp;·&nbsp; `Bash` &nbsp;·&nbsp; `SQL`

#### Artificial intelligence

| Layer | Stack |
|---|---|
| Training | `PyTorch` &nbsp;·&nbsp; `JAX` &nbsp;·&nbsp; `DeepSpeed` &nbsp;·&nbsp; `FSDP` &nbsp;·&nbsp; `Megatron-LM` &nbsp;·&nbsp; `accelerate` |
| Inference kernels | `Triton` &nbsp;·&nbsp; `CUDA` &nbsp;·&nbsp; `Flash-Attention 2/3` &nbsp;·&nbsp; `xFormers` &nbsp;·&nbsp; `bitsandbytes` &nbsp;·&nbsp; `AWQ` &nbsp;·&nbsp; `GPTQ` |
| Serving | `vLLM` &nbsp;·&nbsp; `TensorRT-LLM` &nbsp;·&nbsp; `TGI` &nbsp;·&nbsp; `llama.cpp` &nbsp;·&nbsp; `Ollama` &nbsp;·&nbsp; `BentoML` |
| Eval and observability | `lm-evaluation-harness` &nbsp;·&nbsp; `lighteval` &nbsp;·&nbsp; `Weights & Biases` &nbsp;·&nbsp; `MLflow` &nbsp;·&nbsp; `Phoenix` &nbsp;·&nbsp; `Langfuse` |
| RAG and vectors | `Qdrant` &nbsp;·&nbsp; `Weaviate` &nbsp;·&nbsp; `Milvus` &nbsp;·&nbsp; `pgvector` &nbsp;·&nbsp; `FAISS` &nbsp;·&nbsp; `LangChain` &nbsp;·&nbsp; `LlamaIndex` |
| Multimodal | `CLIP / SigLIP` &nbsp;·&nbsp; `Whisper` &nbsp;·&nbsp; `SAM 2` &nbsp;·&nbsp; `Florence-2` &nbsp;·&nbsp; vision encoders &nbsp;·&nbsp; cross-modal projection |
| Agents and tools | `MCP` (Model Context Protocol) &nbsp;·&nbsp; `AIGENCY` SDKs &nbsp;·&nbsp; tool-use schemas &nbsp;·&nbsp; structured output |

#### Blockchain and on-chain systems

| Layer | Stack |
|---|---|
| Smart-contract development | `Foundry` &nbsp;·&nbsp; `Hardhat` &nbsp;·&nbsp; `viem` &nbsp;·&nbsp; `ethers.js` &nbsp;·&nbsp; `web3.py` |
| EVM and L2s | `Ethereum` &nbsp;·&nbsp; `Optimism` &nbsp;·&nbsp; `Arbitrum` &nbsp;·&nbsp; `Base` &nbsp;·&nbsp; `zkSync` &nbsp;·&nbsp; `Scroll` &nbsp;·&nbsp; `Linea` &nbsp;·&nbsp; `Polygon zkEVM` |
| Non-EVM | `Solana` (Anchor, Rust) &nbsp;·&nbsp; `Cosmos SDK` &nbsp;·&nbsp; `Sui` &nbsp;·&nbsp; `Aptos` |
| Zero-knowledge | `Circom` &nbsp;·&nbsp; `Noir` &nbsp;·&nbsp; `Halo2` &nbsp;·&nbsp; `Plonky3` &nbsp;·&nbsp; `RISC Zero` &nbsp;·&nbsp; `SP1` &nbsp;·&nbsp; `snarkjs` |
| Standards | `ERC-20` &nbsp;·&nbsp; `ERC-721` &nbsp;·&nbsp; `ERC-1155` &nbsp;·&nbsp; `ERC-4337` (account abstraction) &nbsp;·&nbsp; `EIP-712` &nbsp;·&nbsp; `ERC-6551` |
| Audit and analytics | `Slither` &nbsp;·&nbsp; `Mythril` &nbsp;·&nbsp; `Echidna` &nbsp;·&nbsp; Foundry invariants &nbsp;·&nbsp; `The Graph` &nbsp;·&nbsp; `Dune` &nbsp;·&nbsp; `Tenderly` |
| Verifiable AI | content-addressed checkpoints &nbsp;·&nbsp; on-chain attestation registries &nbsp;·&nbsp; restaking primitives (`EigenLayer`) |

#### Cybersecurity and compliance

| Layer | Stack |
|---|---|
| Static and dynamic analysis | `Semgrep` &nbsp;·&nbsp; `CodeQL` &nbsp;·&nbsp; `Bandit` &nbsp;·&nbsp; `Burp Suite` &nbsp;·&nbsp; `OWASP ZAP` &nbsp;·&nbsp; `nuclei` |
| Network and offensive | `nmap` &nbsp;·&nbsp; `Wireshark` &nbsp;·&nbsp; `Metasploit` &nbsp;·&nbsp; `Hydra` &nbsp;·&nbsp; `BloodHound` |
| Supply-chain integrity | `Sigstore` (cosign, rekor) &nbsp;·&nbsp; `SLSA` &nbsp;·&nbsp; `in-toto` &nbsp;·&nbsp; `Syft` &nbsp;·&nbsp; `Grype` &nbsp;·&nbsp; `Trivy` &nbsp;·&nbsp; `GPG` &nbsp;·&nbsp; `age` |
| Cloud and runtime | `Falco` &nbsp;·&nbsp; `OPA / Gatekeeper` &nbsp;·&nbsp; `Kyverno` &nbsp;·&nbsp; AWS Security Hub &nbsp;·&nbsp; GCP SCC &nbsp;·&nbsp; Azure Defender |
| SIEM and detection | `Elastic SIEM` &nbsp;·&nbsp; `Wazuh` &nbsp;·&nbsp; `Splunk` &nbsp;·&nbsp; `Suricata` &nbsp;·&nbsp; `Zeek` |
| Identity and secrets | `HashiCorp Vault` &nbsp;·&nbsp; `OAuth 2.1` &nbsp;·&nbsp; `OIDC` &nbsp;·&nbsp; `SAML` &nbsp;·&nbsp; `mTLS` &nbsp;·&nbsp; `WebAuthn` |
| AI-specific security | prompt-injection threat models &nbsp;·&nbsp; data-exfiltration controls &nbsp;·&nbsp; tokenizer / weight supply-chain &nbsp;·&nbsp; jailbreak red-teaming |
| Compliance frameworks | `KVKK` &nbsp;·&nbsp; `EU AI Act` &nbsp;·&nbsp; `GDPR` &nbsp;·&nbsp; `ISO 27001` &nbsp;·&nbsp; `SOC 2 Type II` &nbsp;·&nbsp; `NIST CSF 2.0` &nbsp;·&nbsp; `PCI DSS` |

#### Platform and infrastructure

`Kubernetes` &nbsp;·&nbsp; `Terraform` &nbsp;·&nbsp; `Pulumi` &nbsp;·&nbsp; `Ansible` &nbsp;·&nbsp; `Helm` &nbsp;·&nbsp; `Argo CD` &nbsp;·&nbsp; `FastAPI` &nbsp;·&nbsp; `gRPC` &nbsp;·&nbsp; `Next.js` &nbsp;·&nbsp; `Postgres` &nbsp;·&nbsp; `ClickHouse` &nbsp;·&nbsp; `Redis` &nbsp;·&nbsp; `Kafka` &nbsp;·&nbsp; `NATS` &nbsp;·&nbsp; `Grafana` &nbsp;·&nbsp; `Prometheus` &nbsp;·&nbsp; `OpenTelemetry`

---

### Citation

If you reference AIGENCY V4 in academic or technical work:

```bibtex
@techreport{aigency-v4-2026,
  title       = {AIGENCY V4: Sovereign, Fully Independent and Multimodal 128B-Parameter AI Architecture},
  author      = {{eCloud Yazılım Teknolojileri}},
  year        = {2026},
  month       = apr,
  institution = {eCloud Yazılım Teknolojileri},
  url         = {https://github.com/ecloud-bh/aigency-v4-whitepaper}
}
```

(Use a UTF-8 BibTeX backend — `biber` + `biblatex` — for correct
rendering of Turkish characters. For legacy `bibtex`, replace
`Yazılım` with `Yaz\i l\i m`.)

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
