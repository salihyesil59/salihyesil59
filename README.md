## Salih Yeşil

**MSc Mathematical Physics · Istanbul University**

I'm a master's student in mathematical physics at Istanbul University, working
in cosmology. I enjoy turning physics and mathematics into code, so on GitHub I
build programs and tools in physics, mathematics and artificial intelligence.

🔗 **[salihyesil59.github.io](https://salihyesil59.github.io/)**

---

### Research code

| | |
|---|---|
| **[CosmoFit](https://github.com/salihyesil59/CosmoFit)** | Cosmological parameter estimation and Bayesian inference. Since v2.0 built from theories, likelihoods and samplers, assembled from a YAML input and run with `cosmofit run`. ΛCDM, wCDM, CPL, JBP, BA, PEDE, GEDE, sign-switching Λ, Chaplygin gas, interacting DE and early dark energy, and modified gravity (f(R), f(R,T), f(T), f(Q), DGP), fitted down to structure growth; 21 datasets including DESI DR2 and the CMB through CAMB, or through fastcmb in milliseconds since v2.3; MCMC, emcee, dynesty, profile and Fisher samplers; a desktop GUI that walks through a fit step by step. [`pip install cosmofit`](https://pypi.org/project/cosmofit/) |
| **[wljs-gr-toolkit](https://github.com/salihyesil59/wljs-gr-toolkit)** | Thirteen notebooks of symbolic general relativity and modified gravity in Wolfram Language. A metric in, curvature tensors out; an action in, field equations and E(z) out, through to gravitational-wave propagation, Solar System bounds and standard sirens. Every notebook ends in verification against known limits. |
| **[fastcmb](https://github.com/salihyesil59/fastcmb)** | An emulator in front of CAMB that learns while the chain runs: it answers a point in about 6 ms when its own error estimate is small enough and runs CAMB otherwise. A ΛCDM Planck fit drops from 16.5 hours to about one. For CosmoFit, cobaya or any Python analysis. [`pip install fastcmb`](https://pypi.org/project/fastcmb/) |
| **[CosmoRecon](https://github.com/salihyesil59/CosmoRecon)** | Model-independent reconstruction of H(z), d_L(z) and fσ₈(z), carried as a posterior over functions so correlations survive every null test, and an error budget that separates what the data measured from what the method chose. *Pre-alpha.* |
| **[Cosmos](https://github.com/salihyesil59/cosmos)** | An interactive desktop app that teaches cosmology from the basics to the research frontier: 58 lessons in 8 levels, 29 simulators built on real Pantheon+, SPARC, WMAP and SDSS data, quizzes with spaced repetition and a 206-term glossary, all on a physics engine verified against astropy. English and Turkish, with [downloads](https://github.com/salihyesil59/cosmos/releases/latest) for Windows, macOS and Linux. |
| **[string-th](https://github.com/salihyesil59/string-th)** | A simulation toolkit for string theory: worldsheet dynamics, the quantum spectrum, the critical dimension, T-duality, orbifolds, all five superstring theories and the two heterotic lattices, mirror symmetry, anomaly cancellation and D-branes, computed rather than quoted. Each layer must reproduce the one below it. |
| **[local-ai](https://github.com/salihyesil59/local-ai)** | A local AI platform that runs on your own computer: a local model in LM Studio with two agents that work in a loop until the job is done. The research agent searches your PDFs, offline Wikipedia and arXiv and writes cited reports; the coding agent plans, writes code, runs the tests and fixes what fails. Comes with a chat mode, Word reports and a SWE-bench Lite benchmark; its successful coding runs train the Qwen3.6-35B-A3B RFT model below. |
| **[Quantum-Computing](https://github.com/salihyesil59/Quantum-Computing)** | Replicating the quantum permutation algorithm of Yalçınkaya & Gedik, [PRA **96**, 062339](https://doi.org/10.1103/PhysRevA.96.062339). |
| **[antenna-length-calculator](https://github.com/salihyesil59/antenna-length-calculator)** | Monopole and dipole antenna lengths, worth writing once instead of re-deriving. |

### Open-weight models

| | |
|---|---|
| **[Qwen3.6-35B-A3B-RFT](https://huggingface.co/salihyesil59/Qwen3.6-35B-A3B-RFT-Agent-GGUF)** | Qwen3.6-35B-A3B fine-tuned by rejection sampling on its own shortest correct solutions in math, physics, tool calling and agentic Python; GPQA Diamond physics from 55% to 63%, MATH-500 with a Python tool from 61% to 71%. A second round, [Harness](https://huggingface.co/salihyesil59/Qwen3.6-35B-A3B-RFT-Harness-GGUF), learns from its own successful runs in the local-ai coding agent. Mixed Q4 GGUF for LM Studio, also in [Agent](https://huggingface.co/salihyesil59/Qwen3.6-35B-A3B-RFT-Agent-GGUF) and [Reasoning](https://huggingface.co/salihyesil59/Qwen3.6-35B-A3B-RFT-Reasoning-GGUF) variants. [`code`](https://github.com/salihyesil59/qwen3.6-35b-a3b-rft) |
| **[qwen3VL_Latex](https://huggingface.co/salihyesil59/qwen3VL_Latex)** | Qwen3-VL 8B fine-tuned to turn handwritten or printed mathematics into LaTeX. [`code`](https://github.com/salihyesil59/qwen3vl-8b-latex) |
| **[llama3.1-8b-physics](https://huggingface.co/salihyesil59/llama3.1-8b-physics)** | Llama 3.1 8B fine-tuned on physics, for explanation and question answering. [`code`](https://github.com/salihyesil59/llama3.1-8b-physics) |

---

Always happy to talk about cosmology, physics, mathematics or AI. Feel free to
get in touch.

[Website](https://salihyesil59.github.io/) · [Hugging Face](https://huggingface.co/salihyesil59)
