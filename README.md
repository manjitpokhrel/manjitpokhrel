# Manjit Pokhrel

**Adversarial ML Researcher · AI Security · GPU Systems**

Kathmandu, Nepal  
[manjitpokhrel.com.np](https://manjitpokhrel.com.np) ·
[Email](mailto:manjitpokhrel42@gmail.com) ·
[LinkedIn](https://linkedin.com/in/manjitpokhrel)

---

## Research Focus

I study **multilingual alignment failures** in instruction-tuned large language models and design **training-free inference optimization systems** for consumer GPUs.

My work operates at the intersection of:

- Adversarial robustness  
- Tokenization asymmetries  
- Multilingual safety alignment  
- GPU kernel-level performance engineering  

---

## Selected Contributions

### NASB — Nepali Adversarial Safety Benchmark

The first structured adversarial benchmark for Nepali LLMs.

- 1,200+ multilingual and code-switched adversarial probes  
- 73.7% safety bypass rate in Nepali  
- 0% bypass rate in English across the same models  
- Evaluated across Qwen, Gemma, Llama, and Gemini  

Revealed systemic tokenizer and alignment asymmetries in low-resource languages.

---

### Vajra Morphing

A sub-tokenization attack exploiting Devanagari–Latin code-switching.

Demonstrates how tokenizer fragmentation can bypass safety-aligned boundaries without semantic mutation.

---

### GhostWeight

Training-free activation sparsity framework for LLM inference.

- Sparse row-packing CUDA kernels  
- No retraining  
- No fine-tuning  
- Up to 110.5% inference speedup on RTX 5060  

Designed for consumer-grade hardware deployment.

---

### LLM Red Teaming & Alignment Analysis

Systematic evaluation of:

- Prompt injection attacks  
- Jailbreak vulnerabilities  
- Multilingual safety failures  
- Alignment boundary inconsistencies  

Across open-weight and proprietary instruction-tuned models.

---

## Publications & Disclosures

**2026**  
*Lost in Translation: Safety Alignment Failures in Nepali and Code-Switched Variants of Instruction-Tuned Large Language Models*  
Zenodo

**2026**  
*GhostWeight: Training-Free Activation Sparsity for LLM Inference on Consumer Hardware*  
PyPI / GitHub

**2026**  
Google AI VRP — Multilingual Alignment Bypass Disclosure (Triaged)

**2026**  
Meta Whitehat — Multilingual Safety Asymmetry Disclosure (Submitted)

---

## Technical Stack

**Adversarial ML & Security**  
Prompt injection · Jailbreak evaluation · PGD · Membership inference · Responsible disclosure  

**ML Frameworks**  
PyTorch · Transformers · PEFT · HuggingFace · NumPy · scikit-learn · llama.cpp  

**GPU & Systems**  
CUDA 12.6 · CUDA C · Sparse matrix ops · CuPy JIT · Nsight Compute · Roofline analysis  

**Languages**  
Python · C++ · CUDA C · SQL · JavaScript  

**Infrastructure**  
Linux · Git · Docker · HuggingFace Spaces  

---

## Education

Kathmandu University  
BSc Computer Science

---

Focus: Adversarial ML · AI Security · GPU Systems Optimization · Transformer Architectures
