import pandas as pd

# Load CSV file into a DataFrame
df = pd.read_csv("data.csv")

# Display first 5 rows
print

import json

# Open and load JSON file
with open("data.json", "r") as file:
    data = json.load(file)

print(data)

import pandas as pd

# Load Excel file
df = pd.read_excel("data.xlsx")

print(df.head())
