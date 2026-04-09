# Amazon_sales_dataset.csv
This dataset contains detailed information about products listed on Amazon, including pricing, discounts, ratings, and customer engagement metrics. It is useful for data analysis, machine learning, and business insights.

---

##  File Included

* `Amazon_sales_dataset.csv` – Main dataset containing product-level data.

---

##  Dataset Description

The dataset includes various attributes related to Amazon products such as:

| Column Name               | Description                        |
| ------------------------- | ---------------------------------- |
| `product_id`              | Unique identifier for each product |
| `product_name`            | Name/title of the product          |
| `category`                | Product category                   |
| `discounted_price`        | Price after discount               |
| `actual_price`            | Original price before discount     |
| `discount_percentage`     | Discount offered (%)               |
| `rating`                  | Average customer rating            |
| `rating_count`            | Number of ratings                  |
| `about_product`           | Description of the product         |
| `user_id`                 | Unique user identifier             |
| `review_id`               | Unique review identifier           |
| `review_title`            | Title of the review                |
| `review_content`          | Content of the review              |
| `img_link`                | Link to product image              |
| `product_link`            | Link to product page               |
| `calculated_discount_pct` | Computed discount percentage       |

*(Note: Column names may vary slightly depending on dataset version.)*

---

##  Use Cases

*  Data Analysis & Visualization
*  Machine Learning (Price Prediction, Recommendation Systems)
*  Market Trend Analysis
*  Sentiment Analysis on Reviews
*  Discount Strategy Insights

---

##  How to Use

### 1. Load Dataset in Python

```python
import pandas as pd

df = pd.read_csv("Amazon_sales_dataset.csv")
print(df.head())
```

### 2. Basic Exploration

```python
print(df.info())
print(df.describe())
```

---

##  Example Insights You Can Derive

* Relationship between price and ratings
* Most discounted product categories
* Customer review trends
* Popular products based on rating count

---

##  Notes

* Some fields may contain missing or inconsistent data.
* Text fields (reviews/descriptions) may require preprocessing.
* Prices may be stored as strings and need conversion.

---

##  License

This dataset is for educational and research purposes only.



## ⭐ Support

If you find this dataset useful, consider giving the repository a star!
