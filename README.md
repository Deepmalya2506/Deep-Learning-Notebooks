# Deep Learning Notebooks

This repository is dedicated to housing my deep learning projects, experiments, and practice notebooks.  
It serves as a personal collection of implementations, starting from foundational concepts and gradually progressing toward more advanced architectures.

---

## 📂 Projects Included

### 1. MNIST Digit Classification (ANN)
- **Dataset:** MNIST handwritten digits (28x28 grayscale images)  
- **Approach:** Artificial Neural Network (ANN) with dense layers  
- **Highlights:**  
  - Flattened image input (784 features)  
  - Multiple hidden layers with ReLU activation  
  - Softmax output for 10 digit classes  
- **Outcome:** Achieved strong baseline accuracy using a simple ANN model.

### 2. Customer Churn Prediction (ANN)
- **Dataset:** Customer churn dataset (tabular data)  
- **Approach:** ANN applied to structured features  
- **Highlights:**  
  - Dense layers with ReLU activation  
  - Experimentation with optimizers and loss functions  
  - Focus on understanding ANN’s capability on non‑image/tabular data  
- **Outcome:** Demonstrated ANN’s effectiveness in predicting churn probabilities.

### 3. CNN Insights – Dogs vs Cats Classification
- **Dataset:** Dogs vs Cats image dataset  
- **Approach:** Convolutional Neural Network (CNN) with TensorFlow/Keras  
- **Highlights:**  
  - Data preprocessing using `shutil` and `ImageDataGenerator` for efficient volume handling  
  - Baseline CNN model (Model1) achieved strong accuracy but showed overfitting  
  - Enhanced CNN (Model2) with Batch Normalization and Dropout layers to address overfitting  
  - Comparative analysis of model performance and generalization  
- **Outcome:** Gained insights into CNN regularization techniques and their impact on training stability and test accuracy.

---

## 🚀 Future Plans
- Extend projects to more **CNN architectures** for image tasks.  
- Explore **RNNs/LSTMs** for sequence data.  
- Add **transformer‑based models** for NLP experiments.  
- Maintain clear, notebook‑friendly explanations for each project.  

---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** TensorFlow / Keras, NumPy, Matplotlib  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 📖 Usage
Clone the repository and open notebooks in Jupyter or Colab:

```bash
git clone https://github.com/Deepmalya2506/Deep-Learning-Notebooks.git
cd Deep-Learning-Notebooks
