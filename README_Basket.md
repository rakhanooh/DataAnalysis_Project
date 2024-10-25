# DataAnalysis_Project
<h1>Market Basket Analysis Project</h1>
<h2>Market Basket Analysis (Supermarket Dataset)</h2>

<h3>Overview</h3>
This project involves performing Market Basket Analysis using a supermarket transaction dataset to identify patterns in customer purchases. The analysis focuses on discovering which items are frequently bought together, helping the retailer provide better product recommendations, enhance customer engagement, and improve sales strategies.

<h3>Objectives</h3>
Detect Common Purchase Patterns: Identify frequently bought-together items to understand customer purchasing behavior.
Analyze Item Frequency: Determine the most popular products in the store.
Apply Apriori Algorithm: Discover item combinations using association rules.
Generate Actionable Insights: Create recommendations to optimize marketing and sales approaches.
<h3>Data Description</h3>
The dataset includes the following columns:

BillNo: Unique transaction ID.
Itemname: Product name.
Quantity: Number of each product per transaction.
Date: Timestamp of each transaction.
Price: Price per product.
CustomerID: Unique identifier for each customer.
Country: Customer's country of residence.
Data Preprocessing
Removed Duplicates: Cleaned data by eliminating duplicate entries.
Addressed Missing Values: Filled or removed rows with missing data.
Data Type Conversion: Adjusted numeric values and dates for consistency.
Formatted Data: Grouped items by transaction, converted quantities to Boolean for analysis, and standardized strings.

<h3>Methodology: Apriori Algorithm</h3>

We applied the Apriori algorithm to find associations between items bought together frequently. The algorithm identifies product combinations with a minimum support threshold of 2%.

<h4>Lift > 1</h4> Indicates a significant association between items.
<h4>Highest Lift</h4> 22.8, showing a strong link between specific product pairs.
Results and Conclusion
The analysis highlighted strong associations between items with a high lift value, suggesting they are often bought together. These findings enable the retailer to make targeted product recommendations, potentially increasing customer satisfaction and sales.

<h3>Conclusion</h3>
The association rule analysis using the lift metric reveals that certain products are frequently purchased together when their lift value exceeds one, with the strongest observed association having a lift value of 22.8.

<h3>Usage</h3>
1. Install libraries needed for data handling and analysis.

2. Load data into a suitable format for exploration.
    
3. Clean the data by handling missing values and duplicates.
   
4. Preprocess to structure data for the Apriori algorithm.
   
5. Run Apriori to discover frequent item patterns and associations.

This sequence prepares data for association rule mining effectively.

<h4>Submitted by:</h4>

Lamar Waleed Fattah

Rakha Matuq Nooh

Institution: College of Computing, Umm Al-Qura University
