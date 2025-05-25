# Amazon Product Review Sentiment Analysis & Modelling

## 📝 Business Problem

Kozmos, a company specializing in home textiles and daily wear, sells its products on Amazon. To boost sales and improve product features, Kozmos aims to analyze customer reviews, identify complaints, and enhance its offerings accordingly.

## 🎯 Project Goal

- Perform sentiment analysis on Amazon product reviews to label each comment as positive, negative, or neutral.
- Build a classification model using the labeled data to automatically predict the sentiment of new reviews.

## 📂 Dataset Description

The dataset consists of customer reviews for Kozmos products sold on Amazon.

### Data Fields

- **Star:** Number of stars given to the product (rating).
- **Helpful:** Number of people who found the comment helpful.
- **Title:** Short title or summary of the comment.
- **Review:** Full text of the customer’s comment on the product.

## 🛠️ Project Steps

1. **Data Loading & Exploration:**  
   - Import the dataset and perform initial exploratory data analysis.

2. **Text Preprocessing:**  
   - Clean and preprocess the review texts (remove punctuation, stopwords, etc.).
   - Tokenize and normalize the text data.

3. **Sentiment Labeling:**  
   - Tag each review with a sentiment label (positive, negative, neutral) using sentiment analysis techniques.

4. **Feature Engineering:**  
   - Create features from the text and metadata (e.g., star rating, helpful count).

5. **Model Building:**  
   - Train a classification model (e.g., Logistic Regression, SVM, or deep learning models) to predict sentiment labels.

6. **Model Evaluation:**  
   - Evaluate the model’s performance using appropriate metrics (accuracy, precision, recall, F1-score).

7. **Insights & Recommendations:**  
   - Analyze the results to identify common complaints and areas for product improvement.

## 🛠️ Libraries Used

- **pandas:** Data manipulation and analysis.
- **numpy:** Numerical operations.
- **scikit-learn:** Machine learning and model evaluation.
- **nltk / spaCy / TextBlob:** Natural language processing and sentiment analysis.
- **matplotlib / seaborn:** Data visualization.

## 🚀 Getting Started

1. **Clone the Repository**
    ```bash
    git clone https://github.com/elifkeskin/Amazon.git
    cd Amazon
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Project**
    - Open the main script or notebook and follow the steps for data preprocessing, sentiment analysis, and model training.

## 🤝 Contributing

Contributions are welcome!  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit your changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature-branch`)  
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

---

**For questions or suggestions, feel free to open an issue or contact the maintainer.**
