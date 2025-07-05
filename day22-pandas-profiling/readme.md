Video Link:https://www.youtube.com/watch?v=E69Lg2ZgOxg


new code for profiling

pip install ydata-profiling

import pandas as pd
from ydata_profiling import ProfileReport

# Read the data from a csv file 
df = pd.read_csv("data.csv")

# Generate the data profiling report 
report = ProfileReport(df, title='My Data')
report.to_file("my_report.html")
