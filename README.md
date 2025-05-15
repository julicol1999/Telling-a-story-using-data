# Telling a story using data

## Project Description

The project explores the viability of opening a small, robot-staffed café in Los Angeles. While the concept is innovative and attention-grabbing, it also involves significant startup costs. To attract potential investors, the team needs to demonstrate that the café can remain profitable even after the novelty of robotic waitstaff wears off.

A market research study is carried out using publicly available data on restaurants in Los Angeles. The goal is to evaluate the competitive landscape, identify potential customer segments, and provide insights into factors that contribute to long-term restaurant success in the area.

---

## Objectives

- Clean and prepare the restaurant data for analysis.
- Analyze establishment types, chain affiliation, and seating capacity.
- Explore location-based trends and seat distribution.
- Provide strategic recommendations based on the findings.

---

## Dataset

- **File path:** `/datasets/rest_data_us_upd.csv`
- **Format:** CSV
- **Description:** Contains information about restaurants in Los Angeles, including name, address, type, chain status, and number of seats.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Regular Expressions (`re`)


## Sample Code Snippet

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import re

# Load dataset
df = pd.read_csv('/datasets/rest_data_us_upd.csv')

# Preview data
print(df.head())

