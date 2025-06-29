Online Fraud Detection Using Random Forest
Hey!
This is a machine learning project where I trained a Random Forest classifier to detect fraudulent credit card transactions. The model learns from real or synthetic data and helps classify whether a transaction is fraud or not fraud.

What’s Inside?
* ML.py – Main code that:

  - Loads the dataset (creditcard.csv)

  - Splits it into train & test sets

  - Trains a Random Forest model

  - Evaluates the model with a classification report and a confusion matrix
* synthetic_creditcard.py – Creates a synthetic dataset with realistic transaction features if you don’t have real data

* creditcard.csv – Dataset used (either real or generated)

How to Use This Project:
 Clone the repo:
    git clone https://github.com/aishwaryakotagiri/Online-Fraud-Detection.git
    cd Online-Fraud-Detection

(Optional) Generate synthetic data:
If you don't have creditcard.csv, run:
  python synthetic_creditcard.py
Run the ML model:
  python ML.py

You’ll see:
1. Model performance (Precision, Recall, F1-Score)
2. A heatmap of the confusion matrix 📊

Tech Stack:
1. Python 

2. Pandas & NumPy

3. Scikit-learn

4. Matplotlib & Seaborn

5. Jupyter Notebook or Command Line

Note:
Fraud cases are rare in real datasets. The synthetic data generator balances this to give you ~3% fraud cases.

If you’re using real data, make sure it's handled responsibly and ethically.

Sample Output (On Synthetic Data)
         precision    recall  f1-score   support

   Non-Fraud       0.99       1.00      0.99       198
       Fraud       1.00       0.90      0.95        12

    accuracy                           0.99       210
About Me:
I'm Aishwarya Kotagiri, currently exploring AI/ML and solving real-world problems with code. 
email : aishwaryakotagiri1902@gmail.com
linkedin : www.linkedin.com/in/aishwaryakotagiri1902
