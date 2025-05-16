
# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Overview

This project aims to implement **Customer Segmentation** using the **K-Means Clustering algorithm** on the **Mall Customers Dataset**. Customer segmentation is a crucial marketing strategy that helps identify and group similar customers to personalize marketing, improve customer satisfaction, and increase business revenue.

---

## 📁 Project Structure

```
├── Customer Segmentation Using Machine Learning.ipynb   # Main Jupyter Notebook
├── Mall_Customers.csv                                   # Dataset used
├── Project Report.docx                                   # Detailed project report
├── Presentation.pptx                                     # Project presentation slides
├── README.md                                             # Project documentation
```

---

## 📊 Dataset

The dataset used in this project is sourced from **Kaggle**. It contains the following features:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

📂 [Mall Customers Dataset on Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)

---

## 🧠 Methodology

1. **Data Preprocessing**:
   - Handling null values (if any)
   - Encoding categorical variables
   - Scaling/normalizing features

2. **Elbow Method**:
   - To determine the optimal number of clusters (k)

3. **Model Training**:
   - Applying K-Means clustering algorithm

4. **Visualization**:
   - Visualizing customer segments using scatter plots

---

## 📈 Results

Based on the Elbow method, the optimal number of clusters was selected. The customers were grouped into distinct segments such as:

- Low income, high spenders
- High income, low spenders
- Balanced income and spenders
- etc.

These clusters help businesses understand their customer base and tailor strategies accordingly.

---

## 🎯 Objectives

- Identify different customer segments.
- Understand behavior and preferences within each segment.
- Optimize marketing strategies and business offerings.
- Improve customer satisfaction and loyalty.

---

## 🔮 Future Work

- Experiment with different distance metrics: Manhattan, Cosine, etc.
- Try advanced clustering methods like DBSCAN or Hierarchical Clustering.
- Use more features like purchase frequency, product category, etc.
- Integrate with CRM or recommendation systems.

---



## 📽️ Presentation

You can view the project presentation in the `Presentation.pptx` file included in the repo.

---

## 💡 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook "Customer Segmentation Using Machine Learning.ipynb"
   ```

---

## 📝 License

This project is for educational purposes only.
