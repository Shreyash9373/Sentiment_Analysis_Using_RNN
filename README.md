#  RNN for Sentiment Analysis

This project implements a **Recurrent Neural Network (RNN)** for performing **sentiment analysis** on textual data. The model learns to classify text inputs (such as reviews or sentences) into sentiment categories like **positive** or **negative**.

---

## 🚀 Features

* Text preprocessing and cleaning
* Tokenization and sequence encoding
* Padding for uniform input length
* RNN-based deep learning model
* Model training and evaluation
* Sentiment prediction on custom inputs

---

## 📁 Project Structure

```
.
├── RNN_for_sentimentanalysis.ipynb   # Main notebook with implementation
├── README.md                        # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/your-username/rnn-sentiment-analysis.git
cd rnn-sentiment-analysis
```

### 2. (Optional) Create a virtual environment

```
conda create -n rnn_env python=3.10
conda activate rnn_env
```

### 3. Install dependencies

```
pip install numpy pandas matplotlib scikit-learn torch
```

---

## 🧠 Model Overview

The model uses a **Recurrent Neural Network (RNN)** to process sequential text data.

### Workflow:

1. Data preprocessing (cleaning & normalization)
2. Tokenization and conversion to sequences
3. Padding sequences to fixed length
4. Passing sequences through RNN layers
5. Fully connected layer for classification

---

## 📊 Training Details

* **Input:** Text sequences
* **Output:** Sentiment labels (Positive / Negative)
* **Loss Function:** Binary Cross Entropy / CrossEntropy
* **Optimizer:** Adam

---

## ▶️ How to Run

1. Start Jupyter Notebook:

```
jupyter notebook
```

2. Open:

```
RNN_for_sentimentanalysis.ipynb
```

3. Run all cells step-by-step.

---

## 🧪 Example Usage

```
text = "This product is really good!"
prediction = model.predict(text)
print(prediction)  # Output: Positive
```

---

## 📈 Results

* The model learns patterns in text to predict sentiment
* Performance improves with better preprocessing and tuning
* Accuracy depends on dataset size and quality

---

## ⚠️ Limitations

* Basic RNN struggles with long-term dependencies
* May not perform well on very long texts

---

## 🔮 Future Improvements

* Replace RNN with LSTM or GRU
* Use pretrained embeddings (GloVe, Word2Vec)
* Add attention mechanism
* Build a web app for real-time predictions

---

## 🤝 Contributing

Feel free to fork the repository and submit pull requests.

---
