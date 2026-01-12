# 🧠 Handwritten Digit '2' Classifier

This project demonstrates a machine learning model that detects whether a handwritten digit is a **2** or not, using the MNIST dataset. It’s perfect for beginners to understand binary classification, model evaluation, and logistic regression.



## 📌 Features


- Trained on the MNIST dataset
- Uses Logistic Regression (not neural networks)
- Focuses on binary classification: "Is it a 2?"
- Evaluates performance with confusion matrix and precision/recall
- Clean and beginner-friendly implementation in Python



## 🛠️ Tech Stack


- Python 🐍  
- NumPy  
- scikit-learn  
- Matplotlib (for visualizing confusion matrix)  



## 🚀 How It Works


1. Load the MNIST dataset using `fetch_openml`
2. Normalize and preprocess the data
3. Convert labels into binary (`2` vs. not `2`)
4. Train a logistic regression model
5. Evaluate using:
   - Cross-validation
   - Confusion matrix
   - Precision, Recall, F1 Score



## 📊 Sample Output


> Example:
> ```
> Accuracy: 97.5%
> Confusion Matrix:
> [[True Negatives, False Positives],
>  [False Negatives, True Positives]]
> ```

(You can add a screenshot of your confusion matrix plot here!)



## 📚 Dataset


MNIST Handwritten Digit Dataset (via `sklearn.datasets.fetch_openml`)



## 🤖 Future Ideas


- Try other classifiers like SVM, Random Forest, or MLP  
- Add a precision-recall or ROC curve  
- Build a web demo with Flask or Streamlit  
- Extend to full 0–9 multiclass classification  



## 🙌 Contributing


Feel free to fork the repo and improve it! Pull requests are welcome.



## 📩 Contact

Created with ❤️ by **Dev Goel**  
Instagram: [@404Dev.NotFound](https://instagram.com/404Dev.NotFound)
