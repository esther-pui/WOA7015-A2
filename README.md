# Logistic Regression: From Scratch to PyTorch

## Project Overview
* **Title:** Individual Assignment 2
* **Course:** WOA7015 Advanced Machine Learning
* **School:** Universiti Malaya (**Master in Artificial Intelligence**)
* **Date:** 26th October 2025 - 1st November 2025

### ⚠️ Disclaimer: Personal Learning & Reference Only
This project is a deliverable for the WOA7015 Advanced Machine Learning course at Universiti Malaya. It represents my from-scratch implementation of Logistic Regression and its Gradient Descent algorithm, intended to document my understanding and learning journey in machine learning fundamentals.

The code should be viewed as educational material and a personal work portfolio, not as a production-ready library. It is shared strictly for reference and documentation purposes.

---

## 🌟 Task Summary

1.  **From Scratch (NumPy):** Implement six functions for a Logistic Regression model from scratch using **NumPy** to train on the toy data.
2.  **Benchmark (PyTorch):** Use **PyTorch** built-in functions to train and test the same model.
3.  **Analysis:** Compare the two model's testing accuracies in a report.

---

## 💡 Implementation: Six Mandatory Functions

The custom model is built by implementing the core optimization steps of **Gradient Descent** manually. The six required functions handle the entire training and testing lifecycle:

| # | Function Name | Mathematical Role |
| :---: | :--- | :--- |
| **1** | `CalcObj` | Calculates **Binary Cross-Entropy Loss** |
| **2** | `CalcGrad` | Calculates the **Gradient** |
| **3** | `UpdateParams` | Updates the **Weights** |
| **4** | `CheckConvg` | Determines **Convergence** |
| **5** | `GradientDescent` | The **Main Training Loop** |
| **6** | `PredictLabels` | Calculates **Test Predictions & Errors** |

---

## 💖 How to Run

| Document | Link Shorcut |
| :--- | :--- |
| **Source Code** | [View Executable Code on Google Colab](https://colab.research.google.com/drive/1g1hC4IxCCDBwawFFaYpd0Ii3uV2xdMOM?usp=sharing)|
| **Report** | [View Final Report (Google Doc/PDF)](https://docs.google.com/document/d/1uFSvaVnrw-Vob7Fx98BWq0fHy80aJEyy-mi74WAc0Wk/edit?usp=sharing)|

The entire project is contained within an **iPython Notebook (`.ipynb`)**.

1.  **Environment:** Use **Google Colab** (recommended) or a local Jupyter setup.
2.  **Data:** Ensure `Train_toydata.txt` and `Test_toydata.txt` are available in the execution environment.
3.  **Execution:** Run all cells sequentially to perform data preparation, custom training, PyTorch benchmarking, and final report generation.
