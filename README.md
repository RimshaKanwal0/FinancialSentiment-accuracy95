# FinancialSentiment-accuracy95

# Financial Sentiment Classification with RoBERTa (95% Accuracy)

This repository contains a fine-tuned **RoBERTa model** for financial sentiment analysis.  
The model classifies financial text into **positive** or **negative** sentiment with **95% accuracy**.

---

##  Features
- Preprocessing with Pandas & Label Encoding
- Hugging Face `datasets` for text processing
- Fine-tuning **RoBERTa-base** on financial dataset
- Handles class imbalance with **weighted loss**
- Achieved **95% accuracy** on test set
- Evaluation with **precision, recall, F1-score**

---

## Results
**Binary Classification:** Positive vs Negative
| Metric        | Score |
|---------------|-------|
| Accuracy      | 0.95  |
| Precision     | 0.94  |
| Recall        | 0.95  |
| F1-Score      | 0.95  |


**Requirements**

Python 3.8+
PyTorch
Transformers
Datasets
Scikit-learn
Pandas, Numpy
Install dependencies:

>pip install -r requirements.txt

**License**

---

 Would you like me to also make you a **requirements.txt** file (so you can run it directly in Colab or EC2) for this repo?
