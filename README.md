# AI-Algorithms

Repository of **machine learning notebooks** for the **Signal Processing Workshop** course.
Includes implementations and experiments with classic ML algorithms (classification, regression, clustering, and dimensionality reduction), with a practical and reproducible approach.

---

## 📂 Project structure

```text
AI-Algorithms/
│
├─ Algorithms/ # Notebooks by algorithm
│ ├─ LinearRegression.ipynb 
│ ├─ LogisticRegression.ipynb
│ ├─ LDA_QDA_kNN.ipynb
│ ├─ SVM.ipynb 
│ ├─ CART.ipynb 
│ ├─ PCA.ipynb 
│ ├─ EM_kMeans.ipynb 
│ ├─ LLM_SR.ipynb 
│ ├─ NaiveBayes.ipynb
│ ├─ VariationalBayes.ipynb 
│ └─ PyMC.ipynb 
│
├─ LICENSE
│
└─ README.md
```

> The notebook names indicate the main method covered.

---

## 🧠 Contenido por tema

| Order | Topic                  | Associated notebook(s)         | Short description                                    |
| ----- | ---------------------- | ------------------------------ | ---------------------------------------------------- |
| 1     | Linear Regression      | `LinearRegression.ipynb`       | Linear regression and gradient descent.              |
| 2     | Logistic Regression    | `LogisticRegression.ipynb`     | Binary classification.                               |
| 3     | LDA, QDA, and kNN      | `LDA_QDA_kNN.ipynb`            | Linear, quadratic, and nearest neighbor classifiers. |
| 4     | SVM                    | `SVM.ipynb`                    | Support vector machines and kernels.                 |
| 5     | CART and Random Forest | `CART.ipynb`                   | Classification and regression trees and forests.     |
| 6     | PCA and k-Means        | `PCA.ipynb`, `EM_kMeans.ipynb` | Dimensionality reduction and clustering.             |
| 7     | EM                     | `EM_kMeans.ipynb`              | Expectation-Maximization and factor analysis.        |
| 8     | Applications           | `LLM_SR.ipynb`                 | Natural language models and recommendation systems.  |
| 9     | GNB and MNB            | `NaiveBayes.ipynb`             | Gaussian and multinomial Naive Bayes classifiers.    |
| 10    | GVB                    | `VariationalBayes.ipynb`       | Bayesian variational inference.                      |
| 11    | Sampling and PyMC      | `PyMC.ipynb`                   | Bayesian modeling and MCMC sampling.                 |

---

## ✅ Requirements

- **Python** 3.10+  
- **Jupyter** Notebook, **Google Collab**, etc.

### Main packages

```bash
pip install -U pip
pip install numpy pandas scikit-learn matplotlib seaborn scipy sklearn
```

### Additional packages

```bash
# Para modelos bayesianos
pip install pymc arviz
```

---

## 🚀 Getting started

```bash
# 1) Clone
git clone https://github.com/felipeperassi/AI-Algorithms.git
cd AI-Algorithms

# 2) Install dependencies
pip install -U pip
pip install numpy pandas scikit-learn matplotlib seaborn scipy sklearn

# 3) Open Jupyter, Google Colab, or your preferred editor
jupyter notebook
```

> Open any notebook inside Algorithms/ and run the cells in order.

> Each notebook includes cells for **setup → preprocessing → training → evaluation → conclusions**.

---

## 📄 Licence

Distributed under the MIT License. See `LICENSE` for more information.
