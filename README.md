# 🚀 **Sentiment Classification with NLP and Machine Learning** 🌟  

This project explores **Natural Language Processing (NLP)** techniques and **Machine Learning models** to classify sentiments in text data. The work integrates a combination of feature extraction methods, oversampling techniques, and models to achieve robust and accurate sentiment classification. 🧠📊  

![NLP and Machine Learning Illustration](A_visually_appealing_digital_illustration_represen.png)  

---

## 🎯 **Project Overview**  
- **Type:** Sentiment Classification  
- **Goal:** Classify positive and negative sentiments with high accuracy.  
- **Techniques Used:** NLP, Feature Engineering, Machine Learning, Oversampling.  

---

## 🛠️ **Feature Extraction Techniques**  
The following methods were implemented to represent textual data effectively:  

1. **📚 Bag of Words (BoW):**  
   - Focuses on word frequencies, representing text as vectors of word occurrences without considering grammar or structure.  

   ![Example of Bag of Words](https://miro.medium.com/max/720/1*DkddLx0Ae_jY9sWlmZmjMw.png)  

2. **🔍 TF-IDF (Term Frequency-Inverse Document Frequency):**  
   - Combines Term Frequency (TF) and Inverse Document Frequency (IDF) using logarithmic scaling to emphasize the importance of words relative to both the document and the entire dataset.  

   ![TF-IDF Example](https://res.cloudinary.com/dyd911kmh/image/upload/v1641806462/Marketing%20Blog/TF_IDF_Calculation_uhuwb9.png)  

3. **🤖 Word2Vec:**  
   - Creates dense word vectors by learning semantic relationships and associations from a large corpus of text.  

4. **🧠 GloVe (Global Vectors):**  
   - Captures global word co-occurrences using pre-trained 100-dimensional word vectors to enhance the understanding of word meanings and contexts.  

---

## ⚖️ **Oversampling Technique**  
### **SMOTE (Synthetic Minority Over-sampling Technique):**  
- To address class imbalance, SMOTE was used to generate synthetic samples for the underrepresented class.  
- This ensures a more balanced dataset, improving the model's ability to classify minority sentiments accurately.  

![SMOTE Visualization](https://miro.medium.com/max/1200/1*m5Zvh6iAyIkupTOFEFTApQ.png)  

---

## 💻 **Machine Learning Models**  
Three models were evaluated for sentiment classification:  
1. **📚 Naive Bayes**  
2. **🌲 Random Forest**  
3. **⚡ XGBoost (Extreme Gradient Boosting)**  

---

## 📈 **Key Results and Insights**  

### **🏆 XGBoost Performance**  
- **Baseline Performance:**  
  - Accuracy: **91.16%**  
  - Precision: **0.88**  
  - Recall: **0.78**  
  - F1-Score: **0.82**  

- **TF-IDF + SMOTE with XGBoost**:  
  - Achieved the **highest performance**:  
    - Accuracy: **92.71%**  
    - Precision, Recall, and F1-Score: **0.93**  
    - **ROC-AUC:** **0.98** 🎉  

### **🤔 GloVe + SMOTE with XGBoost**  
- Accuracy: **87.51%**  
- Highlighted limitations in capturing nuanced sentiment for the underrepresented class.  

---

## 📊 **Evaluation Metrics**  
Standard classification metrics were used:  
✅ **Accuracy**  
✅ **Precision**  
✅ **Recall**  
✅ **F1-Score**  
✅ **ROC-AUC Curve**  

![ROC-AUC Example](https://upload.wikimedia.org/wikipedia/commons/6/6b/Roc_curve.png)  

---

## 🚀 **Future Work**  

1. Explore **deep learning models** like **BERT** for enhanced text representation and sentiment analysis.  
2. Investigate techniques such as **SHAP** and **LIME** for better model interpretability.  
3. Experiment with additional NLP techniques and embeddings to refine performance further.  

---

## 📂 **Getting Started**  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/RanaPrince/sentiment-classification.git  
   pip install -r requirements.txt  




## 📂 **Getting Started**

Run the model scripts and experiment with feature extraction techniques.  

---

## 🤝 **Contact Me**

Feel free to reach out for questions, collaborations, or feedback!  

- **GitHub:** [RanaPrince](https://github.com/RanaPrince)  
- **LinkedIn:** [Prince Rana](https://www.linkedin.com/in/princeranaai/)  
- **Email:** [ranaprinceai@gmail.com](mailto:ranaprinceai@gmail.com)  
