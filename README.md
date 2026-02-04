# LLM-Engineering-Projects
From Zero to Training Trillion Parameter Models- A concrete research roadmap.
Reason and know How Deepseek, KImi, Qwen, Llama and Closed Models are builded.

# LLM Engineering Projects

[![Follow on X](https://img.shields.io/badge/Follow-@marcoharuni-000000?style=for-the-badge&logo=x)](https://x.com/marcoharuni)
[![YouTube](https://img.shields.io/badge/YouTube-marcoharuni-FF0000?style=for-the-badge&logo=youtube)](https://youtube.com/@marcoharuni)

Welcome to this repository. You will find the code, maths, and explanations for all 20+ projects to dive deeper into the mechanics and reasoning behind modern LLMs like DeepSeek, LLaMA, Qwen, and more.

You will be able to build your own state-of-the-art large language model and understand the reason behind every architectural decision.

By working through these projects, you will gain deep intuition for how transformers actually work—not just using APIs, but understanding the mathematics, the engineering trade-offs, and why researchers made specific choices. You will know how to train models from scratch, optimize inference, scale to billions of parameters, and align models with human preferences.

<p align="center">
  <img src="assets/banner.png" alt="LLM Engineering Projects" width="800"/>
</p>

---

## List of Projects

I advise running all projects through **Google Colab** for the easiest setup. But if you have your own GPU locally or through a cloud provider, see the [Environment Setup Guide](docs/SETUP.md) for configuration instructions.

| S/N | Project | Video | Blog | Notebook |
|:---:|---------|:-----:|:----:|:--------:|
| 01 | Tokenization & Embeddings | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| 02 | Positional Embeddings | [▶️]() | [📝]() | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |

---

## Prerequisites

Before starting these projects, make sure you have foundational knowledge in these areas:

| # | Topic | Resource |
|:-:|-------|:--------:|
| 1 | Python, Mojo, Rust, C/C++ (at least one) | [Link]() |
| 2 | High School Mathematics: Algebra, Probability, Calculus, Geometry | [Link]() |
| 3 | Neural Networks & Deep Learning Fundamentals | [Link]() |
| 4 | PyTorch / JAX | [Link]() |
| 5 | GPU Programming (CUDA basics) | [Link]() |
| 6 | Pandas, NumPy, Matplotlib | [Link]() |
| 7 | CS Fundamentals (Data Structures & Algorithms) | [Link]() |
| 8 | Computer Architecture (GPU, CPU, Memory Hierarchy) | [Link]() |

---

## The Researcher's Mindset

**Ablate Everything** — Don't trust paper claims. Break the code. Swap RoPE for ALiBi mid-training. Does it die?

**Visualize Religiously** — Log attention maps to W&B every 100 steps. Plot activation histograms by layer.

**Data > Architecture > Hyperparams** — Spend 50% of time on data quality, 30% on architecture, 20% on hyperparameters.

**Scale Extrapolation** — Train 1M → 10M → 100M → 1B. Fit scaling laws. Predict 10B performance before training.

**Emergency Brakes** — NaN detection. Gradient norm tracking. Kill job if loss > 100 or NaN.

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
```

---

**Good luck on your journey.**
