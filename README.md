# Sales-Analysis-and-Customer-Segmentation
This project performs a comprehensive analysis of sales data and customer segmentation for an e-commerce platform. Using Python and various data science libraries, we dive deep into product popularity, pricing strategies, and customer behavior to extract valuable business insights.

## Key Features
- Data cleaning and preprocessing of raw e-commerce data
- Analysis of product popularity based on rating counts
- Calculation of average discounts across product categories
- Customer segmentation using K-means clustering based on product ratings
- Visualization of key metrics and segments

## Technologies Used
- Python
- Pandas for data manipulation
- Scikit-learn for machine learning (K-means clustering)
- Matplotlib and Seaborn for data visualization

## Main Components
1. **Data Cleaning**: Handles currency symbols, converts data types, and merges product categories for simplified analysis.
2. **Sales Analysis**: 
   - Identifies top-selling products
   - Calculates average discounts by category
   - Determines highest-rated product categories
3. **Customer Segmentation**: 
   - Uses K-means clustering to segment product categories based on average ratings
   - Provides insights into high-performing and underperforming product segments
4. **Visualizations**:
   - Bar charts for product popularity and average discounts
   - Scatter plot for product category segments

## Key Insights
- Identification of best-selling products and their characteristics
- Understanding of discount strategies across different product categories
- Segmentation of product categories based on customer ratings, revealing potential areas for improvement or marketing focus

## How to Use
1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the main script: `python SalesAnalysis.py`
4. View the generated visualizations and printed analysis results

## Future Improvements
- Implement time series analysis for seasonal trends
- Integrate machine learning models for sales prediction
- Develop an interactive dashboard for real-time data exploration
