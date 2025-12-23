# Blinkit-Regional-Performance-Analysis
Retail sales analysis using Power BI to evaluate product performance, pricing, and outlet efficiency. The dashboard highlights key revenue drivers across categories, outlet sizes, and locations, supporting data-driven decisions on product mix, pricing, and expansion strategy.
## Project Objective
The objective of this project is to visualize how sales and orders perform across different outlets and item categories using the Blinkit Dashboard, while adhering strictly to Blinkit’s brand theme and color scheme.
## Data Cleaning & Preparation
#### Item Visibility:
Item visibility values recorded as 0% were treated as missing data rather than true absence of shelf space, as zero visibility is unrealistic in an operational retail environment. These values were handled during data cleaning to avoid distortion of visibility-related insights.
#### Item Weight:
Missing values in the Item Weight column were replaced using the average weight of similar items within the same outlet. Similarity was determined using item identifier, MRP, and fat content to ensure accuracy and consistency.
## Insights & Recommendations
1. Outlet Performance
#### Insight:
- Supermarket Type 1 dominates both sales and order volume.
- Grocery Stores generate only 2% of total revenue but account for 12% of total orders, indicating that customers make smaller, lower-value purchases.
- Supermarket Type 2 shows a similar pattern, though to a lesser extent.
#### Recommendation:
Introduce bundle offers, cross-selling strategies, and minimum-basket promotions in grocery stores and Supermarket Type 2 to increase average order value and improve revenue efficiency per order.
2. Location Tier Performance
#### Insight:
- Tier 3 locations dominate both orders and revenue overall.
- Supermarket Type 1, despite being the only outlet in Tier 2, still ranks second in performance.
- Supermarket Type 1 operates across all three tiers, explaining its dominance.
- Supermarket Type 3, operating only in Tier 3, generates more revenue than grocery stores that operate across two tiers.
#### Recommendation:
Expand Supermarket Type 3 into Tier 2 locations, where sales potential is strong. Replicate Tier 3 strategies in Tier 2 to unlock additional revenue while maintaining cost efficiency.
3. Outlet Size Performance
#### Insight:
Medium-sized outlets dominate both orders and revenue, outperforming large outlets.
#### Recommendation:
Prioritize investment and expansion of medium-sized outlets, as they appear to provide the optimal balance between operational cost, customer traffic, and revenue generation.
4. Pricing, Weight, and Revenue Relationship
#### Insight:
- There is no strong correlation between item weight and MRP, indicating that pricing is driven more by brand and product category than physical quantity.
- Revenue increases with item weight, suggesting customers purchase more based on quantity rather than list price.
#### Recommendation:
Adopt weight- and quantity-based pricing and promotions, especially for mid-weight products with strong revenue potential. Review pricing tiers that may not reflect actual customer value perception.
5. Product Attributes (Fat Content)
#### Insight:
- Low-fat items contribute 64.73% of total revenue, indicating a clear customer preference.
- Regular items still contribute meaningfully but at a lower share.
#### Recommendation:
Increase stock availability and visibility of low-fat products while maintaining a controlled inventory of regular items to avoid stockouts and excess holding costs.
6. Category Performance
#### Insight:
Fruits and vegetables dominate both revenue and order volume, making them the strongest-performing category.
#### Recommendation:
Ensure consistent availability of fruits and vegetables and use them as anchor products for promotions, bundles, and customer retention strategies.
7. Item Visibility Analysis
#### Insight:
- The scatter plot shows no strong correlation between item visibility and the Parameter DAX metric.
- Performance is largely unaffected by increased visibility, with a few isolated outliers.
- Recommendation:
- Shift focus from shelf visibility alone to pricing optimization, category placement, and brand positioning, which appear to have a greater influence on performance.
