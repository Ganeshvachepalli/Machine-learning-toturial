# Dimensionality Reduction Tutorial: PCA vs t-SNE  
### Student: Venkata Ganesh Reddy  
### Student ID: 23122289  
### Module: Machine Learning  
### University of Hertfordshire

---

## Overview

This project explores dimensionality reduction using two widely used techniques:

1. Principal Component Analysis (PCA) – a linear projection method  
2. t-Distributed Stochastic Neighbour Embedding (t-SNE) – a nonlinear manifold learning method  

The goal is to demonstrate how these techniques reveal structure in high-dimensional image data using the Fashion-MNIST dataset.

---

## Dataset

Fashion-MNIST (Zalando Research)  
- 28×28 grayscale images  
- 10 clothing categories  
- 3000 samples used for analysis  

### Class Labels

| Label | Class Name |
|-------|------------|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

---

## Project Structure

```
├── notebook.ipynb
├── README.md
├── requirements.txt
└── figures/
```

---

## How to Run

### 1. Install dependencies  
pip install -r requirements.txt

### 2. Open Jupyter  
jupyter notebook

### 3. Run notebook.ipynb  

---

## Reproducibility

- random_state=42 fixed  
- Fully open-source dependencies  
- No external data files required  

---

## Accessibility

- Colour-blind-friendly palette  
- Clear axis labels  
- Descriptive captions for all figures  

---

## Citations

Xiao et al. (2017). Fashion-MNIST.  
van der Maaten & Hinton (2008). Visualizing data using t-SNE.  
