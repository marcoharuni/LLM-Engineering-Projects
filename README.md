# 🚀 LLM Engineering Projects

<p align="center">
  <a href="https://x.com/marcoharuni">
    <img src="https://img.shields.io/badge/X-@marcoharuni-111111?style=for-the-badge&logo=x&logoColor=white"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://youtube.com/@marcoharuni">
    <img src="https://img.shields.io/badge/YouTube-marcoharuni-ff0000?style=for-the-badge&logo=youtube&logoColor=white"/>
  </a>
</p>

<p align="center">
  <b>Modern LLM Engineering Curriculum — from math to trillion-parameter systems</b>
</p>

<p align="center">
  <img src="assets/banner.png" alt="LLM Engineering Projects" width="900"/>
</p>

---

## 🧠 Prerequisites

| ⭐ | Topic | Resource |
|:--:|-------|:--------:|
| 1 | Python, Mojo, Rust, C/C++ | [Link]() |
| 2 | High School Mathematics: Algebra, Probability, Calculus, Geometry | [Link]() |
| 3 | Neural Networks & Deep Learning Fundamentals | [Link]() |
| 4 | PyTorch | [Link]() |
| 5 | GPU Programming (CUDA basics) | [Link]() |
| 6 | Pandas, NumPy, Matplotlib | [Link]() |
| 7 | CS Fundamentals (Data Structures & Algorithms) | [Link]() |
| 8 | Computer Architecture (GPU, CPU, Memory Hierarchy) | [Link]() |

---

## 📚 List of Projects

<p align="center">
  <b>Run projects using Google Colab for the easiest setup</b>
</p>

<table align="center" width="100%">
<tr>
<th>S/N</th>
<th>Project</th>
<th>Video</th>
<th>Blog</th>
<th>Notebook</th>
</tr>

<tr>
<td align="center"><b>01</b></td>
<td><b>Tokenization & Embeddings</b></td>
<td align="center">▶️</td>
<td align="center">📝</td>
<td align="center">
<img src="https://colab.research.google.com/assets/colab-badge.svg"/>
</td>
</tr>

<tr>
<td align="center"><b>02</b></td>
<td><b>Positional Embeddings</b></td>
<td align="center">▶️</td>
<td align="center">📝</td>
<td align="center">
<img src="https://colab.research.google.com/assets/colab-badge.svg"/>
</td>
</tr>

</table>

---

## 🧪 The Researcher's Mindset

**Ablate Everything** — Don't trust paper claims. Break the code. Swap RoPE for ALiBi mid-training. Does it die?

**Visualize Religiously** — Log attention maps to W&B every 100 steps. Plot activation histograms by layer.

**Data > Architecture > Hyperparams** — Spend 50% of time on data quality, 30% on architecture, 20% on hyperparameters.

**Scale Extrapolation** — Train 1M → 10M → 100M → 1B. Fit scaling laws. Predict 10B performance before training.

**Emergency Brakes** — NaN detection. Gradient norm tracking. Kill job if loss > 100 or NaN.

---

## 📖 Citation

```bibtex
@misc{haruni2026llmengineering,
  author       = {Marco Haruni},
  title        = {LLM Engineering Projects: From Zero to Trillion-Parameter Training},
  year         = {2026},
  publisher    = {GitHub},
  howpublished = {\url{https://github.com/marcoharuni/LLM-Engineering-Projects }}
}
