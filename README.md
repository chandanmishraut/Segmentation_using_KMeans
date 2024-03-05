# Segmentation_using_KMeans
Performing end-to-end data analysis, including preprocessing, exploration, clustering, and classification using Python's data science libraries, resulting in a Decision Tree model with 93.1% accuracy for customer segmentation.

Importing Libraries: Essential libraries like Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn are imported. StandardScaler, PCA, KMeans, DecisionTreeClassifier, and other modules are loaded for data preprocessing, dimensionality reduction, clustering, and classification.

Loading the Dataset: A dataset containing information about customers is loaded into a Pandas DataFrame. The dataset comprises 8950 entries with 18 columns, including numerical and categorical features.

Exploratory Data Analysis (EDA): Basic EDA is performed to understand the structure and characteristics of the dataset. This includes checking shape, info, summary statistics, and handling missing values.

Data Preprocessing: Missing values in the dataset are imputed with mean values. The 'CUST_ID' column, deemed unnecessary, is dropped from the DataFrame.

Data Visualization: Various visualizations such as KDE plots, histograms, and heatmaps are generated to explore the distribution, relationships, and correlations between different features in the dataset.

Data Scaling and Dimensionality Reduction: The dataset is scaled using StandardScaler, and dimensionality reduction is performed using Principal Component Analysis (PCA) to visualize high-dimensional data in two dimensions.

Clustering: KMeans clustering is applied to identify natural groupings (clusters) within the dataset. The optimal number of clusters is determined using the Elbow Method.

Cluster Visualization: The clustered dataset is visualized in two dimensions using scatterplots, showing distinct clusters identified by KMeans.

Model Building: A Decision Tree Classifier is trained on the clustered dataset to predict the cluster label for new data points. The dataset is split into training and testing sets for model evaluation.

Model Evaluation: The Decision Tree model's performance is evaluated using confusion matrix and classification report metrics, achieving an accuracy of 93.1%.

Model Persistence: The trained Decision Tree model is saved to disk using pickle for future use in making predictions on new data.
