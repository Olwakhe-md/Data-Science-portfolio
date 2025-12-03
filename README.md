Overview

This week focuses on building a solid foundation in Python and Pandas for working with biological datasets.
The goal was to load, inspect, clean, transform, and analyze a simple lab sample dataset.

📚 Tasks Completed
1. Dataset Loading

Loaded CSV data using pandas.read_csv()

Inspected structure with .head(), .info(), and .describe()

2. Filtering & Basic Analysis

Isolated acidic samples (pH < 6)

Counted species using value_counts()

Summarized data by sample type and pH category

3. Feature Engineering

Converted weight from mg → grams
(weight_grams = weight_mg / 1000)

Created pH categories: acidic, neutral, basic

4. Grouping & Aggregation

Calculated mean weight per species using groupby()

Created cross-tab and pivot tables for visualization

5. Visualization

Histogram of pH distribution

Grouped bar chart comparing pH categories across sample types

6. Outputs Saved

Cleaned dataset

Species counts table

Mean weight table

Visualization image

🧪 Key Insights

Stem samples had the highest number of acidic pH values.

Arabidopsis thaliana had the highest mean sample weight (290.61 mg).

Solanum lycopersicum had the lowest mean sample weight (211.53 mg).

pH distribution shows meaningful variation across sample types.

🧠 Skills Gained

Python environment basics

Data loading & inspection

Filtering, grouping, and aggregating

Feature creation

Basic visualizations

Saving results

Git/GitHub workflow
