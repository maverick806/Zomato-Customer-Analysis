# Zomato-Customer-Analysis
This project presents an in-depth analysis of Zomato dataset, focusing on restaurant trends, user ratings, cost analysis, and location-based insights. Includes visualizations and key findings to support data-driven decision making.
# 🍽️ Zomato Restaurant Clustering — Unsupervised ML

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-Cloud-0089D6?logo=microsoft-azure&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> Unsupervised Machine Learning project to cluster Zomato restaurants across Indian cities, perform sentiment analysis on customer reviews, and generate actionable business insights for both customers and the company.

---

## 📌 Project Overview

India's restaurant industry is vast and diverse. Zomato, founded in 2008 by Deepinder Goyal and Pankaj Chaddah, is one of the leading food aggregator and delivery platforms in India. This project analyzes Zomato's restaurant data to:

- Segment restaurants into meaningful clusters using unsupervised ML
- Perform **sentiment analysis** on customer reviews
- Visualize patterns around cuisine, cost, ratings, and locality
- Help customers discover the **best restaurant in their area**
- Help Zomato identify **areas for business improvement**

---

## 🎯 Objectives

- Analyze sentiments of customer reviews to extract useful conclusions
- Cluster Zomato restaurants into distinct segments/groups
- Visualize data to make insights accessible and actionable
- Identify critic reviewers using reviewer metadata
- Perform cost vs. benefit analysis across cuisine types

---

## 🗂️ Dataset Description

The project uses two datasets:

### 🏪 Restaurant Data

| Field | Description |
|-------|-------------|
| Name | Name of the restaurant |
| Links | URL link of the restaurant on Zomato |
| Cost | Estimated per-person dining cost |
| Collection | Zomato category tagging |
| Cuisines | Cuisines served by the restaurant |

### 📝 Review Data

| Field | Description |
|-------|-------------|
| Reviewer | Name of the reviewer |
| Review | Review text |
| Rating | Rating given by reviewer |
| MetaData | Reviewer's no. of reviews & followers |
| Time | Date and time of the review |
| Pictures | No. of pictures posted with the review |

---

## 🏗️ Project Architecture

```
EDA → Data Clean-up → Feature Engineering → Pre-Processing → Model Implementation → Model Explainability
```

### Step-by-step breakdown:

1. **EDA** — Distribution of cost across cuisines, visualizing relationships, identifying popular restaurants, checking cost vs. rating correlation
2. **Clean-up** — Handling missing values and removing outliers
3. **Feature Engineering** — Feature encoding and creating new features if required
4. **Pre-Processing** — Feature scaling using StandardScaler / MinMaxScaler
5. **Model Implementation** — Using **K-Means Clustering**, finding the optimal number of clusters using the **Elbow Method**, visualizing clusters
6. **Model Explainability** — Interpreting cluster characteristics and devising strategies for each segment

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and aggregation |
| **NumPy** | Computationally efficient numerical operations |
| **Matplotlib & Seaborn** | Data visualization and plotting |
| **Scikit-learn** | Model building and preprocessing |
| **Microsoft Azure** | Cloud platform (ML & GenAI) |

---

## 📁 Project Structure

```
zomato-restaurant-clustering-ml/
│
├── data/
│   ├── restaurant_data.csv
│   └── review_data.csv
│
├── notebooks/
│   └── Zomato_Analysis.ipynb       # Main Colab notebook
│
├── visuals/
│   └── *.png                       # EDA and cluster plots
│
├── README.md
└── requirements.txt
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/zomato-restaurant-clustering-ml.git
cd zomato-restaurant-clustering-ml
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
Open `notebooks/Zomato_Analysis.ipynb` in Jupyter or Google Colab and run all cells.

---

## 📊 Key Insights

- **K-Means Clustering** used to segment restaurants; optimal K determined via the Elbow Method
- Sentiment analysis on reviews reveals overall customer satisfaction trends
- Cost is not always correlated with rating — value-for-money clusters exist
- Reviewer metadata helps identify influential critics in the food industry

---

## 📈 Evaluation Metrics

The project was evaluated on the following rubrics:

- EDA & Visualization
- Data Cleaning & Feature Engineering
- Hypothesis Formation from Data
- Model Selection & Training
- Prediction & Evaluation Metrics
- Code Quality (modularity, comments, formatting)
- Summary & Technical Documentation

---

## 📜 License

This project is for educational purposes under an academic course on Machine Learning & GenAI with Microsoft Azure.

---

## 👤 Author

Aditya Khare
- GitHub: [@maverick806](https://github.com/maverick806)
- LinkedIn: [your-linkedin](https://linkedin.com/in/your-linkedin)

---

> ⭐ If you found this project helpful, please give it a star!
