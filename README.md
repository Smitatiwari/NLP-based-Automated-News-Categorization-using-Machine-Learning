# NLP-based Automated News Categorization using Machine Learning

This project focuses on building an end-to-end NLP system to automatically categorize news articles from FlipItNews’s internal dataset into categories such as **Politics, Technology, Sports, Business**, and **Entertainment** using machine learning techniques.

## Objective

To enhance content discoverability and user experience by organizing large volumes of news articles using automated multi-class classification.

---

##  Key Features

- **Text Preprocessing**
  - Cleaning non-alphabet characters
  - Tokenization
  - Stopword removal
  - Lemmatization

- **Feature Extraction**
  - Bag of Words
  - TF-IDF (Term Frequency-Inverse Document Frequency)

- **Label Encoding**
  - Converts text-based category labels into numerical format

- **Model Training & Evaluation**
  -  **Naive Bayes** (Baseline)
  -  **Decision Tree**
  -  **K-Nearest Neighbors (KNN)**
  -  **Random Forest**

- **Evaluation Metrics**
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix

---

## Results

- **TF-IDF + Random Forest** delivered the highest classification accuracy across all categories.
- Compared models side-by-side to assess strengths and weaknesses in real-world NLP scenarios.
- Built an interpretable system with clear visualizations and reports.

---

##  Visualizations

- Examples of raw vs. processed articles
- Confusion matrices for each model
- Classification reports with key metrics

---

## Technologies Used

| Tool/Library     | Purpose                        |
|------------------|--------------------------------|
| Python           | Core programming language      |
| Scikit-learn     | Machine learning models        |
| NLTK             | NLP preprocessing              |
| Pandas & NumPy   | Data handling                  |
| Matplotlib & Seaborn | Data visualization         |
| Jupyter Notebook | Development environment        |

---

##  Outcome

- Developed a robust NLP pipeline for multi-class text classification.
- Enhanced content tagging and organization capabilities for a real-world news platform.
- Delivered a modular codebase ready for future integration with personalized recommendation systems.

---
## Model Performance Comparison
![image](https://github.com/user-attachments/assets/17f8c5b8-4365-4951-a27e-ea0e027fadf8)

