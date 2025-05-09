# The Double Ellipsoid Geometry of CLIP

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/double-ellipsoid-clip/blob/main/ellipsoid_geometry.ipynb)
[![Paper](https://img.shields.io/badge/Paper-ICML%202025-blue)](https://arxiv.org/abs/2411.14517)

> Official implementation of **The Double Ellipsoid Geometry of CLIP**, accepted at ICML 2025.

CLIP embeddings are not merely distributed on a single hypersphere — they exhibit a *double ellipsoid* geometry: separate, off-centered, anisotropic distributions for text and image modalities. Our paper uncovers and analyzes this structure, revealing its implications for alignment, interpolation, and representation learning.

---

## 🚀 Highlights
- ✦ **New geometric insight**: text/image distributions occupy shifted ellipsoids, not co-centered hyperspheres  
- ✦ **Improved understanding** of cosine similarity biases in CLIP-style models  
- ✦ **Simple visualizations** to reproduce and explore the geometry  
- ✦ **Colab-compatible notebook** to experiment with your own data

---

## 📓 Try it on Google Colab

Click the badge to launch the interactive notebook:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/double-ellipsoid-clip/blob/main/ellipsoid_geometry.ipynb)

---

## 🧠 Paper

> **The Double-Ellipsoid Geometry of CLIP**  
> Meir Yossef Levi, Guy Gilboa
> _International Conference on Machine Learning (ICML), 2025_  
> [[arXiv link]](https://arxiv.org/abs/2411.14517) • [[Conference page]](https://icml.cc/virtual/2025/poster/45348)

---

## 📈 Example Visualizations

<p align="center">
  <img src="assets/clip_ellipsoid_overview.png" alt="Ellipsoid geometry of CLIP" width="70%">
</p>

---

## 📦 Installation

You can run the notebook directly in Colab, or clone locally:

```bash
git clone https://github.com/YOUR_USERNAME/double-ellipsoid-clip.git
cd double-ellipsoid-clip
pip install -r requirements.txt

