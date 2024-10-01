### Summary and Analysis of the Three Plots:

#### 1. **Bar Plot: Size vs Count**
   - **Description**: This bar plot represents the distribution of product sizes and their respective counts. The x-axis shows different sizes (S, M, L, XL, etc.), and the y-axis represents the frequency of each size.
   - **Findings**:
     - The most popular size is **M (Medium)** with around **6806** purchases.
     - Sizes **L (Large)** and **XL (Extra Large)** follow closely with **6646** and **6326** purchases, respectively.
     - Smaller sizes like **XS (2587)** and **S (4558)** are less popular compared to the larger sizes.
     - Niche sizes like **6XL** and **4XL** have the least demand, indicating their infrequent sales.
   - **Insights**:
     - The data suggests a preference for medium-to-large sizes among customers, which may reflect a general trend in the target market or demographic.
     - Retailers should focus on stocking larger quantities of M, L, and XL sizes as they account for a significant portion of sales.

#### 2. **Histogram: Distribution of Order Amount**
   - **Description**: This histogram, along with a kernel density estimate (KDE) plot, shows the distribution of order amounts (total sales values). The x-axis represents the order amount, and the y-axis represents the frequency of those amounts.
   - **Findings**:
     - Most orders are concentrated between **100 and 1000** in amount.
     - The distribution shows a right-skewed pattern, where a few orders have significantly higher amounts (above 3000).
     - A small number of orders exceed **5000**, but these are outliers and rare.
   - **Insights**:
     - The majority of orders are low to medium in value, which suggests that customers are frequently making smaller purchases.
     - The presence of high-value outliers might indicate bulk or corporate buyers making larger orders.
     - Understanding the distribution helps in setting pricing strategies and promotional offers for the most common order ranges (e.g., discounts for purchases above 500).

#### 3. **Correlation Heatmap: Quantity (Qty) vs Order Amount**
   - **Description**: This heatmap visualizes the correlation between the `Qty` (quantity of products ordered) and `Amount` (total order value). The correlation values are displayed on the plot.
   - **Findings**:
     - The correlation between **Qty** and **Amount** is quite low, approximately **0.072**, indicating a weak positive correlation.
     - This means that the number of items ordered (Qty) doesn't significantly influence the total order amount (Amount), or the relationship is not strong.
   - **Insights**:
     - Since there is no strong correlation between quantity and amount, this suggests that higher quantities do not always result in higher total amounts. For instance, customers could be ordering a large quantity of low-cost items or small quantities of higher-priced items.
     - Further investigation could be done by segmenting products into price ranges or categories to see if certain types of products show stronger correlations between quantity and amount.


4. **Quantity vs Size of Items Sold**
   - **Plot Type**: Bar Plot
   - **Description**: This plot represents the quantity of items sold according to their sizes. The 'Qty' axis shows the total number of units sold, while the 'Size' axis lists different size categories such as M, L, XL, XXL, etc.
   - **Findings**:
     - **M size** is the most sold item, with over **6000 units**.
     - Other popular sizes include **L** and **XL**, both with quantities above 5000 units.
     - The sale of very large sizes like **5XL** and **4XL** is minimal, almost negligible compared to other sizes.
     - Very small sizes like **XS** and **Free** also exhibit low sales.

5. **Order Status by Courier Status**
   - **Plot Type**: Count Plot
   - **Description**: This plot visualizes the count of orders based on their courier status (On the Way, Shipped, Unshipped) and different order statuses (Shipped - Delivered to Buyer, Cancelled, Pending, etc.).
   - **Findings**:
     - The majority of orders fall under the **'Shipped - Delivered to Buyer'** status, indicating a healthy completion of deliveries.
     - There is a significant number of **'Cancelled'** orders (approximately 5000), which might indicate issues related to order handling or customer decision changes.
     - Most of the orders with the 'Shipped' status were successful, with few returns or cancellations.
     - Very few orders remain **'Pending'** or **'Unshipped'**, indicating that most orders were processed and moved to the shipping stage.

6. **Histogram of Category Sales**
   - **Plot Type**: Histogram
   - **Description**: This histogram presents the frequency of sales for different product categories like T-Shirts, Shirts, Blazers, Trousers, etc.
   - **Findings**:
     - **T-Shirts** and **Shirts** dominate sales with over **14,000** and **13,000 units** respectively.
     - **Blazers** come in third with over **6,000** units sold, indicating a preference for more casual or semi-formal attire.
     - Other categories such as **Trousers** (2,459 units) have relatively fewer sales, while products like **Wallets, Perfumes**, and **Shoes** have very minimal sales figures.

     


