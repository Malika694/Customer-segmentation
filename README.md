##     Customer Segementation

**Customer Segmentation** is about applying **clustering (KMeans, DBSCAN, etc.)** on the **Mall Customer dataset** to segment customers based on **Annual Income** and **Spending Score**.

It includes:

* Importing libraries (Pandas, Seaborn, Matplotlib, Scikit-learn)
* Loading `mall customer.csv` dataset
* Exploratory Data Analysis & scatterplots
* Feature scaling
* Applying **KMeans** clustering
* Trying **DBSCAN**
* Visualizing clusters

Now, I’ll create a professional `README.md` file for this notebook.


It seems like I can’t do more advanced data analysis right now. Please try again later.

But no worries—I already drafted the full **GitHub `README.md` content** for your `Task_2_Customer_Segmentation.ipynb`. Here it is, ready for you to copy into your repository:

---

# 🛍️ Customer Segmentation using Clustering

This project applies **clustering techniques** to segment mall customers based on their **Annual Income** and **Spending Score**.
It is part of a Machine Learning internship task.

---

## 📌 Project Overview

* **Goal:** Segment customers into meaningful groups for targeted marketing strategies.
* **Dataset:** [Mall Customer Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)
* **Algorithms Used:**

  * KMeans Clustering
  * DBSCAN Clustering
* **Features Used:** Annual Income (k\$), Spending Score (1–100)

---

## 📂 Dataset Information

The dataset contains:

* **CustomerID** – Unique ID for each customer
* **Gender** – Male/Female
* **Age** – Age of the customer
* **Annual Income (k\$)** – Annual income in thousands
* **Spending Score (1–100)** – Spending behavior score assigned by the mall

---

## ⚙️ Installation & Requirements

To run this notebook, install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Customer-Segmentation.git
   ```
2. Navigate to the project folder:

   ```bash
   cd Customer-Segmentation
   ```
3. Open Jupyter Notebook and run:

   ```bash
   jupyter notebook Task_2_Customer_Segmentation.ipynb
   ```

---

## 📊 Exploratory Data Analysis (EDA)

* Basic dataset info & statistics
* Distribution of customer features
* Scatterplot: Annual Income vs Spending Score

---

## 🤖 Model Building

### 1️⃣ KMeans Clustering

* Selected **Annual Income** and **Spending Score** features
* Applied **Elbow Method** to determine optimal clusters
* Visualized customer clusters

### 2️⃣ DBSCAN Clustering

* Applied density-based clustering
* Compared results with KMeans

---

## 📈 Results

* Customers were successfully segmented into distinct groups.
* Visualization highlights clusters in **Annual Income vs Spending Score** space.
* DBSCAN offered an alternative perspective on dense regions of customers.

---

## 📌 Tools & Libraries

* **Python 3**
* **Pandas, Numpy**
* **Matplotlib, Seaborn**
* **Scikit-learn**



