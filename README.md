# BBC News Classifier
This project explores a Non-Negative Matrix Factorizaton (NMF) model that classifies BBC news articles by topic. The model is trained on a dataset of BBC news articles and their corresponding categories. The project uses various Python libraries such as numpy, pandas, matplotlib, seaborn, and sklearn for data manipulation, visualization, and machine learning.

The project is structured as follows:

- `week4.ipynb`: Main notebook where the data is loaded, explored, and processed. The NMF model is also trained and evaluated in this notebook.

- `nmf_limitations.ipynb`: This notebook explores the limitations of Non-negative Matrix Factorization (NMF), a technique used in the main notebook.

- `data/`: This directory contains the datasets used in the project. It includes training and testing data for BBC news articles (BBC News Train.csv, BBC News Test.csv, BBC News Sample Solution.csv) and movie ratings data (w3/movies.csv, w3/test.csv, w3/train.csv, w3/users.csv).

- `submission.csv`: This file contains the model's predictions on a test set.

- `test_profile.html`: This file is an HTML report generated from the data profiling process.

Please note that some files and directoriesare ignored by Git as specified in the `.gitignore` file. The data can be downloaded through [Kaggle](https://www.kaggle.com/c/learn-ai-bbc/overview).
