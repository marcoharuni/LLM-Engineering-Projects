<div align="center">

<h1>
LLM Engineering Projects
</h1>

<p>
<a href="https://x.com/marcoharuni">
  <img src="https://img.shields.io/badge/Follow%20on%20𝕏-@marcoharuni-000000?style=for-the-badge&logo=x&logoColor=white"/>
</a>
&nbsp;&nbsp;
<a href="https://youtube.com/@marcoharuni">
  <img src="https://img.shields.io/badge/Subscribe-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
</a>
&nbsp;&nbsp;
<a href="https://github.com/marcoharuni/LLM-Engineering-Projects">
  <img src="https://img.shields.io/badge/Star%20on-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>

<br>

<img src="assets/banner.png" width="1000"/>

<br><br>

<p>
<b>Build modern Large Language Models from mathematics to trillion-parameter systems.</b>
</p>

<p>
Code, maths, and explanations for 20+ projects covering the mechanics and reasoning behind<br>
modern LLMs like <b>DeepSeek</b>, <b>LLaMA</b>, <b>Qwen</b>, <b>Mistral</b>, and more.
</p>

<p>
You will be able to build your own state-of-the-art large language model<br>
and understand the reason behind every architectural decision.
</p>

</div>

---

## 🎯 What You Will Learn

By working through these projects, you will:

- **Understand transformers deeply** — not just using APIs, but the mathematics and engineering trade-offs
- **Build from scratch** — tokenizers, attention mechanisms, optimizers, and full training pipelines
- **Train models at scale** — from 1M to 1B+ parameters with distributed systems
- **Optimize inference** — KV cache, speculative decoding, quantization
- **Align models** — instruction tuning, RLHF, DPO, and test-time compute

---

## 📋 Prerequisites

Before starting these projects, make sure you have foundational knowledge in these areas:

<table>
<tr>
<th align="center">S/N</th>
<th align="left">Topic</th>
<th align="center">Resource</th>
</tr>
<tr>
<td align="center">1</td>
<td><b>Python, Mojo, Rust, C/C++</b> (at least one)</td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
<tr>
<td align="center">2</td>
<td><b>High School Mathematics</b> (Algebra, Probability, Calculus, Geometry)</td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
<tr>
<td align="center">3</td>
<td><b>Neural Networks & Deep Learning Fundamentals</b></td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
<tr>
<td align="center">4</td>
<td><b>PyTorch / JAX</b></td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
<tr>
<td align="center">5</td>
<td><b>GPU Programming</b> (CUDA basics)</td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
<tr>
<td align="center">6</td>
<td><b>Pandas, NumPy, Matplotlib</b></td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
<tr>
<td align="center">7</td>
<td><b>CS Fundamentals</b> (Data Structures & Algorithms)</td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
<tr>
<td align="center">8</td>
<td><b>Computer Architecture</b> (GPU, CPU, Memory Hierarchy)</td>
<td align="center"><a href="">📎 Link</a></td>
</tr>
</table>

---

## 📚 List of Projects

I advise running all projects through **Google Colab** for the easiest setup. If you have your own GPU locally or through a cloud provider, see the **[Setup Guide](docs/SETUP.md)**.

<table>
<tr>
<th align="center">S/N</th>
<th align="left">Project</th>
<th align="center">Video</th>
<th align="center">Blog</th>
<th align="center">Notebook</th>
</tr>
<tr>
<td align="center"><b>01</b></td>
<td>Tokenization & Embeddings</td>
<td align="center"><a href="">▶️</a></td>
<td align="center"><a href="">📝</a></td>
<td align="center"><a href=""><img src="https://colab.research.google.com/assets/colab-badge.svg" height="20"/></a></td>
</tr>
<tr>
<td align="center"><b>02</b></td>
<td>Positional Embeddings</td>
<td align="center"><a href="">▶️</a></td>
<td align="center"><a href="">📝</a></td>
<td align="center"><a href=""><img src="https://colab.research.google.com/assets/colab-badge.svg" height="20"/></a></td>
</tr>
</table>

<!--
TO ADD MORE PROJECTS:
Copy the template below and paste it ABOVE this comment (before </table>)

<tr>
<td align="center"><b>03</b></td>
<td>Project Name Here</td>
<td align="center"><a href="">▶️</a></td>
<td align="center"><a href="">📝</a></td>
<td align="center"><a href=""><img src="https://colab.research.google.com/assets/colab-badge.svg" height="20"/></a></td>
</tr>

Then:
1. Change the number (03, 04, 05...)
2. Change "Project Name Here" to your project title
3. Add your video URL inside href=""
4. Add your blog URL inside href=""
5. Add your Colab URL inside href=""
-->

---

## 🧠 The Researcher's Mindset

| Principle | Description |
|-----------|-------------|
| **Ablate Everything** | Don't trust paper claims. Break the code. Swap RoPE for ALiBi mid-training. Does it die? |
| **Visualize Religiously** | Log attention maps to W&B every 100 steps. Plot activation histograms by layer. |
| **Data > Architecture > Hyperparams** | Spend 50% of time on data quality, 30% on architecture, 20% on hyperparameters. |
| **Scale Extrapolation** | Train 1M → 10M → 100M → 1B. Fit scaling laws. Predict 10B performance before training. |
| **Emergency Brakes** | NaN detection. Gradient norm tracking. Kill job if loss > 100 or NaN. |

---

## 📖 Citation

If you use this curriculum in your research or learning journey:

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

<div align="center">

<b>Lock in. Build. Break. Plot. Repeat.</b>

<br>

**Good luck on your journey.**

</div>
