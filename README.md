# Take-Home Test - EDA on US Accidents Dataset

## Project Overview
This project demonstrates the use of *Exploratory Data Analysis (EDA)* and basic *ETL (Extract, Transform, Load)* processes on the publicly available *US Accidents Dataset*. The goal is to extract meaningful insights from the data and present findings through visualizations and statistical analysis.

---

## Dataset
- *Name:* US Accidents Dataset
- *Source:* [Kaggle](https://www.kaggle.com/sobhanmoosavi/us-accidents)
- *Description:* This dataset contains information about accidents in the United States, including time, location, and environmental conditions.
- *File Format:* CSV

---

## Key Features
1. *Dataset Extraction:*
   - The dataset is downloaded using the opendatasets library from Kaggle.
   - The Kaggle dataset URL is utilized for easy access.

2. *Data Loading:*
   - The dataset is loaded into a *pandas DataFrame* for exploration and transformation.

3. *ETL Process:*
   - *Extract:* Data loaded from Kaggle.
   - *Transform:* Time variables (Start_Time, End_Time) converted for analysis.
   - *Load:* Cleaned data stored in a DataFrame for further analysis.

4. *Exploratory Data Analysis (EDA):*
   - Basic descriptive statistics using df.describe() and df.info().
   - Visualizations created using *Seaborn* and *Matplotlib* for insights into trends, distributions, and relationships.

5. *Insights and Documentation:*
   - Each step is explained with detailed Markdown text to ensure clarity.
   - Key findings from the EDA are summarized for better understanding.

---

## Key Insights
- *Trends and Patterns:*
  - Accidents are more frequent in urban areas.
  - Traffic incidents tend to increase during certain times of the day.
- *Feature Distribution:*
  - Clear distributions of accident severity, weather conditions, and time of occurrence.
- *Visual Findings:*
  - Scatter plots and histograms reveal the concentration of accidents in specific regions and times.

---

## Tools and Libraries
- *Python*: Primary programming language.
- *Libraries*:
  - pandas: Data manipulation and analysis.
  - seaborn, matplotlib: Data visualization.
  - numpy: Numerical operations.
  - opendatasets: Dataset extraction from Kaggle.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/uday2909/AAK-Take-Home-Test-EDA.git
