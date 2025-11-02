# 🛍️ Zara Sales for EDA

This repository hosts the **Zara Sales for EDA** dataset — designed for **Exploratory Data Analysis (EDA)** in the fast-fashion retail domain.

---

## 📘 Overview
- **Rows:** +20,000  
- **Columns:** 17  
- **Focus:** Zara’s fashion products (mostly women’s apparel)  
- **Language:** English 🇺🇸  
- **Purpose:** Analyze retail trends, product attributes, and sales behavior within a fast-fashion context.

> **Origin:** The dataset was created by combining several **public fashion datasets** from GitHub and Kaggle focused on Zara products.  
> Additional engineered columns (e.g., `season`, `url`) were added, and **oversampling** was applied to increase the number of records from the original ~7K to over **20K** and to balance categories for more effective EDA.

---

## 🧩 Variable Dictionary (17 columns)
| Variable | Type | Description |
|-----------|------|-------------|
| **Product ID** | Integer | Unique identifier for each product; includes both original and oversampled entries. |
| **Product Position** | Categorical | In-store placement of the item (e.g., *Aisle*, *End-cap*, *Front of Store*). |
| **Promotion** | Categorical (Yes/No) | Indicates whether the product was included in a promotion or discount. |
| **Product Category** | Categorical | Broad product family or category. |
| **Seasonal** | Categorical (Yes/No) | Flags whether the item belongs to a limited or seasonal collection. |
| **Season** | Categorical | Logical season label (*Spring*, *Summer*, *Autumn*, *Winter*) assigned from product name/description keywords (e.g., *jacket*, *coat*, *puffer* → *Autumn/Winter*). |
| **Sales Volume** | Integer | Approximate number of units sold (or demand proxy); useful for trend and regression analysis. |
| **brand** | Categorical | Brand of the product. |
| **url** | Text | Synthetic yet realistic product link built by combining Zara’s base URL with the product name. |
| **name** | Text | Product title as shown on Zara’s online store (e.g., *Slim Fit Suit Jacket*). |
| **description** | Text | Short product description (design, fit, or features). |
| **price** | Float | Retail price in **USD**, standardized to Zara’s price ranges. |
| **currency** | Text | Currency code of the price (mainly **USD**). |
| **terms** | Categorical | Keyword or subcategory used for grouping (e.g., *jackets*, *shoes*, *sweaters*, *jeans*, *t-shirts*). |
| **section** | Categorical | Store section the item belongs to (e.g., *WOMAN*, *MAN*). |
| **material** | Categorical | Main fabric composition (e.g., *Polyester*, *Cotton*, *Wool Blend*). |
| **origin** | Categorical | Country of manufacture or supply (e.g., *China*, *Bangladesh*, *Cambodia*, *Turkey*). |

---

## 💡 Example Use Cases
- Exploratory data analysis on **pricing** and **promotions**  
- Studying **seasonal trends** and fashion cycles  
- Product **clustering and segmentation** by attributes  
- Building simple **forecasting models** or dashboards  



