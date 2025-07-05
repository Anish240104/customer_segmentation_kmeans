# 🧠 Customer Segmentation using K-Means

This project was developed as part of the **RISE (Real-time Internship & Skill Enhancement)** program by **Tamizhan Skills** under the **Data Science & Analytics** track.

It applies **K-Means clustering**, an unsupervised machine learning algorithm, to segment customers based on their purchasing behavior. The goal is to help businesses target customers more effectively by understanding behavioral patterns.

---

## 🚀 Project Objective

To segment customers into meaningful clusters based on:
- Age
- Annual Income (k$)
- Spending Score (1-100)

These insights can be used by businesses to:
- Personalize marketing campaigns
- Design targeted offers
- Improve customer satisfaction and retention

---

## 📁 Dataset

A synthetic dataset containing the following columns:

| Column Name           | Description                        |
|-----------------------|------------------------------------|
| `CustomerID`          | Unique ID for each customer        |
| `Age`                 | Age of the customer                |
| `Annual Income (k$)`  | Annual income in thousands         |
| `Spending Score (1-100)` | Spending score assigned by the business |

📂 File used: [`customer_data.csv`](customer_data.csv)  
📝 Generated manually using NumPy for the project.

---

## 🧪 Technologies Used

- 🐍 Python (Google Colab)
- 📊 Pandas, NumPy
- 🎯 Scikit-learn (KMeans, StandardScaler)
- 📈 Matplotlib, Seaborn
- 🖼️ Plotly ( 3D/interactive charts)

---

## 🧠 Methodology

1. **Data Exploration & Cleaning**
   - Checked for missing/null values
   - Visualized distribution of age, income, spending

2. **Feature Selection & Scaling**
   - Selected relevant features for clustering
   - Scaled them using `StandardScaler` to normalize values

3. **Elbow Method**
   - Determined the optimal number of clusters using the elbow curve

4. **K-Means Clustering**
   - Applied KMeans to form 4 clusters
   - Assigned cluster labels to each customer

5. **Data Visualization**
   - 2D and 3D plots to visualize customer segments

6. **Cluster Analysis**
   - Grouped clusters to understand customer personas

---


---

## 📝 Key Insights

- **Cluster 0:** High-income frequent spenders — ideal for premium offers.
- **Cluster 1:** Young low-income high spenders — could respond well to discounts.
- **Cluster 2:** Older low-income cautious spenders — best for loyalty rewards.
- **Cluster 3:** Moderate income, moderate spending — mainstream target group.

These segments help businesses **optimize marketing**, **forecast sales**, and **improve user experience**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ About the Author

**Anish Jhajhria**  
📍 B.Tech Student – Rajasthan Technical University  
💼 RISE Internship Trainee – Data Science & Analytics  
💡 Passionate about solving real-world problems using data  
📧 Contact: anish241ajhajhria@gmail.com  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/anish-jhajhria-83b53628a)

---

## ⭐ Acknowledgements

Special thanks to **Tamizhan Skills** for launching the **RISE Internship Program** and providing free, high-quality project-based learning to students from all backgrounds.

---

> 📌 Want to see the full notebook?  
> 👉 Click here: [`customer_segmentation_kmeans.ipynb`](customer_segmentation.ipynb)
