# Heart Disease Predictor
Machine Learning model to predict heart disease.

## Description
This project uses machine learning to predict the presence of heart disease based on various medical features, such as chest pain type, maximum heart rate achieved, resting blood pressure, and more.  
The goal is to improve my skills in data manipulation, data analysis, machine learning development, and the correct interpretation of ML results.

## Stack
<p justify-content="center" display="flex" align-items="center">
  <a href="https://www.python.org" target="_blank">
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  </a>

   <a href="https://scikit-learn.org/" target="_blank">
    <img alt="Scikit" src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
  </a>
  
   <a href="https://numpy.org/" target="_blank">
    <img alt="Numpy" src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white">
  </a>

   <a href="https://pandas.pydata.org/" target="_blank">
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white">
  </a>

   <a href="https://matplotlib.org/" target="_blank">
    <img alt="MatPlotLib" src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white">
  </a>
  </p>
  
## Exploratory Data Analysis

<p>
  I used <strong>Pandas</strong> to explore and understand the dataset, and <strong>Matplotlib</strong> along with <strong>Seaborn</strong> for visualizations.
</p>

<ul>
  <li>First of all, I checked for null and duplicated values — luckily, there were none.</li>
  <li>Next, I categorized the features into numerical and categorical types.</li>
  <li>Then came the visualizations: I used histograms for numerical data and bar charts for categorical variables.</li>
  <li>To detect outliers, I used box plots. I found a few, but decided to keep them, considering that in medical data, anomalies can still represent real and important cases.</li>
  <li>Finally, I created a correlation heatmap to understand the relationships between all features.</li>
</ul>

## Data Prepare for ML

<p>  
  Of course, I had to prepare the dataset to be suitable for the different <strong>machine learning</strong> models I planned to use. Since the dataset is relatively small (only 297 rows), I decided to split it into training and testing sets, without using a separate validation set. In this case, I believe that <strong>cross-validation</strong> is a better approach to make the most out of the limited data.
</p>

<p>
  To split the data, I used the <code>numpy.split()</code> function, dividing the dataset into 80% for training and the remaining 20% for testing. While libraries like Scikit-learn provide more specialized tools for this task, I chose NumPy for its simplicity and to reinforce my understanding of manual data manipulation.
</p>














