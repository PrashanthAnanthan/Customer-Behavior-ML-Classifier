Project Overview
This project simulates an e-commerce environment to predict whether a visitor will purchase a product based on their site behavior. I built this to demonstrate the full ML Lifecycle, from data generation to model evaluation and probability visualization.

 Key Features
Synthetic Data Generation: Created a dataset of 1,000 customers using variables like spending_time, deep_scrolling, and add_to_cart.

Binary Classification: Implemented Scikit-Learn's Logistic Regression to classify buyers vs. non-buyers.

Performance: Achieved a 95.50% Accuracy score on unseen test data.

Visual Analytics: * Scatter Plots: Visualized behavioral clusters.

Sigmoid Curve: Plotted the probability transition to show the model's decision-making process.

 Business Logic & Thresholds
The model doesn't just predict 1 or 0; it calculates probabilities. In a real-world business scenario, this allows for Threshold Tuning:

Low Threshold: Catch more potential buyers (Aggressive Marketing).

High Threshold: Focus on high-certainty buyers to save on voucher costs (Conservative Strategy).
