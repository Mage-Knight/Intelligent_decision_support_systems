# 💻 Intelligent_decision_support_systems

This repository contains laboratory works written in Python and completed during the "Intelligent decision support systems" course at the National Technical University of Ukraine 'Kyiv Polytechnic Institute', IASA AI department, during the second semester of the master's program from February to June 2024. Use PyTorch library for deep learning, where GPU acceleration was utilized to boost training speed and sklearn for NLP.

---

## 🔬 Laboratory work 1

Data used:
- Artificial data generated using high-order polynomial.
- Netflix Stock Price data.

Tasks completed:
- Trained polynomial model (for Netflix data polynomial with multiple inputs) using backpropagation to predict the target value and visualize results.
- Performed Grid-search to find best hyperparameters for such training.

---

## 🔬 Laboratory work 2

- Data used:
    - gooogle-stock-price.

- Tasks completed:
    - Performed EDA and data preprocessing, including transformation into timeseries sequences for prediction.
    - Trained single/multilayered Basic RNN, LSTM and GRU based models with/without dropout using backpropagation to predict the target value and visualize results.
    - Performed Grid-search for these models to find best hyperparameters.
    - Evaluated obtained models using several metrics and performed their comparison.

---

## 🔬 Laboratory work 3 (a continuation of Laboratory work 2)

- Using different features from gooogle-stock-price next models were trained and compared for predicting target variable using different amount previous days data:
    - Univariate LSTM/GRU model.
    - Univariate/Multivariate single/multilayered LSTM/GRU Encoder-Decoder.
    - Exponentially smoothed LSTM/GRU Encoder.

---

## 🔬 Laboratory work 4 (a continuation of Laboratory work 3)

- Tasks completed:
    - Implemented next PyTorch modules:
        - TimeDistributed.
        - ConvLSTMCell.
        - LSTMConv2D.
        - RNNEncoderDecoder with different encoder options.
    - Using different features from gooogle-stock-price next models were trained and compared for predicting target variable using different amount previous days data:
        - Univariate/Multivariate single/multilayered Conv1D-LSTM/GRU Encoder-Decoder.
        - Univariate/Multivariate single/multilayered ConvLSTM2D-LSTM Encoder-Decoder.
    - Compared results with those obtained in Laboratory work 3.

---

## 🔬 Laboratory work 5

Tasks completed:
- Explored different ways of sentence vectorization:
    - bag-of-words.
    - n-gram.
- Assesed word importance using tf-idf, explored different values of hyperparameters.
- Performed stemming using Porter algorithm and SnowballStemmer.
- Removed stopwords from English and Ukrainian sentences.
- Preprocessed dataset obtained from fetch_20newsgroups and built a classifier pipeline for predicting a newsgroup (TfidfVectorizer, HashingVectorizer and word2vec tested).
- Found best hyperparameters using Grid-search.
- Performed topic modelling for fetch_20newsgroups using different vectorizer and LDA.

---

## 🔬 Laboratory work 6

Tasks completed:
- Trained Uni/Bidirectional Basic, LSTM or GRU-based RNN for binary text classification from fetch_20newsgroups and compared the results.
- Conducted tests with different max input sequence length values.

---

## 🔬 Laboratory work 7

- Performed different model comparisons for breast cancer classification, simultaneously considering several metrics using multiplicative synthesis with HCR and arithmetical normalization.