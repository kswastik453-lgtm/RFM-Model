# 🛒 RFM Customer Segmentation Analysis

> Segment customers based on their purchasing behavior using the **RFM (Recency, Frequency, Monetary)** model — built
>  with Python on the Superstore dataset.

---

## 📌 What is RFM?

RFM is a proven marketing framework used to identify and rank customers based on three key dimensions:


| Dimension | Description |
|-----------|-------------|
| **R — Recency** | How recently did the customer make a purchase? |
| **F — Frequency** | How often do they purchase? |
| **M — Monetary** | How much do they spend in total? |

By scoring customers across these three axes, businesses can identify their most valuable segments — from **loyal champions** 
to **at-risk churners** — and tailor marketing strategies accordingly.

---

## 📂 Dataset

- **Source:** Superstore Sales Dataset (`Superstore.xls`)
- **Domain:** Retail / E-commerce
- **Content:** Transaction-level data including customer IDs, order dates, and sales amounts

---

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4c8cbf)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kswastik453-lgtm/RFM-Model.git
cd RFM-Model
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn xlrd
```

### 3. Add the Dataset

Place the `Superstore.xls` file in the root directory of the project.

### 4. Run the Notebook

```bash
jupyter notebook RFM_model.ipynb
```

---

## 📊 Project Workflow

```
Load Data → Clean & Preprocess → Calculate RFM Scores → Segment Customers → Visualize Insights
```

1. **Data Loading** — Read the Superstore Excel file using Pandas
2. **RFM Calculation** — Compute Recency, Frequency, and Monetary values per customer
3. **Scoring** — Assign scores (1–5) to each RFM dimension using quantile-based ranking
4. **Segmentation** — Classify customers into meaningful segments (Champions, Loyal, At Risk, etc.)
5. **Visualization** — Explore segment distributions with Matplotlib & Seaborn

---

## 🧠 Customer Segments



| Segment | RFM Score | Description |
|---------|-----------|-------------|
| 🏆 Champions | 555 | Bought recently, buy often, spend the most |
| 💛 Loyal Customers | 4-5 | Buy regularly with good spend |
| 🌱 Potential Loyalists | 3-4 | Recent buyers with moderate frequency |
| ⚠️ At Risk | 2-3 | Once valuable, haven't bought in a while |
| 💤 Lost | 1 | Low recency, frequency, and monetary value |

---

## 📈 RFM Score Matrix

> Each customer is scored 1–5 on all three dimensions. Higher scores indicate better customers. The bubble size above represents
> monetary value — bigger bubble = higher spender.

---

## 📁 Repository Structure

```
RFM-Model/
│
├── RFM_model.ipynb        # Main analysis notebook
├── Superstore.xls         # Dataset (add manually)
├── README.md              # Project documentation
└── images/
    ├── workflow.png        # Pipeline diagram
    ├── segments.png        # Customer segment chart
    └── rfm_heatmap.png    # RFM score matrix
```

---

## 💡 Key Insights

- Customers in the **Champions** segment contribute the highest revenue and should be rewarded
- **At Risk** customers need re-engagement campaigns before they churn completely
- **Potential Loyalists** can be nudged into the Champions tier with targeted offers
- RFM scoring allows businesses to **prioritize marketing spend** on the right customers

---

## 🔮 Future Improvements

- [ ] Add K-Means clustering for data-driven segmentation
- [ ] Build an interactive dashboard using Plotly or Streamlit
- [ ] Automate the pipeline with scheduled data updates
- [ ] Add email campaign recommendations per segment

---

## 👤 About the Author

**Swastik K** — Data Analyst & Python Enthusiast

Passionate about turning raw data into actionable business insights.
Currently exploring machine learning and customer analytics.

[![GitHub](https://img.shields.io/badge/GitHub-kswastik453--lgtm-181717?logo=github&logoColor=white)](https://github.com/kswastik453-lgtm)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)

📬 Open to collaborations, internships & data roles!

---

## ⭐ Show Some Love

If you found this project useful, consider giving it a ⭐ — it helps others discover it too!

---

<p align="center">Made with ❤️ and Python</p>
