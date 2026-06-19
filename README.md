*********************************************************************
# SUPERSTORE SALES ANALYSIS

This is a project that uses Python with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

to clean, analyze and visualize data.
*********************************************************************
# This project answers the following business questions:
1. Which region generates the most total sales?
2. What are the top 5 products by total revenue?
3. What do monthly sales trends look like over time?
4. Which category has the best profit margin?
5. Which sub-categories are losing money?
6. Does offering a higher discount actually hurt profit?
7. Which customer segment (Consumer, Corporate, Home Office) is most valuable?
8. What's the average order value per region?
9. Which shipping mode is used most, and does it correlate with order size?
10. Which state has the most orders but lowest profit? (hidden underperformer)
*********************************************************************
# Key findings:
- **Most total sales:** West ($725457.82)
- **Highest profit margin:** Technology (17.4%)
- **Biggest underperformer:** Texas (Total profit of *-25729.36* with 985 total orders)
- **Sub-categories with negative total profit:** Bookcases ($-3472.56), Supplies ($-1189.10) & Tables ($-17725.48)
- **Most valuable customer segment:** Consumer (with a total profit of *$134119.21*)
- **Higher discounts tend to lead to negative profit:** Discounts between 30-40% averaged a profit of *$-50.24*, meanwhile orders that offered a discount of 50% or more, averaged a profit of *$-107.65*
*********************************************************************
# After cloning this repo:

1: Get the Dataset
Download the dataset and place it inside the `data/` directory:

👉 Superstore Dataset (Kaggle): https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

2: Install Dependencies
Run this command in your terminal: `pip install -r requirements.txt`

OR install it directly: `pip install pandas numpy matplotlib seaborn jupyter`

3: Launch Jupyter Notebook
For environment run: `jupyter notebook` and open the `notebooks/` to check the notebooks

4: Test Your Setup
*********************************************************************
# NOTEBOOK SECTIONS
1. Imports and setup
2. Data import and exploring
3. Data Cleaning using pandas
4. Answering business questions using SQL queries
5. NumPy analysis
6. Visualizations
*********************************************************************
# HAPPY CODING & DATA EXPLORATION!
