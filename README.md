## -Discount-Strategy-Impact-Analysis
Data analysis and presentation as part of a Data Science Bootcamp at WBS Coding School

# Eniac Discount and Revenue Dilemma 

The project aims to provide a data-driven answer to the ongoing debate at Eniac:
 **Is it beneficial to discount products?**
While the Marketing Team believes discounts drive growth and acquisition, 
The Board of Investors is concerned about the "high volume, low revenue" trend and
 The potential erosion of Eniac's "Quality" brand positioning.

## 📊 Key Analytical Questions

### 1. The Discount Landscape
* **Volume:** How many products are currently being discounted?
* **Depth:** What is the average discount percentage relative to the MSRP?
* **Revenue Computation:** Total Revenue is calculated as:

    ## 🛠️ Methodology & Technical Stack
* **Python:** Data extraction and cleaning from the main database.
* **Python (Pandas/Seaborn/Matplotlib):** Statistical distribution, modeling, plotting, and visualization.
* ** 🧹 Data Cleaning Process Included
* **Handling Duplicates:** Identified and removing duplicates
* **Filtering Order Status:** Excluded "Cancelled" or "Pending" orders; only "Completed" orders were analysed.
* **Date Standardization:** Unified timestamp formats to accurately align sales with seasonal events like Black Friday.

### 3. Product Portfolio, Market Performance & Seasonality Analysis 
* **Classification:** Products are categorized to observe behavior across price points.
* **Price Distribution:** How prices are spread across different categories to identify over-discounted segments.
* **Impact of Special Dates:** Analysis of how Black Friday and Christmas affect order volume vs. profit margins.
* **Time Period:** [January 2017] to [March 2018].
* **Order Status:** Only "Completed" (Shipped/Delivered) orders are used for revenue calculations.

## 🚀 Recommendations for Data Improvement
To further settle the debate, we recommend implementing:
1. **Remove all discounts:** Monitor if discounted customers convert into full-price repeat buyers.
2. **Newsletter 5% discount for new customers**.
3. **Real-time data on market pricing to validate discount necessity**.
4. **Developed as practicals at WBS Data Science Bootcamp**
   
