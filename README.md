# Gradient Descent From Scratch 🚀

This repository demonstrates **Gradient Descent** in **1D** and **3D** using Python, NumPy, and Matplotlib.  
It provides animated plots to show how gradient descent moves towards minima.

---

## 📂 Project Structure
```
  gradient-descent-from-scratch/
  │── README.md
  │── requirements.txt
  │── gradient_descent_1d.py # Gradient descent on y = sin(x)
  └── gradient_descent_3d.py # Gradient descent on z = sin(5x)cos(5y)/5
```

---

## 🔧 Requirements

- Python 3.8+
- NumPy
- Matplotlib

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

### 🔹 1D Gradient Descent
```bash
python 1D/gradient_descent_1d.py
```
### This runs gradient descent on ```y = sin(x)``` and visualizes the iterative path to a local minimum.
### 🔹 3D Gradient Descent
```bash
python 3D/gradient_descent_3d.py
```
### This runs gradient decent on ```z(x,y)= sin(5x)cos(5y) / 5```
---
## 📘 Learning Outcomes

- Understand how gradient descent works in 1D and 3D.

- Visualize convergence to local minima.

- Experiment with different learning rates and starting points

