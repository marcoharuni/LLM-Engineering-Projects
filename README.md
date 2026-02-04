# LLM-Engineering-Projects
From Zero to Training Trillion Parameter Models- A concrete research roadmap.
Reason and know How Deepseek, KImi, Qwen, Llama and Closed Models are builded.

# LLM Engineering Projects

&lt;div align="center"&gt;

[![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)](https://x.com/marcoharuni)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/@marcoharuni)

&lt;/div&gt;

Welcome to this repository. You will find the code, maths, and explanations for all 20+ projects to dive deeper into the mechanics and reasoning behind modern LLMs like DeepSeek, LLaMA, Qwen, and more.

You will be able to build your own state-of-the-art large language model and understand the reason behind every architectural decision.

By working through these projects, you will gain deep intuition for how transformers actually work—not just using APIs, but understanding the mathematics, the engineering trade-offs, and why researchers made specific choices. You will know how to train models from scratch, optimize inference, scale to billions of parameters, and align models with human preferences.

&lt;p align="center"&gt;
  &lt;img src="assets/banner.png" alt="LLM Engineering Projects" width="800"/&gt;
&lt;/p&gt;

---

## List of Projects

I advise running all projects through **Google Colab** for the easiest setup. But if you have your own GPU locally or through a cloud provider, see the [Environment Setup Guide](docs/SETUP.md) for configuration instructions.

&lt;br&gt;

| S/N | Project | Video | Blog | Notebook |
|:---:|:---|:---:|:---:|:---:|
| 01 | Tokenization & Embeddings | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 02 | Positional Embeddings | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 03 | Attention Mechanisms | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 04 | Multi-Head & Grouped Query Attention | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 05 | Multi-Head Latent Attention (MLA) | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 06 | Sliding Window & Linear Attention | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 07 | Transformer Blocks & Normalization | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 08 | Mixture of Experts (MoE) | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 09 | Training at Scale: 3D Parallelism | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 10 | KV Cache & Inference Optimization | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 11 | Quantization & Compression | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 12 | Speculative Decoding | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 13 | RLHF & DPO Alignment | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 14 | Reasoning Models & GRPO | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 15 | Test-Time Compute & Inference Scaling | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 16 | Multimodal Vision-Language Models | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 17 | Long Context & RoPE Scaling | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 18 | Tool Use & Agent Architectures | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 19 | Evaluation & Interpretability | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 20 | Continuous Learning & Knowledge Editing | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |

&lt;br&gt;

---

## Prerequisites

Before starting these projects, make sure you have foundational knowledge in these areas:

| # | Topic | Resource |
|:-:|-------|:--------:|
| 1 | Python, Mojo, Rust, C/C++ | [Link]() |
| 2 | High School Mathematics: Algebra, Probability, Calculus, Geometry | [Link]() |
| 3 | Neural Networks & Deep Learning Fundamentals | [Link]() |
| 4 | PyTorch | [Link]() |
| 5 | GPU Programming (CUDA basics) | [Link]() |
| 6 | Pandas, NumPy, Matplotlib | [Link]() |
| 7 | CS Fundamentals (Data Structures & Algorithms) | [Link]() |
| 8 | Computer Architecture (GPU, CPU, Memory Hierarchy) | [Link]() |

---

## The Researcher's Mindset

**Ablate Everything** — Don't trust paper claims. Break the code. Swap RoPE for ALiBi mid-training. Does it die?

**Visualize Religiously** — Log attention maps to W&B every 100 steps. Plot activation histograms by layer.

**Data &gt; Architecture &gt; Hyperparams** — Spend 50% of time on data quality, 30% on architecture, 20% on hyperparameters.

**Scale Extrapolation** — Train 1M → 10M → 100M → 1B. Fit scaling laws. Predict 10B performance before training.

**Emergency Brakes** — NaN detection. Gradient norm tracking. Kill job if loss &gt; 100 or NaN.

---

## Citation

If you use this curriculum in your research or learning journey, please cite:

```bibtex
@misc{haruni2026llmengineering,
  author       = {Marco Haruni},
  title        = {LLM Engineering Projects: From Zero to Trillion-Parameter Training},
  year         = {2026},
  publisher    = {GitHub},
  howpublished = {\url{https://github.com/marcoharuni/LLM-Engineering-Projects}}
}
