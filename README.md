# Food Delivery Cost and Profitability Analysis

This project provides a comprehensive analysis of the costs and profitability associated with food delivery services. The goal is to identify key factors driving losses and propose strategies for optimizing commission and discount rates to improve profitability.

## Overview
The project focuses on understanding the financial performance of a food delivery service by analyzing order data. By calculating various metrics related to costs and revenue, it identifies areas where the service is incurring losses and suggests a more profitable approach.

## Dataset
The dataset used in this analysis consists of food delivery orders, including details such as:
- Order value
- Delivery fee
- Payment processing fee
- Discounts and offers
- Commission fee

## Analysis Steps
1. **Data Preprocessing**: 
   - Converted date and time columns to the appropriate format.
   - Extracted and standardized discount values from the `Discounts and Offers` column.
   - Ensured all monetary values were in a suitable format for calculations.

2. **Cost and Profit Calculation**:
   - Calculated the total costs for each order, including delivery fees, payment processing fees, and discounts.
   - Determined the revenue generated from commission fees and calculated the profit by subtracting total costs from revenue.

3. **Visualization**:
   - Visualized the distribution of profit per order and the breakdown of total costs.
   - Highlighted the impact of current discount and commission strategies on overall profitability.

4. **Simulated Strategy**:
   - Analyzed profitable orders to determine optimal commission and discount percentages.
   - Simulated the impact of recommended commission (30%) and discount (6%) rates on profitability.

## Key Findings
- The current discount strategies are leading to significant losses, with costs exceeding revenue.
- Higher commission rates and lower discount rates contribute to profitability.
- A simulated strategy with 30% commission and 6% discount shows a potential increase in overall profitability.

## Visualization
- **Profit Distribution**: The histogram shows a wide distribution of profit per order, with a notable number of orders resulting in a loss.
- **Cost Breakdown**: The pie chart illustrates the proportion of total costs, highlighting the significant impact of discounts.
- **Profitability Comparison**: KDE plots compare actual vs. simulated profitability, showing the potential improvement with recommended rates.

## Simulated Strategy
By analyzing the characteristics of profitable orders, the project proposes a new strategy:
- **Recommended Commission Percentage**: 30%
- **Recommended Discount Percentage**: 6%
This strategy is simulated, and the results indicate a shift towards higher profitability.

## Conclusion
The analysis identifies the need for a strategic adjustment in commission and discount rates to achieve profitability in food delivery services. The simulated strategy provides a guideline for making informed decisions to improve financial performance.
