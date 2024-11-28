# Sentiment Classification with NLP and Machine Learning

This project explores **Natural Language Processing (NLP)** techniques and **Machine Learning models** to classify sentiments in text data. The work integrates a combination of feature extraction methods, oversampling techniques, and models to achieve robust and accurate sentiment classification.

---

## **Feature Extraction Techniques**
The following vectorization methods were implemented to represent textual data:

1. **Bag of Words (BoW)**  
   - Focuses on word frequencies, representing text as vectors of word occurrences without considering grammar or structure.

2. **TF-IDF (Term Frequency-Inverse Document Frequency)**  
   - Combines Term Frequency (TF) and Inverse Document Frequency (IDF) using logarithmic scaling to emphasize the importance of words relative to both the document and the entire dataset.

3. **Word2Vec**  
   - Creates dense word vectors by learning semantic relationships and associations from a large corpus of text.

4. **GloVe (Global Vectors)**  
   - Captures global word co-occurrences using pre-trained 100-dimensional word vectors to enhance the understanding of word meanings and contexts.

---

## **Oversampling Technique**
### **SMOTE (Synthetic Minority Over-sampling Technique)**  
To address class imbalance, SMOTE was used to generate synthetic samples for the underrepresented class, ensuring a more balanced dataset and better model performance.

---

## **Machine Learning Models**
Three models were evaluated:
1. **Naive Bayes**
2. **Random Forest**
3. **XGBoost (Extreme Gradient Boosting)**

---

## **Key Results and Insights**

### **XGBoost Performance**
- **Baseline:**  
  XGBoost achieved an accuracy of **91.16%**, with:
  - Precision: **0.88**
  - Recall: **0.78**
  - F1-Score: **0.82**

### **GloVe + SMOTE with XGBoost**
- Accuracy: **87.51%**
- Precision, Recall, and F1-Score: **0.88**
- While decent, this setup showed limitations in capturing the nuances of the data, particularly in the underrepresented class.

### **TF-IDF + SMOTE with XGBoost**
- Achieved the **highest performance**:
  - Accuracy: **92.71%**
  - Precision, Recall, and F1-Score: **0.93**
  - This result demonstrates the effectiveness of TF-IDF in feature representation when combined with SMOTE and XGBoost.

---

## **Evaluation Metrics**
Evaluation was based on standard classification metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Curve**  
  - The ROC curve had an **AUC of 0.98**, showcasing excellent capability in distinguishing between positive and negative sentiment classes, minimizing false positives, and maintaining a high true positive rate.

---

## **Future Work**
- Explore **deep learning models** like **BERT** for enhanced text representation and sentiment analysis.
- Investigate techniques like **SHAP** and **LIME** for improving model interpretability.
- Experiment with additional NLP techniques and embeddings to capture more nuanced semantic information.

---

## **Getting Started**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RanaPrince/sentiment-classification.git

   pip install -r requirements.txt




