# BUMK744 Team Assignment II: Customer Segmentation using PCA and K-Means

## Project objective
This project analyzes customer-level marketing campaign data to identify meaningful customer segments and recommend targeted marketing actions.

## Dataset
Customer Personality / Marketing Campaign dataset. The notebook currently imports the dataset from a raw GitHub CSV URL.

## Methods used
1. Principal Component Analysis (PCA)
2. K-Means Clustering

## Analysis flow
1. Load and inspect the data
2. Handle missing `Income` values
3. Create marketing variables such as `Age`, `Children`, `TotalSpend`, `TotalPurchases`, `CustomerTenureDays`, and `TotalCampaignAccepted`
4. Remove unrealistic age outliers and irrelevant/constant columns
5. Standardize the modeling variables
6. Run PCA and retain five principal components
7. Run K-Means clustering on the PCA scores
8. Profile and interpret four customer segments
9. Recommend targeted marketing actions for each segment

## Final segments
- Cluster 0: Low-Engagement Family Customers
- Cluster 1: Premium High-Value Customers
- Cluster 2: Deal-Seeking Omnichannel Families
- Cluster 3: Young Digital Browsers / Low Converters

## How to run
Open `Marketing_Research_Team_Assignment_2.ipynb` in Google Colab and run all cells from top to bottom.

## Notes for submission
Use the Google Colab sharing link for the final assignment submission if the instructor specifically requested a Colab notebook with general access. Use this GitHub repository as a backup/shareable project version for the team.
