# Hotel-Discount-Optimization

🏨 Hotel Discount Optimization Challenge
Problem Statement
Hotels regularly run discount campaigns to attract customers, but not every discount strategy is effective. Some discounts lead to substantial room bookings, while others reduce revenue without increasing occupancy.
Your challenge is to analyze hotel reservation snapshots and identify the most effective discount strategies across different hotels, dates, and star ratings.

Why This Matters
Revenue Optimization: Offering the right discount at the right time maximizes bookings while protecting revenue.
Inventory Management: Hotels with too many empty rooms risk losses, while overbooking can cause customer dissatisfaction.
Competitive Strategy: Understanding which hotel categories respond better to discounts helps in pricing and promotions.

Dataset
Each row represents a snapshot of available hotel rooms with associated discounts.
Field
Description
Snapshot ID
Identifier for the snapshot batch (all rows collected at the same time).
Snapshot Date
Date when the snapshot was taken.
Checkin Date
Date of the customer’s check-in.
Days
Number of nights (length of stay).
Original Price
Price before discount.
Discount Price
Price after discount.
Discount Code
Identifier for the discount type applied.
Available Rooms
Number of rooms available at that time (may include negative placeholders like -1 for missing).
Hotel Name
Name of the hotel.
Hotel Stars
Star rating of the hotel (e.g., 3, 4, 5).


Tasks
Discount Effectiveness
Analyze which discount codes result in the largest booking potential (reduction in available rooms).
Price Elasticity Modeling
Build models to estimate the relationship between discount percentage and available rooms.
Identify “sweet spots” where discounts maximize bookings without unnecessary revenue loss.
Hotel Segmentation
Cluster hotels based on price levels, discount strategies, and star ratings.
Identify segments like “Luxury Hotels that rarely discount” vs. “Mid-range hotels that aggressively discount.”

Evaluation
Regression / Elasticity: R², RMSE between predicted vs. actual demand (available rooms).
Clustering: Silhouette score and clear business interpretation.
Insights: Actionable recommendations for hotel managers on how to adjust discounts by hotel type and season.

Deliverables
A predictive model estimating expected demand under different discount levels.
Clusters of hotels with distinct discounting strategies.
A business report/dashboard showing how hotels can optimize their discounts to maximize both occupancy and revenue.

⚡ Your mission: Help hotels uncover the science behind discounts—maximizing occupancy without giving away rooms too cheaply!

