# Customer Segmentation & Sales Analysis

## 📌 Project Overview
This project aims to analyze customer purchasing behavior and segment customers using two approaches: **RFM Analysis** and **K-Means Clustering**. Additionally, we performed a **sales data analysis** to gain deeper insights into purchasing patterns.

## 🚀 Dataset
The dataset consists of transactional data, including:
- `Customer ID` (Unique identifier for customers)
- `Invoice Date` (Purchase date)
- `Invoice No` (Transaction ID)
- `Quantity` (Number of items purchased)
- `Price` (Unit price of the item)

## 🛠️ Data Preprocessing
Before applying clustering algorithms, the following preprocessing steps were performed:
- **Handling Missing Values:** Missing `Customer ID` values were replaced with "Unknown".
- **Feature Engineering:** Calculated `Recency`, `Frequency`, and `Monetary` (RFM) values.
- **Data Scaling:** Standardized RFM values using `StandardScaler`.

## 🔍 Customer Segmentation Approaches
### **1. RFM Analysis**
RFM (Recency, Frequency, Monetary) analysis was used to group customers based on their purchasing behavior:
- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer purchases.
- **Monetary:** The total amount a customer has spent.

### **2. K-Means Clustering**
We applied the **K-Means Clustering** algorithm to segment customers into three main groups:

| **Segment** | **Recency (days)** | **Frequency** | **Monetary (Total Spend)** | **Customer Behavior** |
|------------|------------------|-------------|---------------------|-----------------|
| **0** | 39.45 | 6.12 | 2,367 TL | Average Customers |
| **1** | 0.00 | 3,710.00 | 1,447,682 TL | VIP Customers |
| **2** | 247.36 | 1.88 | 477 TL | Inactive Customers |

## 📊 Sales Data Analysis
Apart from customer segmentation, we also analyzed overall sales trends:
- **Top-selling products** identified to focus on high-performing items.
- **Revenue trends over time** examined to understand seasonal variations.
- **Customer purchase behavior** analyzed to determine repeat purchase rates.

## 📌 Insights & Recommendations
- **VIP Customers (Segment 1):** Should be retained through loyalty programs and exclusive offers.
- **Average Customers (Segment 0):** Encouraged to shop more frequently through discounts.
- **Inactive Customers (Segment 2):** Targeted with re-engagement campaigns.
- **Sales Strategy Optimization:** Focus on high-demand products and optimize inventory.

## 📌 Next Steps
- Experiment with **Hierarchical Clustering** and **DBSCAN** for better segmentation.
- Develop **personalized marketing strategies** based on segments.
- Deploy a **real-time customer segmentation and sales dashboard**.


## 🤝 Contributing
Feel free to fork this repository, make improvements, and submit pull requests!

## 📧 Contact
If you have any questions, reach out at **haticekcbas@gmail.com**.

---
**🚀 Happy Coding!** 🎯
