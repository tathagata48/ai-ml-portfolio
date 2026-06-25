<div align="center">

# 🧠 AI & Machine Learning

### A curated portfolio of deep learning labs and applied projects — from first principles to production-style pipelines

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)

<p>
  <img src="https://img.shields.io/github/last-commit/tathagata48/ai-ml-portfolio?style=flat-square&color=8b5cf6" alt="last commit"/>
  <img src="https://img.shields.io/github/languages/top/tathagata48/ai-ml-portfolio?style=flat-square&color=06b6d4" alt="top language"/>
  <img src="https://img.shields.io/github/repo-size/tathagata48/ai-ml-portfolio?style=flat-square&color=f59e0b" alt="repo size"/>
</p>

</div>

---

## 📖 Overview

This repository collects hands-on work across the modern machine-learning stack — supervised and
unsupervised learning, computer vision, sequence modeling, and generative models. Every notebook is
**self-contained and runnable end-to-end**, with data loading, model definition, training loops,
evaluation metrics, and visual analysis of the results.

The material is split into two tracks:

- **🔬 Machine Learning Labs** — foundational techniques built and trained from the ground up.
- **🚀 Deep Learning Projects** — applied, project-style notebooks tackling real datasets and tasks.

> 💡 Every notebook ships with an **"Open in Colab"** badge — click it to run on a free GPU, no setup required.

---

## 🔬 Machine Learning Labs

Foundational labs covering the core building blocks of modern ML, implemented primarily in **PyTorch**.

| # | Lab | What it covers | Stack |
|:-:|-----|----------------|-------|
| 01 | [**Classification**](machine-learning-labs/01-classification.ipynb) | Image classification, handling imbalanced data, custom CNNs & transfer learning | PyTorch · torchvision · scikit-learn |
| 02 | [**Image Segmentation**](machine-learning-labs/02-image-segmentation.ipynb) | Binary semantic segmentation — predicting pixel masks for road signs | PyTorch · torchvision |
| 03 | [**Monocular Depth Estimation**](machine-learning-labs/03-monocular-depth-estimation.ipynb) | Estimating per-pixel depth from a single RGB image | TensorFlow · Keras · scikit-image |
| 04 | [**Autoencoders**](machine-learning-labs/04-autoencoders.ipynb) | Unsupervised representation learning & reconstruction with autoencoders | PyTorch · torchvision |

---

## 🚀 Deep Learning Projects

Applied notebooks that take a task end-to-end on real-world data.

| Project | Description | Stack |
|---------|-------------|-------|
| [**CNN vs. ResNet-18**](deep-learning-projects/cnn-vs-resnet18-classification.ipynb) | Head-to-head comparison of a custom CNN against a transfer-learned ResNet-18 classifier | PyTorch · torchvision |
| [**YOLO Object Detection**](deep-learning-projects/yolo-object-detection.ipynb) | Real-time object detection with Ultralytics YOLO on a Roboflow dataset | Ultralytics · OpenCV · Roboflow |
| [**RNN: Time Series & Text Generation**](deep-learning-projects/rnn-timeseries-and-text-generation.ipynb) | LSTM/GRU for BTC/USD price forecasting **and** character-level text generation | PyTorch · yfinance |
| [**GAN Image Generation**](deep-learning-projects/gan-image-generation.ipynb) | Generative Adversarial Network for image synthesis, evaluated with FID | PyTorch · clean-fid · torch-fidelity |

---

## 🗂️ Repository Structure

```
ai-ml-portfolio/
├── machine-learning-labs/
│   ├── 01-classification.ipynb
│   ├── 02-image-segmentation.ipynb
│   ├── 03-monocular-depth-estimation.ipynb
│   └── 04-autoencoders.ipynb
├── deep-learning-projects/
│   ├── cnn-vs-resnet18-classification.ipynb
│   ├── yolo-object-detection.ipynb
│   ├── rnn-timeseries-and-text-generation.ipynb
│   └── gan-image-generation.ipynb
├── LICENSE
└── README.md
```

---

## 🛠️ Tech Stack

<div align="center">

| Domain | Tools |
|--------|-------|
| **Deep Learning** | PyTorch · torchvision · TensorFlow · Keras |
| **Computer Vision** | Ultralytics YOLO · OpenCV · scikit-image · Pillow |
| **Classic ML & Metrics** | scikit-learn · NumPy · pandas |
| **Visualization** | Matplotlib · seaborn |
| **Data & Tooling** | kagglehub · Roboflow · yfinance · tqdm |

</div>

---

## ⚡ Getting Started

### Option 1 — Google Colab (recommended)
Open any notebook and click the **"Open in Colab"** badge at the top. Colab provides a free GPU and
pre-installed libraries, so the notebooks run with little to no setup.

### Option 2 — Run locally

```bash
# 1. Clone the repository
git clone https://github.com/tathagata48/ai-ml-portfolio.git
cd ai-ml-portfolio

# 2. (Recommended) create a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Install the core dependencies
pip install torch torchvision tensorflow scikit-learn \
            matplotlib seaborn numpy pandas opencv-python \
            ultralytics kagglehub tqdm

# 4. Launch Jupyter
jupyter notebook
```

> Each notebook lists any project-specific dependencies in its first few cells.

---

## 📊 At a Glance

- **8** end-to-end notebooks across **6+** ML/DL domains
- Covers **classification, segmentation, depth estimation, detection, sequence modeling & generation**
- Built with both **PyTorch** and **TensorFlow/Keras**
- Designed to be **reproducible** and **GPU-ready** on Colab

---

## 📜 License

Released under the **MIT License** — see [`LICENSE`](LICENSE) for details.

<div align="center">

---

⭐ **If you find this useful, consider starring the repo!**

</div>
