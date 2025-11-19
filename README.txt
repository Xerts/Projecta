This project presents a fully offline, CPU-only sentiment analysis system built using the IMDb Large Movie Review Dataset. The objective is to classify movie reviews as positive or negative using an efficient, interpretable, and resource-friendly machine learning pipeline.

Rather than relying on computationally intensive deep learning frameworks, the system is based on a classical NLP approach combining:

TF-IDF vectorization for feature extraction
Logistic Regression for sentiment classification

This design ensures that the entire workflow remains lightweight, reproducible, and suitable for environments without GPU acceleration. The project was implemented as part of the Deep Learning Course Project, with a focus on clarity, efficiency, and full offline usability.

The IMDb Movie Review Dataset (50,000 labeled reviews) must be downloaded manually from the official source: https://ai.stanford.edu/~amaas/data/sentiment/
Once extracted, the dataset can be loaded directly from local storage for preprocessing, feature engineering, and model training.
