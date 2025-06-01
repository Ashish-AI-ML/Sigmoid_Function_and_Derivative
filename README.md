# 🧠 Sigmoid Function with Derivative – Visualization and Explanation

This project provides a comprehensive explanation and visualization of the **Sigmoid activation function** and its **derivative**, both of which are essential in neural networks, logistic regression, and binary classification tasks.

---

## 🔣 Sigmoid Function

### Mathematical Formula
\[
\sigma(x) = \frac{1}{1 + e^{-x}}
\]

### Key Characteristics
- **Purpose**: Maps real-valued inputs to the range **(0, 1)**.
- **Shape**: S-shaped (sigmoidal) curve.
- **Range**: Output always between 0 and 1.
- **Interpretation**: Often used as a **probability-like output**.

---

## 📈 Derivative of the Sigmoid Function

### Formula
\[
\sigma'(x) = \sigma(x)(1 - \sigma(x))
\]

### Key Insights
- **Peaks at** \( x = 0 \)
- **Flattens** out as \( |x| \) increases, leading to **vanishing gradients**
- **Use in Backpropagation**: Guides the weight update during training by calculating how much the output changes with respect to inputs

---

## 📊 Visualization

This project includes:
- 📉 Plot of the **Sigmoid function**
- 📉 Plot of its **derivative**

These plots illustrate:
- Non-linearity and smoothness
- How the gradient behaves across different inputs
- Where the function saturates (near 0 and 1)

---

## 💡 Why This Matters

| Feature              | Sigmoid Function           |
|----------------------|----------------------------|
| **Output Range**     | (0, 1)                     |
| **Use Case**         | Binary classification      |
| **Non-linearity**    | Yes                        |
| **Derivative Shape** | Peaks at 0, drops at edges |
| **Output Meaning**   | Probability-like values    |

---

## 💻 Usage Instructions

### ✅ Requirements

Install required libraries:

```bash
pip install numpy matplotlib
