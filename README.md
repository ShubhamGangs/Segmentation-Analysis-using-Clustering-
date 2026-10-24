# Portfolio Projects: Unsupervised Learning & Clustering

Welcome to this comprehensive analytics notebook. This file contains two major data science workflows focused on extracting insights and patterns from multi-dimensional datasets using Unsupervised Machine Learning, Clustering, and Dimensionality Reduction techniques.

---

## Project 1: Credit Card Customer Segmentation (AllLife Bank)

### Objective
To identify distinct segments within AllLife Bank's existing customer base. These groups are classified using spending patterns and contact channel preferences to enable customized marketing strategies and improve service delivery.

### Data Elements
- **Financial Indicators:** Average Credit Limit, Total Credit Cards.
- **Interaction Channels (Yearly):** Total Visits Bank, Total Visits Online, Total Calls Made.

### Methodology
1. **Exploratory Data Analysis (EDA):** Visualization of features using combined boxplots and histograms alongside descriptive statistics.
2. **Dimensionality Reduction:** Application of **t-SNE** in both 2D and 3D spaces across multiple perplexity values ($5$ to $150$) to evaluate cluster separation.
3. **Clustering:** K-Means clustering algorithm optimized using the Elbow Method (Within-Cluster Sum of Squares) and Silhouette score analysis ($K=3$).
4. **Strategic Insights:** Formulating channel-specific recommendations for each segmented user persona.

---

## Project 2: Adidas vs. Nike Competitive Product Clustering

### Objective
To perform competitive market analysis and product grouping of footwear from Adidas and Nike based on pricing configurations, customer sentiment, and promotional trends.

### Data Elements
- **Pricing Metrics:** Listing Price, Sale Price, Discount Percentages.
- **Feedback Metrics:** Ratings, Total Reviews.
- **Brand Identifier:** Adidas vs. Nike.

### Methodology
1. **Data Preprocessing:** Imputation of missing/zero-valued listing prices using corresponding sale values, and deduplication of records.
2. **Bivariate Correlation Analysis:** Checking relationships between prices, discount frequencies, and user engagement metrics across brands.
3. **Clustering:** $K$-Means clustering optimized for maximum silhouette score cohesion ($K=4$).
4. **Competitive Profiling:** Mapping cluster patterns back to brand dynamics, highlighting differences in discount policies and premium inventory structures.

---
