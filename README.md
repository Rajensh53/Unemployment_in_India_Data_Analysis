📊 Unemployment in India - Data Analysis & Visualization
This project presents a comprehensive analysis of unemployment trends in India using various data visualization tools. The dataset includes estimated unemployment rates, employed numbers, and labour participation rates across different Indian regions and cities from January 2020 to November 2020.

📁 Dataset Description
The project uses a dataset named:

Unemployment_Rate_upto_11_2020.csv

Key Features:
City: Indian State or Union Territory

Date: Date of the record

Estimated_Unemployment_Rate: Percentage of estimated unemployed individuals

Estimated_Employed: Estimated number of employed individuals

Estimated_Labour_Partiipation_Rate: Labour participation percentage

Region: The broader Indian region (North, South, East, West, Northeast)

Langitude, Latitude: Geographic coordinates

🛠️ Technologies Used
Python 🐍

Libraries:

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Static visualizations

Plotly – Interactive visualizations

📈 Exploratory Data Analysis (EDA)
Cleaned and renamed dataset columns for clarity

Converted Date column to datetime format

Removed unnecessary columns (Frequency)

Checked and confirmed absence of missing and duplicate data

📊 Visualizations
📌 Static Plots (Seaborn, Matplotlib):
Heatmap of correlation among numerical variables

Histogram of Estimated_Employed and Estimated_Unemployment_Rate by Region

📌 Interactive Plots (Plotly):
City-wise unemployment rate histogram

Region-wise unemployment rate histogram

Sunburst chart showing hierarchical unemployment data from Region → City → Rate

📍 Insights
North India has the most data entries, followed by South and West.

Unemployment spikes observed in April–May 2020, likely due to COVID-19 lockdown.

Some cities show significantly higher unemployment rates than others.
