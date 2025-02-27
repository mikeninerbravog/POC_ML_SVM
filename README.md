# Support Vector Machine (SVM) - Proof of Concept (PoC)

This repository presents a **Proof of Concept (PoC)** for using **Support Vector Machine (SVM)**, a powerful classification algorithm, to solve real-world problems.  
The PoC includes two practical examples:

1. **Handwritten Digit Recognition:** Identifying numbers (0-9) written by hand, a key application in document processing and automated systems.
2. **Spam Detection:** Classifying emails as spam or not based on textual and sender characteristics.

---
## 🔍 **What is Support Vector Machine (SVM)?**
**Support Vector Machine (SVM)** is a supervised learning algorithm widely used for classification tasks. It works by identifying the best decision boundary (hyperplane) that separates different classes within a dataset.  

SVM is particularly effective for **high-dimensional data** and cases where the classes are not perfectly separable. It can use **linear and non-linear kernels** to improve classification performance.

---
## 📌 **Project Objective**
This PoC demonstrates how **SVM** can be applied to real-world classification problems, showcasing its ability to separate classes effectively based on feature inputs.

---
## **Example 1: Handwritten Digit Recognition**
This model classifies **handwritten digits (0-9)** based on pixel intensity patterns using the **MNIST dataset**. The process involves:

- **Converting digit images into numerical features**.
- **Training an SVM classifier** to recognize digit patterns.
- **Predicting new handwritten digits** with high accuracy.

This technique is used in:
- **Banking systems** for processing handwritten checks.
- **ATMs** that recognize handwritten account numbers.
- **Automated document digitization**.

---
## **Example 2: Spam Detection**
SVM is also used in **email filtering systems** to classify emails as **spam or not spam**.  
The model is trained based on:

- **Keywords in the email** (e.g., "free", "click here", "special offer").
- **Number of suspicious links**.
- **Sender reputation** (whether the sender has previously sent spam).

If the probability of an email being spam is **above a threshold**, it is marked as **spam**; otherwise, it is considered legitimate.  
This approach is commonly used in **email services, cybersecurity, and corporate mail filtering**.

---
## 📂 **Project Structure**
The code is available in Google Colab notebooks:

- [Handwritten Digit Recognition - Open in Colab](https://colab.research.google.com/github/mikeninerbravog/POC_SVM_HandwrittenDigits/blob/master/POC_SVM_HandwrittenDigits.ipynb)
- [Spam Detection - Open in Colab](https://colab.research.google.com/github/mikeninerbravog/POC_SVM_SpamDetection/blob/master/POC_SVM_SpamDetection.ipynb)

Each notebook includes:
- **Data preprocessing** for both use cases.
- **Training an SVM classifier** with a linear kernel.
- **Model evaluation and performance metrics**.
- **Visualization of classification results**.

---
## ⚙ **How to Run the Code**
You can execute the code directly in **Google Colab** without any local setup.

### **Steps to Run in Colab:**
1. Click on the **Open in Colab** link for the example you want to test.
2. Run each cell sequentially in the notebook.
3. Explore the predictions, accuracy reports, and visualizations.

---
## 📊 **Expected Results**
Each notebook provides:
- **Accuracy scores** for model evaluation.
- **Confusion matrix** to analyze classification errors.
- **Predicted results** for new handwritten digits and emails.
- **Precision, recall, and F1-score** for both examples.

---
## 🚀 **Why Use SVM for These Problems?**
✔ Works well with **high-dimensional data**, such as images and text.  
✔ Provides a **clear decision boundary** for classification.  
✔ Can be used with **linear and non-linear kernels** to improve accuracy.  
✔ Widely used in **document processing, cybersecurity, and automation**.

---
## 📜 **License**
This project is licensed under the MIT License - see the `LICENSE` file for details.
