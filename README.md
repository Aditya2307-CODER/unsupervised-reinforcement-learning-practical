# Unsupervised & Reinforcement Learning Practical

A beginner Colab practical on Unsupervised and Reinforcement Learning — K-Means customer segmentation plus a simple RL delivery-route example.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/unsupervised-reinforcement-learning-practical/blob/main/part-a/unsupervised-learning/Unsupervised_and_Reinforcement_Learning_Practical.ipynb)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Learning Objectives

By the end of this notebook, you will be able to:

- Understand customer segmentation using K-Means Clustering
- Observe how similar customers are grouped together
- Interpret clusters from a business point of view
- Understand the basic idea of Reinforcement Learning
- Identify Agent, Action, and Reward using a simple example

## Contents

### Part A — Customer Segmentation Using K-Means
A small retail dataset (monthly spending vs. app visits) is grouped into 3 clusters with `scikit-learn`'s `KMeans`, visualized with `matplotlib`, and interpreted from a business perspective (e.g. premium vs. low-engagement customers).

### Part B — Introduction to Reinforcement Learning
A simple delivery-route scenario (Route A vs. Route B) introduces the core RL loop — **Action → Reward → Learning** — along with the Agent / Environment / Action / Reward framework and the exploration-vs-exploitation trade-off.

## Repository Structure

```
.
├── part-a/
│   └── unsupervised-learning/
│       └── Unsupervised_and_Reinforcement_Learning_Practical.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```

## Getting Started

**Option 1 — Google Colab (recommended)**
Click the "Open in Colab" badge above.

**Option 2 — Run locally**
```bash
git clone https://github.com/YOUR-USERNAME/unsupervised-reinforcement-learning-practical.git
cd unsupervised-reinforcement-learning-practical
pip install -r requirements.txt
jupyter notebook part-a/unsupervised-learning/Unsupervised_and_Reinforcement_Learning_Practical.ipynb
```

## Requirements

- Python 3.8+
- pandas
- matplotlib
- scikit-learn

See [`requirements.txt`](requirements.txt) for exact packages.

## License

This project is licensed under the [MIT License](LICENSE).
