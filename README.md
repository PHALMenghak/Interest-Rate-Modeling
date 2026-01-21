# QuantRates: Interest Rate Modeling

A computational finance project built with [Quarto](https://quarto.org/) and Python. This website visualizes and analyzes stochastic short-rate models used in quantitative finance.

## 📈 Models Covered

1.  **Vasicek Model (1977)**
    *   **Type:** Ornstein-Uhlenbeck Process.
    *   **Feature:** Mean-reverting.
    *   **Limitation:** Allows negative interest rates.
    *   **Equation:** $dr_t = \kappa(\theta - r_t)dt + \sigma dW_t$

2.  **Cox-Ingersoll-Ross (CIR) Model (1985)**
    *   **Type:** Square-root diffusion process.
    *   **Feature:** Mean-reverting and strictly positive rates (under Feller condition).
    *   **Equation:** $dr_t = \kappa(\theta - r_t)dt + \sigma \sqrt{r_t} dW_t$

## 🛠️ Technology Stack

*   **Framework:** [Quarto](https://quarto.org/) (Static Site Generator)
*   **Language:** Python 3.x
*   **Libraries:**
    *   `numpy` (Stochastic simulation)
    *   `matplotlib` (Visualization)
    *   `pandas` (Data handling)
    *   `jupyter` (Kernel execution)

## 🚀 Setup & Installation

### 1. Prerequisites
*   Install [Quarto CLI](https://quarto.org/docs/get-started/).
*   Install Python 3.8 or higher.

### 2. Install Python Dependencies
Run the following commands to install the required libraries and the Jupyter kernel interface.

**Note:** This includes `PyYAML` and `jupyter` to prevent Quarto kernel errors.

```bash
# Windows
pip install numpy matplotlib pandas jupyter PyYAML

# Mac/Linux
pip3 install numpy matplotlib pandas jupyter PyYAML