# IMDb Sentiment Analysis with BiLSTM

This project is a Natural Language Processing and Deep Learning coursework project focused on **IMDb movie review sentiment analysis**.

The aim of the project is to classify movie reviews as positive or negative using text preprocessing, word embeddings, and a Bidirectional LSTM neural network.

The notebook includes the full machine learning workflow, including data loading, text cleaning, tokenisation, lemmatisation, embedding preparation, model training, hyperparameter testing, and model evaluation.

---

## Project Timeline

* **Originally completed:** 2024
* **Refactored and published on GitHub:** 2026
* **Context:** Bachelor’s Advanced Topics in AI and Data Science coursework project

This repository has been cleaned and documented for portfolio purposes.

---

## Dataset

The project uses an IMDb movie review sentiment dataset.

The dataset is **not included** in this repository.
Please download the dataset using the link provided inside the notebook.

After downloading, place the dataset in a local `data/` folder or update the notebook path to match your local environment.

Example structure:

```text
data/
└── IMDB_Dataset.csv
```

The `data/` folder is intentionally ignored by Git.

---

## Word Embeddings

This project uses **GloVe word embeddings**.

The GloVe embedding file is **not included** in this repository because it is large.
Please download GloVe separately and place the file locally.

Example:

```text
embeddings/
└── glove.6B.100d.txt
```

Then update the GloVe file path inside the notebook if needed.

---

## Project Features

* IMDb review sentiment classification
* Text preprocessing
* HTML tag removal
* Punctuation and special character cleaning
* Tokenisation using NLTK
* Stopword removal with sentiment-aware exceptions
* Lemmatisation
* GloVe word embedding integration
* Train/test split
* Bidirectional LSTM model using TensorFlow/Keras
* Dropout and batch normalisation
* Hyperparameter testing
* Confusion matrix
* Accuracy, precision, recall, and F1-score evaluation

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* scikit-learn
* TensorFlow/Keras
* GloVe word embeddings
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```text
.
├── imdb_sentiment_analysis_bilstm.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

1. Clone the repository.

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Download the IMDb dataset using the link provided in the notebook.

4. Download the GloVe embeddings and place them locally, for example:

```text
embeddings/glove.6B.100d.txt
```

5. Open the notebook:

```text
imdb_sentiment_analysis_bilstm.ipynb
```

6. Update the dataset and GloVe file paths if required.

7. Run the notebook cells from top to bottom.

---

## Model Summary

The final model uses a **Bidirectional LSTM** architecture for binary sentiment classification.

The workflow includes:

* converting text to sequences
* padding sequences
* using pre-trained GloVe embeddings
* training a BiLSTM model
* evaluating performance using classification metrics

---

## Evaluation Metrics

The notebook evaluates the model using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

---

## What I Learned

Through this coursework project, I practised:

* Building an NLP pipeline for sentiment analysis
* Cleaning and preprocessing text data
* Using NLTK for tokenisation and lemmatisation
* Working with pre-trained word embeddings
* Preparing text data for deep learning models
* Building a Bidirectional LSTM using TensorFlow/Keras
* Testing model hyperparameters
* Evaluating classification performance
* Interpreting confusion matrices and classification metrics
* Preparing a deep learning notebook for GitHub presentation

---

## Future Improvements

Possible improvements include:

* Comparing the BiLSTM model with simpler models such as Logistic Regression and Naive Bayes
* Adding TF-IDF baseline models
* Adding ROC-AUC analysis
* Improving hyperparameter search
* Trying GRU and Transformer-based models
* Saving and loading the trained model
* Refactoring notebook code into Python scripts
* Adding a clearer final results table

---

## Author

**Amir Lorvand**
