Customer Segmentation Using K-Means Clustering

Overview

This project implements customer segmentation using the K-Means Clustering algorithm. The goal is to analyze customer data and group them into clusters based on features like age, income, spending score, and membership years. The project involves univariate, bivariate, and multivariate clustering, along with detailed exploratory data analysis (EDA).

The segmentation helps businesses understand their customer base better, enabling personalized marketing strategies and improving customer experience.

Features
Exploratory Data Analysis (EDA):

Visualizations for understanding the distribution and correlation between variables.
Gender-wise analysis with KDE and boxplots.
Clustering Analysis:

Univariate Clustering: Clustering based on a single feature (e.g., income).
Bivariate Clustering: Clustering based on two features (e.g., income and spending score).
Multivariate Clustering: Clustering based on multiple features using PCA for visualization.
Elbow Method: Determine the optimal number of clusters.

Silhouette Score: Evaluate the quality of clusters.

Dataset
The dataset includes customer attributes such as:

Age
Gender
Income
Spending Score
Membership Years
Make sure to upload the dataset (customer_segmentation_data.csv) to the appropriate folder.

Prerequisites
Ensure you have the following installed:

Python 3.8+
Required Libraries:
bash
Copy code
pip install pandas seaborn matplotlib scikit-learn
How to Run the Project
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/Customer-Segmentation-KMeans.git
cd Customer-Segmentation-KMeans
Install Dependencies
Install all required libraries:

bash
Copy code
pip install -r requirements.txt
Prepare the Dataset

Place your customer_segmentation_data.csv file in the same directory as the script.
Ensure the dataset follows the required format.
Run the Script
Execute the Python script:

bash
Copy code
python customer_segmentation.py
View Visualizations and Results

EDA visualizations and clustering outputs will be generated.
Clustering results will be displayed on the console.
Methodology
1. Data Preprocessing
Label Encoding: Encoded the gender column to numerical values.
Feature Selection: Selected relevant features for clustering.
2. Exploratory Data Analysis (EDA)
Used KDE plots, boxplots, and pairplots for feature distribution and gender-based analysis.
Visualized the correlation heatmap for feature relationships.
3. Clustering Analysis
Performed univariate, bivariate, and multivariate clustering using the K-Means algorithm.
Applied the Elbow Method to determine the optimal number of clusters.
Verified clustering quality using the Silhouette Score.
4. Principal Component Analysis (PCA)
Reduced multivariate clustering dimensions to 2D for visualization.
Visualized clusters in a scatter plot with principal components.
Results
Univariate Clustering:
Segmentation based on income grouped customers into three clusters.

Bivariate Clustering:

Used income and spending score to create four clusters.
Visualized cluster centers to identify high/low-income and spending patterns.
Multivariate Clustering:

Incorporated additional features like age, gender, and purchase frequency.
Achieved six distinct clusters and visualized them using PCA.
Silhouette Score Analysis:

Provided insights into cluster quality and helped select the optimal number of clusters.
Outputs
Key Visualizations
Distributions:
KDE plots, boxplots, and pairplots for feature analysis.
Elbow Method Plots:
For univariate, bivariate, and multivariate clustering.
Cluster Visualizations:
Scatter plots with cluster centers and PCA-based visualizations.
Metrics
Silhouette Score: Evaluated clustering effectiveness for different numbers of clusters.
Applications
This project can be applied to:

Marketing Campaign Optimization
Customer Retention Strategies
Personalized Product Recommendations

Folder Structure
bash
Copy code
Customer-Segmentation-KMeans/
│
├── customer_segmentation.py         # Main Python script
├── customer_segmentation_data.csv   # Dataset (not included, upload your own)
├── README.md                        # Project Documentation
└── requirements.txt                 # Dependencies

Author
Akash Verma
Feel free to reach out via akashverma35722@gmail.com or connect on LinkedIn.

Feel free to modify this README as needed!






