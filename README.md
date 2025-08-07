# AI-Algorithms

Repositorio de **notebooks de aprendizaje automático** para la materia **Taller de Procesamiento de Señales**.  
Incluye implementaciones y experimentos con algoritmos clásicos de *ML* (clasificación, regresión, clustering y reducción de dimensionalidad), con enfoque práctico y reproducible.

---

## 📂 Estructura del proyecto

```text
AI-Algorithms/
│
├─ Algorithms/ # Notebooks por algoritmo
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

> Los nombres de los notebooks indican el método principal trabajado.

---

## 🧠 Contenido por tema

| Orden | Tema                                    | Notebook(s) asociado(s)             | Descripción breve |
|-------|-----------------------------------------|--------------------------------------|-------------------|
| 1     | Regresión Lineal, GD                    | `LinearRegression.ipynb`             | Regresión lineal y gradiente descendente. |
| 2     | Regresión Logística                     | `LogisticRegression.ipynb`          | Clasificación binaria. |
| 3     | LDA, QDA y kNN                           | `LDA_QDA_kNN.ipynb`                   | Clasificadores lineales, cuadráticos y vecinos cercanos. |
| 4     | SVM                                     | `SVM.ipynb`                          | Máquinas de vectores de soporte y kernels. |
| 5     | CART y Random Forest                    | `CART.ipynb`                         | Árboles y bósques de clasificación y regresión. |
| 6     | PCA y k-Means                             | `PCA.ipynb`, `EM_kMeans.ipynb`       | Reducción de dimensionalidad y clustering. |
| 7     | EM                    | `EM_kMeans.ipynb`                    | Expectation-Maximization y análisis factorial. |
| 8     | Aplicaciones                            | `LLM_SR.ipynb`                 | Modelos del lenguaje natural y sistemas de recomendación |
| 9    | GNB y MNB                                | `NaiveBayes.ipynb`                    | Clasificadores Naive Bayes gaussiano y multinomial. |
| 10    | GVB                                     | `VariationalBayes.ipynb`             | Inferencia variacional bayesiana. |
| 11    | Muestreo y PyMC                          | `PyMC.ipynb`                          | Modelado bayesiano y muestreo MCMC. |

---

## ✅ Requisitos

- **Python** 3.10+  
- **Jupyter** Notebook, **Google Collab**, etc.

### Paquetes principales

```bash
pip install -U pip
pip install numpy pandas scikit-learn matplotlib seaborn scipy sklearn
```

### Paquetes adicionales

```bash
# Para modelos bayesianos
pip install pymc arviz
```

---

## 🚀 Cómo empezar

```bash
# 1) Clonar
git clone https://github.com/felipeperassi/AI-Algorithms.git
cd AI-Algorithms

# 2) Instalar dependencias
pip install -U pip
pip install numpy pandas scikit-learn matplotlib seaborn scipy sklearn

# 3) Abrir Jupyter, Google Collab o tu editor de preferencia
jupyter notebook
```

> Abrí cualquier notebook dentro de Algorithms/ y ejecutá las celdas en orden.

> Cada notebook incluye celdas de **setup → preprocesamiento → entrenamiento → evaluación → conclusiones**.

---

## 📄 Licencia

Distribuido bajo licencia MIT. Ver `LICENSE` para más información.