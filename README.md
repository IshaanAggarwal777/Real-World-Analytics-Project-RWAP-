Football Players Data Analysis and Machine Learning Model
Project Overview
This repository contains an in-depth analysis and machine learning project based on the Male Football Players Data available on Kaggle. The project includes data preprocessing, feature selection, and the development of an unsupervised machine learning model to cluster football players based on various attributes. Additionally, an analytical dashboard is provided to explore the dataset interactively.

Key Components:
Dataset: Male Football Players Data
Analytical Dashboard: Interactive dashboard for data exploration and visualization.
Machine Learning Model: K-Means clustering model for grouping players based on their attributes.
Dataset
The dataset used in this project can be found on Kaggle and contains detailed information about male football players. The data includes features such as:

**Overall and Potential ratings**
Physical attributes like Height (cm), Weight (kg), and Age
Performance metrics including Pace, Shooting, Passing, Dribbling, Defending, and Physic
Player Positions and various Attacking and Defending skills
The full dataset is available for download here.

**Analytical Dashboard**
The analytical dashboard allows users to explore the dataset interactively. Key features of the dashboard include:

Visualization of player distributions based on various attributes.
Filtering options to narrow down players by specific criteria.
Graphical representation of the clustering results from the machine learning model.

**How to Use:**
Download or clone the repository.
Run the dashboard script (instructions provided in the dashboard directory).
Explore the data using the interactive visualizations.
Machine Learning Model
This project applies K-Means Clustering to group football players into distinct clusters based on selected features. The optimal number of clusters was determined using the Elbow Method and Silhouette Analysis.

**Model Details:**
Feature Selection: The features used for clustering include overall ratings, potential, physical attributes, and performance metrics.
Clustering Analysis: The model was evaluated using metrics such as the Silhouette Score and Davies-Bouldin Score to determine the quality of clustering.
Results: The model found that clustering into 2 to 5 groups provided meaningful separations within the dataset.

**How to Run the Model:**
Ensure that the required libraries (e.g., scikit-learn, pandas, matplotlib) are installed.
Run the machine_learning_model.py script to execute the clustering process.
The script outputs evaluation metrics and visualizations, which can be further analyzed.
