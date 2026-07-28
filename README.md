# 🤖 Machine Learning Masterclass — ML & Deep Learning Bible

> My personal comprehensive course and notes on Machine Learning, Deep Learning, and Data Science — from Python fundamentals and math foundations to Transformers, Vision models, and Transfer Learning with live in-browser Python execution.

## 🌐 Live Website

👉 **[https://muhammadanas20.github.io/Machine-Learning/](https://muhammadanas20.github.io/Machine-Learning/)**

---

## 🗂️ Course Roadmap & Curriculum

| Week | Section / Topic | Notebook | Datasets |
|:---:|---|---|:---:|
| **Week 01** | Python Programming Basics | `Week01_Python_Fundamentals.ipynb` | — |
| **Week 02** | Data Science Essentials (NumPy, Pandas, Seaborn) | `Week02_NumPy_Pandas_Visualization.ipynb` | — |
| **Week 03** | Mathematics for Machine Learning (Linear Algebra, Calculus) | `Week03_Math_for_ML.ipynb` | — |
| **Week 04** | Applied Probability, Statistics & Regression | `Week04_Applied_Probability_Statistics_Regression.ipynb` | — |
| **Week 05** | Introduction to Machine Learning (Linear/Logistic Reg, Trees) | `Week05_Train_Test_Regression_Classification.ipynb` | Telco Churn |
| **Week 06** | Feature Engineering & Pipelines (Encoding, Scaling, Selection) | `Week06_Feature_Engineering.ipynb` | Bike Sharing |
| **Week 07** | Advanced ML & Ensemble Methods (Random Forest, XGBoost) | `Week07_Ensemble_Methods.ipynb` | Telco Churn |
| **Week 08** | Model Tuning & Optimization (GridSearch, Optuna, CV) | `Week08_Hyperparameter_Tuning.ipynb` | Telco Full |
| **Week 09** | Deep Learning Foundations (ANN, Backprop, TensorFlow/PyTorch) | `Week09_Deep_Learning_Foundations.ipynb` | — |
| **Week 10** | Convolutional Neural Networks (CNNs, ResNet, Augmentation) | `Week10_CNNs_In_Depth.ipynb` | — |
| **Week 11** | Recurrent Neural Networks (SimpleRNN, LSTM, GRU, Seq2Seq) | `Week11_RNN_LSTM_GRU.ipynb` | — |
| **Week 12** | Transformers & Attention Mechanisms (Self-Attention, BERT, GPT) | `Week12_Transformers_Attention_BERT_GPT.ipynb` | — |
| **Week 13** | Transfer Learning & Fine-Tuning (ViT, LoRA, Capstone) | `Week13_Transfer_Learning_Fine_Tuning.ipynb` | — |

**Total: 13 Structured Weeks | 350+ Interactive Cells | 3 Real Datasets | Math Reference Book**

---

## ✨ Web App Features

- 🐍 **Pyodide Python WASM Runtime** — run Python code cells live inside your browser without any server backend. Pre-loaded with `NumPy`, `Pandas`, `Matplotlib`, and `Scikit-Learn`.
- 📊 **Matplotlib Chart Generation** — code cells automatically capture `plt.show()` and render high-resolution PNG plots directly below the cell.
- 📁 **Course Datasets Explorer** — inspect, preview, search, download, and load real CSV datasets (`Telco-Customer-Churn.csv`, `bike_sharing_daily.csv`, `Telco-Customer-Churn-Full.csv`) directly into the Python sandbox.
- 📖 **Jupyter Notebook Viewer** — renders `.ipynb` cells dynamically with Markdown parsing and KaTeX LaTeX math equation rendering ($...$, $$...$$).
- 📚 **Math Reference Book** — built-in viewer for `Machine learning maths book.pdf`.
- ⚡ **1-Click Google Colab & GitHub Launchers** — launch any notebook instantly on Colab or inspect on GitHub.
- 🔍 **Instant Search** — search across all 13 modules, topics, models, and datasets.
- ❤️ **Bookmarks & Progress Tracker** — save favorite notebooks and mark completed weeks to track progress.
- 🌙 **Neumorphic Dark / Light Mode** — modern UI design in dark and light themes.

---

## 🚀 How to Use

1. Open the **[Live Webpage](https://muhammadanas20.github.io/Machine-Learning/)**.
2. Select any Week from the course roadmap sidebar or overview grid.
3. Read notebook content and math formulas rendered inline.
4. Click **Run Cell** on any Python code block to execute code live in Pyodide.
5. Click **Datasets** in top header to explore course CSV files or **Python Sandbox** to experiment freely.

---

## 📁 Repository Structure

```
Machine-Learning/
├── index.html                                                      ← Interactive Web App
├── Machine learning maths book.pdf                                 ← Core Math Reference PDF
├── Section_02_Week_01_Python_Programming_Basics/                  ← Python Fundamentals
├── Section_03_Week_02_Data_Science_Essentials/                    ← NumPy & Pandas
├── Section_04_Week_03_Mathematics_for_Machine_Learning/           ← Linear Algebra & Calculus
├── Section_05_Week_04_Probability_and_Statistics/                 ← Stats & Regression
├── Section_06_Week_05_Introduction_to_Machine_Learning/           ← Telco Churn Dataset
├── Section_07_Week_06_Feature_Engineering_and_Model_Evaluation/   ← Bike Sharing Dataset
├── Section_08_Week_07_Advanced_Machine_Learning_Algorithms/       ← Ensemble Methods
├── Section_09_Week_08_Model_Tuning_and_Optimization/              ← Hyperparameter Tuning
├── Section_10_Week_09_Neural_Networks_and_Deep_Learning/          ← ANN Foundations
├── Section_11_Week_10_Convolutional_Neural_Networks/              ← CNN Architectures
├── Section_12_Week_11_Recurrent_Neural_Networks/                  ← LSTM & GRU
├── Section_13_Week_12_Transformers_and_Attention/                 ← BERT & GPT
└── Section_14_Week_13_Transfer_Learning_and_Fine_Tuning/          ← Fine-Tuning & Capstone
```

---

## 🛠️ Tech Stack

- **Python Runtime**: [Pyodide WebAssembly](https://pyodide.org/) (Python 3.11 WASM) + Judge0 CE API fallback
- **Frontend Core**: HTML5 + CSS3 + Vanilla JavaScript
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) + Custom Neumorphic Token System
- **Markdown & Math**: [marked.js](https://marked.js.org/) + [KaTeX](https://katex.org/)
- **Syntax Highlighting**: [highlight.js](https://highlightjs.org/) (Tokyo Night Dark)

---

*Built with ❤️ for Machine Learning & Deep Learning Mastery*
