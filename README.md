
### 🛍️ Myntra E-commerce Product Dataset

This repository contains a rich dataset of products from Myntra, one of India's leading e-commerce platforms. The data is organized into four distinct CSV files, each representing a key stage in the data analysis pipeline, from raw collection to final analysis.

---

### 📂 File Descriptions

* **`Myntra_final Data.xlsx - Raw data.csv`**
    * **Description**: This is the pristine, raw dataset, fresh from the source! It includes essential product details like name, brand, ratings, and pricing, untouched by any cleaning or processing.
    * **Columns**: `product_name`, `brand_name`, `rating`, `rating_count`, `marked_price`, `discounted_price`, and `product_link`.

* **`Myntra_final Data.xlsx - somewhat clean.csv`**
    * **Description**: A step up from the raw data, this file is a "somewhat clean" version. We've added new, insightful columns like `product_category`, `unique id`, `discount%`, and `revenue%` to get it ready for some basic analysis.
    * **Columns**: `product_name`, `brand_name`, `rating`, `rating_count`, `marked_price`, `discounted_price`, `product_category`, `unique id`, `discount%`, and `revenue%`.

* **`Myntra_final Data.xlsx - analysis.csv`**
    * **Description**: Think of this as the "blueprint" for a full-scale data analysis! Although the file is currently empty, its headers and comments lay out all the key questions we aim to answer. From finding the most expensive products to identifying top-selling categories, this is where the real insights are born.
    * **Analysis Questions**:
        * 📊 Average prices (marked and discounted)
        * 📈 Most and least expensive products
        * ⭐ Average rating and total ratings
        * 🏷️ Most popular brands and categories
        * 📉 Products with the highest discounts

* **`Myntra_final Data.xlsx - Pivots.csv`**
    * **Description**: This file is a workspace for summarizing data with pivot tables. It's currently empty, but it's set up to store aggregated metrics like the sum and average of ratings and prices, organized by brand and product category. It's the perfect tool for creating quick business intelligence dashboards!
    * **Key Aggregations**:
        * Total and average ratings
        * Sum of discounted and marked prices
        * Groupings by brand and product category
     
<img width="935" height="349" alt="myntra dashboard pic" src="https://github.com/user-attachments/assets/d3d5a4b6-d4bf-4366-a566-4303f0ab2bca" />
