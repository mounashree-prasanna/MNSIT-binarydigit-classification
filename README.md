# Binary Classification on MNIST (Digits 0 & 3)

This notebook implements a binary classifier to distinguish between MNIST digits **0** and **3** using a feed-forward neural network.

---

## 📌 Overview
- Load MNIST dataset and filter digits 0 & 3  
- Normalize pixel values and flatten images  
- Split into training, validation, and test sets  
- Build a neural network with:
  - Dense(128, ReLU)
  - Dropout(0.3)
  - Dense(64, ReLU)
  - Dense(1, Sigmoid)
- Train with **EarlyStopping** (monitoring validation loss)

---

## 🧪 Experiments
Tested combinations of:
- **Initializers:** Normal, He Normal, Xavier (Glorot Normal)  
- **Activation functions:** ReLU, Sigmoid, Tanh  

Metrics used:
- Accuracy  
- Confusion matrix  
- Precision, Recall, F1  
- Loss curves

---

## 📈 Key Results
- Test Accuracy: **> 99%**
- Stable training curves with early stopping  
- Clear performance differences across initializer × activation combinations  

---

## 🛠️ Libraries
TensorFlow • Keras • NumPy • Pandas • Matplotlib • Seaborn • scikit-learn

