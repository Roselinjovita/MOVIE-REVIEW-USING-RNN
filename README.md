# MOVIE-REVIEW-USING-RNN


# 🎬 RNN-Based Movie Review Sentiment Analysis

This project uses a Recurrent Neural Network (RNN) to predict the sentiment (positive or negative) of IMDb movie reviews. The model is trained using TensorFlow/Keras and deployed using Streamlit for an interactive web interface.

---

## 📌 Project Overview

- **Dataset**: IMDb movie reviews (built into Keras)
- **Model**: Simple RNN using Embedding, SimpleRNN, and Dense layers
- **Task**: Sentiment classification (Positive or Negative)
- **Frontend**: Streamlit Web App
- **Output**: Web interface for users to input reviews and get predictions


---

## 🧠 Model Architecture

* 🔹 **Input Layer**: Sequences of fixed length
* 🔹 **RNN Layer**: `SimpleRNN` with ReLU or tanh activation
* 🔹 **Dense Output Layer**: Predicts next item in the sequence

**Training Configuration**:

* **Loss Function**: Mean Squared Error (MSE) or Categorical Crossentropy
* **Optimizer**: Adam
* **Epochs**: 50 (adjustable)
* **Batch Size**: 32

---

## 📊 Results

* ✅ Model learns sequential patterns effectively
* 🔍 Loss curve shows good convergence
* 🔮 Generates reasonable predictions on unseen data

---

## ⚠ Challenges and Solutions

| Challenge                                   | Solution                                       |
| ------------------------------------------- | ---------------------------------------------- |
| Difficulty capturing long-term dependencies | Consider using LSTM/GRU layers for improvement |
| Overfitting on small dataset                | Early stopping, regularization                 |
| Input data scaling                          | Applied normalization and reshaping            |

---

## ✅ Conclusion

This RNN model serves as a solid baseline for understanding sequence modeling. It can be extended to solve real-world problems like:

* Time series forecasting
* Text generation
* Stock prediction
* Weather forecasting

---







<img width="1913" height="961" alt="Screenshot 2025-07-31 124433" src="https://github.com/user-attachments/assets/a0030aaf-fda5-4d44-833e-a265413da799" />
