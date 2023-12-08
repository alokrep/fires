# Wild Fires and Impact of Demographics/Geography on their destruction
The study strategically considers the impact of key demographic and geographic variables, including county area, population density, and income levels. Employing a robust methodology that integrates advanced machine learning classification models and rigorous statistical tests, our findings consistently support the null hypothesis, suggesting that reported fire sizes do not exhibit significant differences among study states after accounting for demographic and geographic factors.
# Steps to run the code
- Import the `src/*.ipynb` file into Google Colab
- Import/Upload the `src/eol/*` folder into your Google Drive and replace the path in the above notebook file.
`filepath = '/content/drive/MyDrive/Neal/DataScience/fires'`
- Run the notebook on Colab, this might require providing permission for Colab to access your Google Drive folder

# Methodology, Models and Datasets used
- Study states included California, Oregon and Washington
- Spatial wildfire occurance data for the US, 1992-2020 (https://www.fs.usda.gov/rds/archive/catalog/RDS-2013-0009.6)
- Convertion to CSV and cleanup of above dataset for our purpose. 
- Demographic data from Corgis(https://corgis-edu.github.io/corgis/datasets/csv/county_demographics/county_demographics.csv) at a county level
- KNN(K-Nearest Neighbors), XGBoost and Random forest classifiers for fire size classification
- Linear and random forest regressors for latitude and longitude.
- Normalizing variables and evaluationing metrics like AIC, LLP, R2, MAE and F-static.
- Comparing tradeoffs and priorties for model complexity and error
- Overlay of maps with fire size

# Goals
- Understand application of various models across datasets
- Reinforce learning from prior NLP projects
- Contribute to the knowledge on wildfires, facilitating more informed management strategies.

# Authors
- Nilai(Neal) Damireddy
- Clayton Greenberg

# Journal Publish
- JSR.org(https://jsr.org): Submission ID: 2411
