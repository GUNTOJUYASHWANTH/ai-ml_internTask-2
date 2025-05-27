Titanic Dataset: Data Cleaning & Preprocessing
This project is a comprehensive walkthrough of cleaning and preprocessing the Titanic dataset using Python. It involves statistical analysis, visualization, handling missing values, encoding, feature scaling, and detecting/removing outliers — preparing the data for machine learning tasks.

 Objective
The goal is to demonstrate step-by-step preprocessing for real-world structured data, focusing on making the Titanic dataset suitable for ML models.

 Tools & Libraries
Python (Jupyter Notebook)

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📊 Dataset Overview
The dataset contains information about passengers on the Titanic, such as:
Personal info (Name, Sex, Age)
Travel info (Ticket, Fare, Embarked)
Survival status (Survived)

 Workflow Summary
1. Data Loading & Exploration
Loaded Titanic-Dataset.csv using Pandas
Performed summary statistics: mean, median, mode, std dev, variance, skewness, kurtosis
Checked for missing values
![Screenshot 2025-05-27 115817](https://github.com/user-attachments/assets/e65e7ed8-c602-4aca-9a71-796ece748861)
![Screenshot 2025-05-27 115852](https://github.com/user-attachments/assets/781f87f4-faf1-4c65-9051-a95bef25817c)
![Screenshot 2025-05-27 115915](https://github.com/user-attachments/assets/993b0be7-2db8-440f-b27d-62aa2b170a65)

2. Data Visualization
Plotted histograms and boxplots for all numeric features

Used Seaborn & Matplotlib to visually assess distributions and outliers

3. Missing Value Treatment
Replaced missing Age values with the mean

Replaced missing Embarked entries with the mode

4. Encoding Categorical Features
Applied one-hot encoding to Sex and Embarked using pd.get_dummies()

5. Feature Scaling
Used StandardScaler to normalize Age and Fare

6. Outlier Detection
Visualized outliers using boxplots post-scaling

🖼️ Visual Outputs
Histograms & Boxplots: All numeric features
![Screenshot 2025-05-27 115940](https://github.com/user-attachments/assets/61b38258-d9c4-4344-bc91-ea8a9ab39fec)
![Screenshot 2025-05-27 120051](https://github.com/user-attachments/assets/ca7cf9ab-2f81-4ff9-8a0d-895335799c59)
![Screenshot 2025-05-27 120116](https://github.com/user-attachments/assets/1869b54b-7f0d-4827-8233-11f1dadbc85a)
![Screenshot 2025-05-27 120131](https://github.com/user-attachments/assets/e4f7b3b6-97bb-499e-9d25-f065143e72e4)
![Screenshot 2025-05-27 120148](https://github.com/user-attachments/assets/a40a929a-31e5-400b-b721-64d941b73e8f)

Correlation matrix:
![Screenshot 2025-05-27 120258](https://github.com/user-attachments/assets/1e93ee18-647e-4346-87cd-03cdea04ce58)


Pair plots for multivariate relationships:
![Screenshot 2025-05-27 120240](https://github.com/user-attachments/assets/85cea8e6-0814-432f-8f40-fe539b42ddc2)

Identify patterns, trends, or anomalies in the data.
![Screenshot 2025-05-27 120322](https://github.com/user-attachments/assets/ef259ba8-ec3a-4ed3-8d7d-e6d29c795292)
![Screenshot 2025-05-27 120332](https://github.com/user-attachments/assets/7ad5ed70-8b97-4357-b3b6-f5f1df537096)
![Screenshot 2025-05-27 120356](https://github.com/user-attachments/assets/739dbe0f-4fbd-47c8-ab30-eea314a0624c)
![Screenshot 2025-05-27 120442](https://github.com/user-attachments/assets/bc409e76-f4a0-4e78-922a-a3db117683c6)
![Screenshot 2025-05-27 120456](https://github.com/user-attachments/assets/85af103e-9379-4680-aec4-9f394d62b79e)

 Missing values heatmap:
 ![Screenshot 2025-05-27 120518](https://github.com/user-attachments/assets/23c2f5d6-eca9-4417-bcf1-ae6cced85095)




