# L3T04 - Unsupervised Learning - K-means Clustering

## K-Means Clustering Analysis

### Overview
This task involves performing K-means clustering analysis on the Country-data.csv dataset. The objective is to segment countries based on their economic indicators such as GDPP, child mortality, and inflation. The notebook `Kmeans_task.ipynb` will be used to complete the analysis.

### Dataset
Country-data.csv: Contains country wise data on economic indicators like child-mortality, health, GDPP, inflation etc. [Source](<Country-data.csv>)

### Instructions
#### Setup and Installation
1. **Clone the Repository**
   - Clone this repository to your local machine:
     ```
     git clone https://github.com/vswapna3202/L3T04.git
     ```
2. **Navigate to the Project's Folder**
   - Navigate to the folder containing the project:
     ```
     cd L2T04 or cd <your-task-folder>
     ```

### Workflow
1. **Open the Notebook**
   - Open the Jupyter notebook `Kmeans_task.ipynb` to begin the analysis.

2. **Load the Dataset**
   - Load the `Country-data.csv` dataset into the notebook.

3. **Data Preprocessing**
   - Drop any non-numeric columns from the dataset.

4. **Exploratory Data Analysis (EDA)**
   - Plot nine different scatter plots with different combinations of variables against GDPP.
   - Note the plots that look the most promising for separating into clusters.

5. **Normalization**
   - Normalize the dataset using MinMaxScaler from sklearn.

6. **Finding the Optimal Number of Clusters**
   - Find the optimal number of clusters using the elbow and silhouette score method.

7. **Model Training**
   - Fit the scaled dataset to the optimal number of clusters.

8. **Model Evaluation**
   - Report back on the silhouette score of the model.

9. **Visualizing Clusters**
   - Visualize the clusters for the following two groups:
     - Child mortality vs GDPP
     - Inflation vs GDPP
   - Label the groups of countries based on economic indicators such as GDPP, child mortality, and inflation.

### Running the Notebook
1. **Start Jupyter Notebook**
   - Start Jupyter Notebook:
     ```
     jupyter notebook
     ```  
2. **Open the Notebook**  
   - Open the Jupyter notebook `Kmeans_task.ipynb` to continue the analysis.  