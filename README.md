# 🛒 eCommerce Store Analytics Dashboard

This project presents an interactive **eCommerce Store Dashboard** built using data visualization techniques to derive insights from sales data. The dashboard and dataset explore patterns in gender-based shopping, product categories, order status, channel performance, and customer demographics across states and cities in India.

---

## 📊 Dashboard Overview

The dashboard provides the following insights:

* **Amount and Orders by Month**: Trends in monthly sales and order volume.
* **Gender vs Shopping Behavior**: Comparison of shopping preferences across gender.
* **Order Status**: Breakdown of delivered, returned, cancelled, and refunded orders.
* **Top Categories**: Most purchased product categories such as kurtas, western wear, sets, etc.
* **Top States & Cities**: Regions contributing the highest order volumes.
* **Age Group vs Gender**: Shopping behavior segmented by age groups and gender.
* **Sales Channel Analysis**: Performance of platforms like Amazon, Myntra, Flipkart, Meesho, etc.
* **B2B vs B2C**: Classification of transactions.
* **Monthly Order Distribution**: Seasonal trends in customer purchases.

---

## 📁 Dataset

The dataset consists of order-level data capturing customer and transaction details.

### Key Columns:

| Column Name       | Description                              |
| ----------------- | ---------------------------------------- |
| `Order ID`        | Unique identifier for each order         |
| `Cust ID`         | Customer identifier                      |
| `Gender`          | Gender of the customer                   |
| `Age`             | Age of the customer                      |
| `Date`            | Date of transaction                      |
| `Status`          | Order status (Delivered, Returned, etc.) |
| `Channel`         | Sales platform (e.g., Amazon, Myntra)    |
| `SKU`             | Product identifier                       |
| `Category`        | Product category                         |
| `Size`            | Size of the item ordered                 |
| `Qty`             | Quantity purchased                       |
| `Amount`          | Order amount in INR                      |
| `Ship-City/State` | Shipping address details                 |
| `B2B`             | Business transaction flag                |

Sample entries:

```csv
Order ID              Gender  Age  Channel   Category     Amount  City      State
171-1029312-3038738   Women   44   Myntra    kurta        376     MOHALI    PUNJAB
405-2183842-2225946   Women   29   Ajio      Set         1449     GURUGRAM  HARYANA
404-7490807-6300351   Women   20   Amazon    Set          729     THANJAVUR TAMIL NADU
```

---

## 🛠️ Tech Stack

* **Power BI / Tableau**: For dashboard design and visualization
* **Python / Pandas (optional)**: For preprocessing and data cleaning
* **CSV**: Format of raw data input

---

## 🔍 Insights Uncovered

* Women account for **64%** of total purchases.
* **Kurta** is the most popular product category.
* Most orders come from states like **Uttar Pradesh** and cities like **Zirakpur**.
* The highest volume of orders is through **Amazon**.
* The business is primarily **B2C (99.4%)**, with minimal B2B transactions.

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ecommerce-dashboard.git
   ```
2. Open the `.pbix` (Power BI) or `.twbx` (Tableau) file in the respective software.
3. Load the dataset from `data/orders.csv` or the embedded data.
4. Explore the interactive dashboard.

---

## 📌 Future Enhancements

* Integrate real-time data from APIs.
* Add customer segmentation and RFM analysis.
* Improve mobile responsiveness for dashboards.

---
Contact:
Name:Aarya Meshram
Email:aaryameshram18@gmail.com
