# Zara-sales-dataset-
Dataset de ventas de Zara para análisis exploratorio (EDA).


# 🛍️ Zara Sales for EDA

## 📘 Overview  
This repository contains the dataset **Zara Sales for EDA**, designed for **Exploratory Data Analysis (EDA)** focused on fashion retail.  
The dataset aggregates multiple public sources (including GitHub and Kaggle datasets) related to **Zara’s fashion products**, with an emphasis on **women’s apparel**.  
It allows data enthusiasts and analysts to explore **sales behavior, product attributes, and retail trends** in a fast-fashion context.

---

## 📊 Dataset Overview
| Feature | Description |
|----------|--------------|
| **Rows** | +20,000 |
| **Columns** | 17 |
| **Focus** | Zara’s fashion products (mostly women’s apparel) |
| **Language** | English 🇺🇸 |
| **Purpose** | Analyze retail trends, product attributes, and sales behavior in a fast-fashion context |

---

## 🧩 About the Data
This dataset was created by combining several public **fashion-related datasets** from GitHub and Kaggle.  
It includes the following key information for each product:

- **Product name**  
- **Description**  
- **Price**  
- **Category**  
- **Sales volume**  

Additional columns were generated to enhance analysis:
- **`season`** — assigned automatically based on product names (e.g., *“jacket” → Winter/Autumn*).  
- **`url`** — constructed using Zara’s base link and the product title.

The **original dataset** had around **7K rows**, and oversampling techniques were applied to expand it to **20K+ rows** and improve category balance for better exploratory analysis.

---

## 🧮 Columns Overview (examples)
| Column | Description |
|---------|-------------|
| `product_id` | Unique identifier of the product |
| `product_name` | Product title |
| `category` | Type of item (e.g., dresses, jackets, pants) |
| `price` | Product price in EUR |
| `sales_volume` | Estimated or recorded sales volume |
| `season` | Season assigned based on product |
| `url` | Generated Zara product page link |

---

## 💡 Example Use Cases
- Exploratory analysis of **pricing strategies**  
- Identifying **seasonal sales trends**  
- Clustering products by **attributes and categories**  
- Building dashboards or ML models for **sales prediction**  

---

## 📂 Repository Structure
