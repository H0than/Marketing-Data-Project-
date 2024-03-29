## Marketing Data Project 

# Project Overview:
This project focuses on automating the weekly marketing data using Python.
The objective is to streamline the process of handling marketing data and perform various data manipulation tasks efficiently.

# Tasks Completed:

1. Reading CSV File
The provided CSV file containing weekly marketing data was successfully read into a Pandas DataFrame.
2. Multiple column names were renamed to enhance clarity and consistency:
3. Calculation of New Metrics:
Several new metrics were calculated based on the existing data;
Click-Through Rate (CTR)
Cost Per Acquisition (CPA)
Cost Per Click (CPC)
Return On Advertising Spend (ROAS)
Cost Per Mille (CPM)
5. Conversion and Formatting:
Currency formatting was applied to 'Spend', 'Revenue', 'CPA', 'CPC', and 'CPM' columns to represent monetary values in a standardized format.
6. Creation of Campaign Name Column:
A new column named 'Campaign Name' was created by concatenating 'Platform' and 'Campaign Type' columns.
This provides a comprehensive view of the marketing campaigns.
8. Reordering Columns:
The columns were reordered to ensure that the 'Campaign Name' column is positioned after the 'Platform' column for improved readability and organization.
9. Saving Modified DataFrame to CSV:
The modified DataFrame was saved to a new CSV file to ensure that the changes are retained for future analysis and reference.


The automation of weekly marketing data using Python has significantly improved efficiency and accuracy in handling marketing data. 
By automating tasks such as column renaming, metric calculation, and data saving, the project has streamlined the process and reduced manual effort.

# Project Files:

Marketing Data Project.ipynb: This Jupyter Notebook contains the Python code used to automate the marketing data.
Modified_Marketing_Campaign_Data_py.csv: This CSV file contains the modified marketing data after performing various data manipulation tasks.
marketing_campaign_data_py.csv: This CSV file contains the marketing data before data cleaning. 
