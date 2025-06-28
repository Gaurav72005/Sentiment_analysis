# 🧠 Sentiment Analysis – Customer Reviews (Data Analysis)

This project focuses on **analyzing customer reviews** to understand user sentiment – Positive, Negative, or Neutral – using data visualization techniques.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Sentiment Analysis](#sentiment-analysis)
- [Data Visualization](#data-visualization)
- [Insights & Results](#insights--results)
- [How to Run](#how-to-run)
- [License](#license)

---

## 📝 Overview

This repository contains Python code for:
- Data cleaning on dataset
- Assigning sentiment labels (positive, negative, neutral) from Rating
- Visualizing key patterns using `user_id`, `product_id`, `rating`, and `timestamp`, 'Sentiment'

---

## 📂 Dataset Description

The dataset used includes the following columns:

| Column       | Description                          |
|--------------|--------------------------------------|
| `user_id`    | Unique identifier for the reviewer   |
| `product_id` | Unique product code                  |
| `rating`     | Numerical rating (e.g., 1 to 5 stars)|
| `timestamp`  | Time of the review                   |
| `sentiment`  | Sentiment label (Positive/Negative/Neutral) |

---

## 🛠 Technologies Used

- **Python** for scripting
- **Pandas** for data handling
- **Seaborn & Matplotlib** for data visualization
- **Jupyter Notebook** for analysis

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/sentiment-analysis-data-analysis.git
cd sentiment-analysis-data-analysis
pip install -r requirements.txt
