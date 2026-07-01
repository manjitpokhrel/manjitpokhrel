# Manjit Pokhrel

**AI Security Researcher · Adversarial ML · Hardware Security · Compiler Security**

Kathmandu, Nepal · MLCommons Contributor  
[manjitpokhrel.com.np](https://manjitpokhrel.com.np) · 
[Email](mailto:manjitpokhrel42@gmail.com) · 
[LinkedIn](https://linkedin.com/in/manjitpokhrel) · 
[ResearchGate]([https://researchgate.net/profile/YOUR_ID](https://www.researchgate.net/profile/Manjit-Pokhrel?ev=hdr_xprf)) · 
[Medium](https://medium.com/@manjitpokhrel)

---

## Research Focus

I study **adversarial safety failures** in large language models 
and build **systems-level tools** for inference optimization 
and security analysis — from GPU kernels to compiler passes.

Currently investigating:

- **Multilingual safety alignment failures** in RLHF-trained LLMs
- **Compiler-level safety degradation** — does `torch.compile` silently break alignment?
- **Cache-timing side-channel attacks** on transformer inference
- **Activation-level jailbreak detection** via neuron firing patterns
- **Training-free inference sparsity** via custom CUDA/Triton kernels

---

## Selected Contributions

### NASB — Nepali Adversarial Safety Benchmark  
[Paper (Zenodo)]([INSERT_DOI_LINK](https://zenodo.org/records/19764520)) · [Code]([INSERT_GITHUB_LINK](https://github.com/manjitpokhrel))

First structured adversarial safety benchmark for Nepali-language LLMs.

- 1,200+ multilingual and code-switched adversarial probes  
- **73.7% safety bypass rate in Nepali vs 0% in English**
- Evaluated across Qwen, Gemma, Llama, and Gemini  
- Findings disclosed to **Google AI VRP** (triaged) and **Meta Whitehat**
- Independently confirmed by Qwen engineer
- Revealed systemic tokenizer and alignment asymmetries in low-resource languages

---

### GhostWeight  
[PyPI]([INSERT_PYPI_LINK](https://pypi.org/project/ghostweight/)) · [Code]([INSERT_GITHUB_LINK](https://github.com/manjitpokhrel/GhostWeight))

Training-free activation sparsity framework for LLM inference.

- Custom CUDA kernels: sparse row-packing at warp/shared-memory level  
- **110.5% inference speedup** on RTX 5060 (Blackwell)
- Zero retraining. Zero fine-tuning. Zero accuracy loss.
- Currently porting to **OpenAI Triton** as GhostWeight-Triton (sm_120)

---

### Vajra Morphing

Adversarial attack vector I coined. Exploits morphological 
transformations in Devanagari script to bypass LLM safety 
filters at the **subtoken level** — below where safety 
alignment operates.

---

### The Eleventh Optimization *(in progress)*

Investigating whether ML compiler optimizations 
(`torch.compile`, Triton kernels, TensorRT) **silently 
alter safety alignment** in RLHF-trained models. 
Zero prior work exists on this intersection.

---

### Cache-Timing Attacks on Transformer Attention *(in progress)*

Extending Flush+Reload side-channel attacks from CNNs 
(Cache Telepathy, USENIX 2020) to **transformer attention 
mechanisms** — exploiting input-dependent memory access 
patterns unique to self-attention.

---

## Publications & Disclosures

| Year | Work | Venue |
|------|------|-------|
| 2026 | *Lost in Translation: Safety Alignment Failures in Nepali and Code-Switched Variants of Instruction-Tuned LLMs* | [Zenodo]([INSERT_LINK](https://zenodo.org/records/19764520)) |
| 2026 | *GhostWeight: Training-Free Activation Sparsity for LLM Inference* | [PyPI]([INSERT_LINK](https://pypi.org/project/ghostweight/)) / [GitHub]([INSERT_LINK](https://github.com/manjitpokhrel/GhostWeight)) |
| 2026 | Multilingual Alignment Bypass Disclosure | Google AI VRP (Triaged) |
| 2026 | Multilingual Safety Asymmetry Disclosure | Meta Whitehat |
| 2026 | *The Eleventh Way In* (essay) | [Medium]([INSERT_LINK](https://medium.com/@manjitpokhrel42/the-eleventh-way-in-c590236fc249)) |

---

## Affiliations

- **MLCommons** — Contributor, DMLR & AI Risk and Reliability Working Groups (2026–present)

---

## Technical Stack

**Security & Adversarial ML**  
Jailbreak evaluation · Cross-lingual safety bypass · Tokenizer exploitation · 
Morphological attacks · Side-channel analysis (cache-timing) · Responsible disclosure

**ML Frameworks**  
PyTorch · HuggingFace Transformers · PEFT · NumPy · scikit-learn · llama.cpp

**GPU & Compiler Systems**  
CUDA 12.8 · CUDA C (warp-level kernels) · OpenAI Triton (sm_120 Blackwell) · 
MLIR (learning) · Nsight Compute · Roofline analysis

**Systems & Hardware**  
Flush+Reload (C) · Cache-timing attacks · AMD Zen 4 microarchitecture · 
· Operator fusion · Graph breaks

**Languages**  
Python · C · CUDA C · JavaScript · SQL

**Infrastructure**  
Linux · Git · Docker · FastAPI · HuggingFace Spaces · Vercel

---

## Hardware

RTX 5060 8GB (Blackwell, sm_120) · Ryzen 7 7700 (Zen 4) · 16GB DDR5

---

## Education

**Kathmandu University**  
BSc Computer Science (Expected 2029)

---
