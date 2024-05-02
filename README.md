**Repository Name:** FakeNewsDetector

**Description:**
This repository contains an IPython Notebook file (FakeNewsDetection.ipynb) aimed at detecting fake news using three different models: Naive Bayes, LSTM, and Bi-LSTM. The notebook utilizes two datasets, namely `True.csv` and `Fake.csv`, each containing news articles labeled as either true or fake. These datasets are imported separately and combined into a unified dataset named `dataset`. 

Preprocessing steps include removing author names and merging the title and text columns for each article. Text data preprocessing techniques such as tokenization, stemming, or lemmatization might also be applied, depending on the implementation. 

The notebook then proceeds to train and evaluate the three models on the combined dataset. Accuracy metrics are computed for each model, and the results are visualized using three separate graphs, providing insights into the performance of each model in detecting fake news.

**Contents:**
- FakeNews.ipynb: Jupyter Notebook containing code for fake news detection using Naive Bayes, LSTM, and Bi-LSTM models.
- True.csv: Dataset containing true news articles.
- Fake.csv: Dataset containing fake news articles.

**Usage:**
1. Clone the repository.
2. Open and run the FakeNewsDetection.ipynb notebook in a Jupyter environment.
3. Ensure the necessary dependencies are installed to execute the code successfully.


