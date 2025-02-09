# Fraud Detection

## Overview
This project focuses on detecting fraudulent activities using data analysis. The repository includes a Power BI report (`fraud detection.pbix`) that visualizes key insights and trends in fraud detection.

## Features
- **Excel Data Processing:** Load, clean, and store Excel data using Jupyter Notebook.
- **DataBase:** Store data on MySQL.
- **Database Integration:** Fetch data from MySQL using ODBC server.
- **Data Visualization:** Interactive dashboards in Power BI to analyze fraud patterns.
- **Reports & Insights:** Summary of key fraud trends and anomalies.

## Installing Jupyter Notebook
To install Jupyter Notebook, follow these steps:
1. Install Python (if not already installed) from [Python Official Website](https://www.python.org/downloads/).
2. Install Jupyter Notebook using pip:
   ```sh
   pip install notebook
   ```
3. Launch Jupyter Notebook:
   ```sh
   jupyter notebook

## Installation
To run the Power BI report, follow these steps:
1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/)
2. Download the `fraud detection.pbix` file from this repository.
3. Open the file in Power BI Desktop.

## Database Connection
To fetch data from MySQL using ODBC:
1. Install MySQL ODBC driver from [MySQL official website](https://dev.mysql.com/downloads/connector/odbc/).
2. Configure an ODBC Data Source for your MySQL database.
3. In Power BI, go to **Get Data** > **ODBC** and select your configured data source.
4. Load the data and refresh as needed.

## Loading and Cleaning Excel Data in Jupyter Notebook, then Storing in MySQL
process 
1. Install required libraries:
   ```python
   !pip install pandas , numpy
   ```
2. Load the Excel file in Jupyter Notebook:
   ```python
   import pandas as pd
   df = pd.read_excel('data.xlsx')
   ```
3. Perform data cleaning:
   ```python
   df.isnull().sum()        # Checking missing values
   df.dropna(inplace=True)  # Remove missing values
   df = df.drop_duplicates()  # Remove duplicate rows
   ```

4. Convert to csv file:
   ```python
   df.to_csv("Data.csv")
5. Connect to MySQL database:
  - Store data(csv file) on MySQL

6. Fetch data from MySQL:
   - In Power BI, go to **Get Data** > **ODBC** and select your configured data source.


## Usage
- Open `fraud detection.pbix` in Power BI Desktop.
- Navigate through the interactive reports to explore fraud patterns.
- Customize filters to analyze specific segments of data.

## Key Insights
## 📸 Preview  




![1](https://github.com/user-attachments/assets/3e02017d-c8df-427e-9da1-79a0b2ee99dc)






![2](https://github.com/user-attachments/assets/04e048f5-8d7a-43e3-94ef-a6d223f70163)




![3](https://github.com/user-attachments/assets/02dc4b61-1d11-434c-914c-adac019a10f6)








https://github.com/user-attachments/assets/115e0cd5-a618-415b-b4a4-70fd9697af1e



## Insights
- Out of the total merchants, ~ 53% of fraud cases happened with males, and 47% with females.
- Fraud cases were higher in 2019 compared to the previous year.
- More frauds happened with audiological scientists compared to other jobs.
- Credit card transactions were highest among females compared to males.
- The highest number of fraud cases in North America were found in the state of TX.


## How to Access Insights

1. Download the dataset from the `data/` directory.
2. Open the Power BI file (`data.pbix`) or refer to visualizations provided in the `/visuals` folder.
3. Use filters and slicers to explore specific trends.



## Feedback and Contributions

We welcome contributions! If you have insights, improvements, or suggestions, please open an issue or submit a pull request.
- 🌐 [GitHub Profile](https://github.com/ShubhamKumar0786https://github.com/ShubhamKumar0786)  
- 📧 Email:shubhamkashyap9501@gmail.com
- LinkedIn: [Linkedin_link](https://www.linkedin.com/in/shubham0786/)
