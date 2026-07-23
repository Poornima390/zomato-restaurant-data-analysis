# Zomato Restaurant Data Analysis
## Data Science Internship – Task 1
This project analyzes the Zomato restaurant dataset to extract insights related to restaurant 
ratings, cuisines, locations, pricing, online ordering, table booking, and customer preferences.
## Objective
The objective of this project is to analyze restaurant and review data to understand:
- Restaurant rating patterns
- Popular cuisines
- Location-wise restaurant distribution
- Relationship between price and rating
- Customer preferences
- Factors affecting restaurant popularity and ratings
## Dataset
The dataset used in this project is the Zomato Restaurant Dataset obtained from Kaggle.
### Dataset Details
- Original records: 56,252
- Features: 13
- Location: Bangalore, India
### Main Features
- `name` – Restaurant name
- `location` – Restaurant location
- `online_order` – Online ordering availability
- `book_table` – Table booking availability
- `rate` – Restaurant rating
- `votes` – Number of customer votes
- `rest_type` – Type of restaurant
- `dish_liked` – Popular dishes
- `cuisines` – Cuisines offered
- `approx_cost` – Approximate cost for two people
- `listed_in(type)` – Restaurant category
## Data Cleaning
The following preprocessing steps were performed:
- Handled missing values.
- Removed duplicate records.
- Removed corrupted records containing misplaced text.
- Converted restaurant ratings into numeric format.
- Converted approximate cost into numeric format.
- Cleaned categorical columns for analysis.
## Exploratory Data Analysis
The following analyses were performed:
- Top restaurant locations
- Highest-rated cuisines
- Price vs rating analysis
- Rating distribution
- Online order analysis
- Table booking analysis
- Restaurant type distribution
- Cost distribution
- Votes vs rating analysis
- Average rating by location
## Visualizations
The project includes:
- Bar charts
- Histograms
- Scatter plots
- Correlation heatmap
- Cuisine WordCloud
- Popular dishes WordCloud
## Key Findings
- BTM is one of the major restaurant hotspots.
- North Indian and Chinese cuisines are among the most popular.
- Most restaurants provide online ordering.
- Table booking is available in a smaller number of restaurants.
- Most restaurants have ratings between 3.5 and 4.2.
- Price has a weak relationship with restaurant ratings.
- Restaurants with higher customer engagement generally receive more votes.
## Business Recommendations
1. Partner with highly rated restaurants to improve platform quality.
2. Focus promotional campaigns on restaurant hotspot locations.
3. Promote popular cuisines through personalized recommendations.
4. Encourage online ordering through offers and discounts.
5. Use customer ratings and preferences to build personalized restaurant recommendations.
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Google Colab
## Project Files
- `Zomato_Dataset_Analysis.ipynb` – Complete analysis notebook
- `zomato_cleaned.csv` – Cleaned dataset
- `README.md` – Project documentation
## Internship
This project was completed as part of the Data Science Internship – Task 1.
