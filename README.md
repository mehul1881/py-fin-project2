import pandas as pd

# Load the data
url = "your_dataset_link.csv"
data = pd.read_csv(url)

# Check the structure of the data
print(data.head())
