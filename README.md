# Film Junky Union: Movie Review Sentiment Classifier

## About

An NLP sentiment classifier for movie reviews. Uses spaCy lemmatization and TF-IDF to achieve an F1 score of 0.95 and ROC AUC of 0.99.

## 🚀 Technical Highlights

* **Advanced NLP Pipeline**: Implemented a comprehensive text-cleaning workflow using **spaCy** for lemmatization and tokenization, ensuring semantic consistency before vectorization.
* **TF-IDF Vectorization**: Transformed unstructured text into high-dimensional numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)** to capture word importance relative to the entire corpus.
* **Comparative Model Evaluation**: Benchmarked multiple architectures, including **Logistic Regression**, **Random Forest**, and **LightGBM**, optimizing for the best trade-off between inference speed and classification accuracy.
* **Exceptional Performance Metrics**: Achieved a top-performing **F1 score of 0.95** and an **ROC AUC of 0.99**, significantly exceeding the project's target requirements.
* **Robust Validation**: Utilized **Precision-Recall** and **ROC curves** to validate model performance across different thresholds, ensuring reliable sentiment detection for diverse review styles.

### 📂 Repository Structure
* **`data/`**: Directory for the IMDb movie review dataset.
* **`notebooks/`**: Main analytical file: `movie_review_sentiment_analysis.ipynb`.
* **`requirements.txt`**: Project dependencies including `spacy`, `nltk`, and `lightgbm`.
