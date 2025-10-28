# Task 6 – K-Nearest Neighbors (KNN)

This project is my **Task-6 work** for KNN algorithm using Python.  
It check the dataset, normalize it, test many K values, and find which K give best accuracy.  
It also print confusion matrix, accuracy report, and show decision boundary graph for better understanding.

---

## What This Code Do

- Load **Iris dataset** from sklearn (already available)  
- Normalize feature values using StandardScaler  
- Split dataset into **train** and **test** part  
- Try multiple **K values (1 to 25)**  
- Find best K automatically based on accuracy  
- Plot **Accuracy vs K** graph  
- Train final model using that best K  
- Print accuracy score, confusion matrix, and classification report  
- Show 2D **Decision Boundary** for 2 features (sepal length & width)  
- Display sample predictions for checking model output  

---

## File Info

| File Name | Use |
|------------|-----|
| `task6_knn_myStyle.py` | Main Python code file |
| `README.md` | Project explanation and run guide |

---

## Required Libraries

Make sure you have these before running code:  
```bash
pip install scikit-learn pandas matplotlib seaborn numpy