import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import requests

# Data (you can modify these values based on your actual data)
data = [5, 2, 5, 3, 4, 1]  # Example values

# Age groups corresponding to the bars
age_groups = ['25-44', 'Under 18', '45-64', '18-24', '65-84', '85 or older']

# Plotting the histogram
plt.bar(age_groups, data)

# Adding titles and labels
plt.title('')
plt.xlabel('')
plt.ylabel('')

# Show the plot
plt.show()


