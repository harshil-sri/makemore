<div align="center">

# 🧠 Makemore: Neural Networks from Scratch

*My personal journey through character-level language models, inspired by Andrej Karpathy*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)

</div>



## 📂 Repository Structure

The project tracks my progression from simple models to more complex architectures across sequential Jupyter Notebooks:

| Module | Focus | Description |
| :--- | :--- | :--- |
| **[`Part 1`](./makemore%20part%201.ipynb)** | **Bigram Models** | Introduction to language models. Building the foundation using statistical counting and a simple neural network. |
| **[`Part 2`](./makemore%20part%202.ipynb)** | **MLP** | Implementing a Multi-Layer Perceptron following the Bengio et al. 2003 paper. |
| **[`Part 3`](./makemore%20part%203.ipynb)** | **Internals** | Deep dive into activations, gradients, initialization, and Batch Normalization. |
| **[`Part 4`](./makemore%20part%204.ipynb)** | **Backprop Ninja**| Advanced manual backpropagation and dealing with deeper network complexities. |
| **[`Final`](./makemore%20final.ipynb)** | **Full MLP Backprop** | Completing the manual backpropagation journey with a full MLP implementation from scratch. |

*Note: Models are trained on `names.txt`, a dataset of names used to generate new, unique character-level variations.*

---

## 🛠️ Tech Stack

- **Core:** Python 3
- **Deep Learning:** PyTorch *(Tensors, Autograd)*
- **Environment:** Jupyter Notebooks
- **Visualization:** Matplotlib *(Embeddings, activations, and loss curves)*

---

## 🎯 Achievements & Next Steps

- [x] Build a solid, intuitive understanding of manual backpropagation without relying entirely on PyTorch's `autograd`.
- [x] Master PyTorch tensor operations, broadcasting semantics, and memory management.
- [ ] Progress towards modern architectures like GRUs, LSTMs, and eventually **Transformers**.

<div align="center">
  <br>
  <i>"Throughout Heaven and Earth, I alone backpropagate manually" - Gojo Satoru (probably)</i>
</div>