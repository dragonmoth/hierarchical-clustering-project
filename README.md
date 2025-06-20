
# 🧠 Customer Segmentation using Hierarchical Clustering

This project performs customer segmentation using **Agglomerative Hierarchical Clustering** based on two features:  
**Annual Income (k$)** and **Spending Score (1–100)**.

---

## 📌 Problem Statement

Businesses often need to understand customer behavior to offer personalized experiences.  
In this project, we segment customers from a mall dataset to identify patterns like:

- High income but low spending
- Low income but high spending
- High income and high spending
- etc.

---

## 📂 Dataset

The dataset used is `Mall_Customers.csv` which contains:

| Feature            | Description                         |
|--------------------|-------------------------------------|
| `Annual Income`    | Customer income in thousands (k$)   |
| `Spending Score`   | Score assigned by mall based on behavior and spending nature |

---

## 🧰 Technologies Used

- Python 🐍
- Pandas 📊
- Matplotlib 📈
- SciPy (for dendrogram) 🌳
- scikit-learn (Agglomerative Clustering)

---

## 🚀 How it Works

1. Imported and visualized dataset
2. Used **dendrogram** to identify the optimal number of clusters
3. Applied `AgglomerativeClustering` with the selected cluster count
4. Visualized the resulting customer segments

---

## 📊 Output

Here is a sample plot of the resulting clusters:

![image](https://github.com/user-attachments/assets/5131ef44-493a-4d97-9a60-e3db223fd467)


Each color in the plot represents a different customer group based on income and spending score.

---

## 📁 Project Structure

```
├── Mall_Customers.csv
├── hierarchical_clustering.py
└── README.md
```

---

## ✅ Installation (Optional for others)

```bash
pip install pandas matplotlib scipy scikit-learn
```

---

## 📬 Contact

**Sejal Naik**  
Feel free to connect or fork the repo if this helped you!

---

⭐ If you like this project, don't forget to **star** this repo!
