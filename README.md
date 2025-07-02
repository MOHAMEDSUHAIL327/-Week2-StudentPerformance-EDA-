Import Libraries – Load pandas, matplotlib, and seaborn for data handling and visualization.
Load Dataset – Upload and read the country_wise_latest.csv file into a DataFrame.
Preview Data – Display the first 5 rows to understand dataset structure.
Check Summary Status – Use .describe() to view basic statistics of the dataset.
Check Missing Values – Identify null values in each column using .isnull().sum().
Check Duplicates – Find duplicate rows with .duplicated().sum().
Count Unique Countries – Count how many unique countries are present using .nunique().
Top 10 Affected Countries – Sort by confirmed cases and show top 10 countries.
Visualize Deaths – Create a bar chart for top 10 countries with highest deaths.
Pie Chart Recovered vs Deaths – Plot a pie chart comparing global recovered and death counts.
