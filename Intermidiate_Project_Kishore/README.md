# Automatic K-Means Clustering Project

## Description
This project performs automatic clustering on any uploaded dataset using the K-Means algorithm. 
It identifies patterns in data and groups similar records into clusters.

## Dataset
- Source: User-uploaded CSV file
- The dataset can contain multiple features (numeric columns are used)

## Steps Performed
1. Data Loading using CSV upload
2. Selection of numeric columns
3. Handling missing values
4. Feature scaling using StandardScaler
5. Finding optimal K using the Elbow Method
6. Applying K-Means clustering
7. Evaluating using Silhouette Score
8. Generating cluster insights
9. Visualisation of clusters
10. Exporting a clustered dataset

## Results
- Clusters are created based on similarity
- Silhouette Score indicates clustering quality
- Cluster-wise mean values help in understanding patterns

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## How to Run
1. Open in Google Colab
2. Run all cells
3. Upload any CSV dataset
4. View clustering results and download the output file

## Output
- Clustered dataset saved as: `clustered_output.csv`

## Author
Kishore
