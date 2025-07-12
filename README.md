# 🛍️ E-Commerce Customer Segmentation and Analysis

This project focuses on analyzing and segmenting e-commerce customer data using machine learning and data visualization techniques. The dataset used is a sample customer database from Datablist.

---

## Project Objectives

- Clean and preprocess customer data.
- Engineer useful features for deeper analysis.
- Segment customers using clustering algorithms.
- Visualize key insights to support business decisions.
- Enable BI integration through Power BI or similar tools.

---

## 📁 Dataset

The dataset contains structured customer information, including:

- Full Name
- Company
- Email Address
- Phone Number
- Job Title
- Industry
- Country, City
- Website
- Subscription Date

📎 **Cleaned Dataset**: [Download Link](https://drive.google.com/file/d/1vH0RzPKSRjjmX6gns8qiLLXVvC74NP_x/view?usp=sharing)

---

##  Preprocessing Steps

- Converted date columns to datetime format.
- Removed duplicates and constant columns.
- Handled missing values.
- Encoded categorical variables.
- Treated outliers using visual inspection.
- Scaled numerical features using `StandardScaler`.

---

## ⚙️ Feature Engineering

- Extracted `Subscription_Year` and `Subscription_Month`.
- Computed `Name_Length`, `Company_Length`.
- Derived `Email_Domain` and `Is_Personal_Email`.

---

## Clustering Model

**Algorithm**: K-Means  
**Evaluation**:
- Elbow Method (to find optimal clusters)
- Silhouette Score (~0.50)

**Result**: Segmented into 3 clusters:
1. Low-engagement or new users
2. Business-oriented loyal users
3. Personal email users with active profiles

---

## 📊 Visualizations

- Count plots for clusters
- Pie charts for domain/job distribution
- Histograms of subscription behavior
- Heatmaps for feature correlation

All plots created using:
- `matplotlib`
- `seaborn`
- `pandas`

---

## Business Insights

- Personalized marketing campaigns can target specific clusters.
- Behavioral features like email type and job title enable customer profiling.
- Subscription patterns reveal growth opportunities.

---

## 📎 Files Included

- `Project Final process.ipynb`: Full project notebook
- `cleaned_customers.csv`: Preprocessed dataset
- `README.md`: Project overview
- Optional Power BI file (if available)

---

## 📌 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ecommerce-customer-segmentation.git
    ```
2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the notebook:
    ```bash
    jupyter notebook Project\ Final\ process.ipynb
    ```

---

## 📚 Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

---

## 📈 Future Enhancements

- Add classification models for churn prediction.
- Integrate dashboard in Power BI or Tableau.
- Automate updates using scheduled scripts.

---

## 🧑‍💻 Author

**Anu Akhil**  
For queries or collaborations, feel free to reach out via GitHub or email.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
