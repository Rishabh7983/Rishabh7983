- import pandas as pd

# Load the dataset
file_path = '/Assignment - Junior Data Analyst.csv'
data = pd.read_csv(file_path)

# Display basic information and the first few rows of the dataset
data_info = data.info()
data_head = data.head()

data_info, data_head
