# 🤖 Robot Café Market Analysis - Los Angeles

## 📍 Project Description

You’ve decided to open a small café in Los Angeles, fully staffed by robots. The idea is promising but costly, so you and your partners are looking to attract investors. To do so, you need to demonstrate that your business can remain successful even after the initial hype around robotic waitstaff fades away.

As a data analysis expert, you've been tasked with preparing a **market research study** using open data on restaurants in Los Angeles.

---

## 📊 Objectives

- Clean and prepare the restaurant data for analysis.
- Analyze establishment types, chain affiliation, and seating capacity.
- Explore location-based trends and seat distribution.
- Provide strategic recommendations based on the findings.

---

## 📁 Dataset

- **File path:** `/datasets/rest_data_us_upd.csv`
- **Format:** CSV
- **Description:** Contains information about restaurants in Los Angeles, including name, address, type, chain status, and number of seats.

---

## 🛠 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Regular Expressions (`re`)


## 📈 Sample Code Snippet

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import re

# Load dataset
df = pd.read_csv('/datasets/rest_data_us_upd.csv')

# Preview data
print(df.head())

