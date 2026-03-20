<div align="center">

# 🧠 Deep Learning & Neural Networks

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![Keras](https://img.shields.io/badge/Keras-red?style=flat-square&logo=keras&logoColor=white)](https://keras.io)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A structured collection of **Deep Learning & Neural Network** lab experiments and assignments.  
Covers core concepts from forward propagation to convolutional neural networks.

[📂 Browse Notebooks](#-lab-notebooks) · [🚀 Getting Started](#-getting-started) · [🛠️ Tech Stack](#%EF%B8%8F-tech-stack)

</div>

---

## 📁 Lab Notebooks

| # | Notebook | Topic | Type |
|---|----------|-------|------|
| 1 | [`FORWARD PROPAGATION METHOD - ASSIGNMENT 1`](./FORWARD%20PROPAGATION%20METHOD%20-%20ASSIGNMENT%201) | Manual forward pass implementation from scratch | Assignment |
| 2 | [`CNN_Model_Building.ipynb`](./CNN_Model_Building.ipynb) | Convolutional Neural Network for image classification | Jupyter Notebook |

---

## 📖 Topics Covered

### ⚡ Forward Propagation — Assignment 1
> Manual implementation of the forward pass without deep learning libraries.

- Weight matrix multiplication and bias addition
- Activation functions: **Sigmoid**, **ReLU**, **Tanh**
- Layer-wise computation from input → hidden → output
- Building intuition for data flow before backpropagation

### 🖼️ CNN Model Building
> Constructing a Convolutional Neural Network using Keras/TensorFlow.

- `Conv2D` layers for spatial feature extraction
- `MaxPooling2D` for spatial downsampling
- `Flatten` + `Dense` layers for classification
- Model compilation, training, and evaluation on image data

---

## 🗺️ Conceptual Overview

```
Input Layer     Hidden Layers       Output Layer
   [ X ] ──→  [ W·X + b ] ──→  σ( ) ──→  [ ŷ ]
               ↑ ReLU / Sigmoid         ↑ Softmax

CNN Pipeline:
 Image ──→ Conv2D ──→ MaxPool ──→ Conv2D ──→ MaxPool ──→ Flatten ──→ Dense ──→ Class
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 Python 3 | Core language |
| 🔶 TensorFlow 2.x | Deep learning framework |
| 🔷 Keras | High-level model API |
| 🔢 NumPy | Numerical computation |
| 🐼 Pandas | Data manipulation |
| 📊 Matplotlib | Visualization & plots |
| 📓 Jupyter Notebook | Interactive lab environment |
| 🤗 scikit-learn | Preprocessing & utilities |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ShickenShawarma20/Deep-Learning-And-Neural-Network.git
cd Deep-Learning-And-Neural-Network
```

### 2. Install dependencies

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn jupyter
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

### 4. Open a notebook

Start with the **Forward Propagation assignment** to build foundational intuition, then move to the **CNN notebook** for applied image classification.

---

## 📂 Repository Structure

```
Deep-Learning-And-Neural-Network/
│
├── FORWARD PROPAGATION METHOD - ASSIGNMENT 1   # Manual forward pass (Assignment)
├── CNN_Model_Building.ipynb                    # CNN with Keras (Jupyter Notebook)
└── README.md
```

---

## 🧩 Key Concepts at a Glance

| Concept | Description |
|---------|-------------|
| **Forward Propagation** | Computing predictions from input to output layer |
| **Activation Functions** | Non-linear transforms — ReLU, Sigmoid, Softmax |
| **Convolutional Layers** | Feature extraction from spatial/image data |
| **Pooling** | Reducing spatial dimensions while retaining features |
| **Backpropagation** | Gradient-based weight updates (upcoming) |
| **Loss Functions** | Measuring prediction error — CrossEntropy, MSE |

---

## 🤝 Contributing

Contributions, issues, and suggestions are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/new-experiment`
3. Commit your changes: `git commit -m 'Add new lab notebook'`
4. Push to the branch: `git push origin feature/new-experiment`
5. Open a Pull Request

---

<div align="center">

Made with ❤️ and lots of matrix multiplications

⭐ **Star this repo** if you found it helpful!

</div>
