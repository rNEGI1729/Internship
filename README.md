Project Description:

In this internship project, I worked on analyzing a comprehensive COVID-19 dataset using a combination of SQL and Python. The primary objective was to clean the raw data, extract key insights, and perform statistical analysis to understand the spread of the virus over time and across different regions. The dataset, originally in CSV format, contained records of confirmed cases, deaths, and recoveries, along with geographic and date information for various countries and provinces.

The first step in the project was data preprocessing. The CSV file was imported into a Pandas DataFrame, and I ensured that the date column was properly formatted. The dataset was then loaded into an SQLite database to allow efficient querying and analysis. As part of the data cleaning process, I checked for null values across key columns such as country, province, latitude, longitude, confirmed cases, deaths, and recoveries. If any null values were detected, they were updated with appropriate default values—empty strings for text fields and zeros for numerical fields like confirmed cases, deaths, and recoveries.

Once the data was cleaned, I performed a series of SQL queries to analyze the dataset. I started by calculating the total number of records and identifying the start and end dates of the data. Next, I broke down the data into months and years to find the average number of confirmed cases, deaths, and recoveries. Using SQL's GROUP BY functionality, I was able to extract monthly and yearly summaries, providing a clear understanding of how COVID-19 spread over time. For example, I computed the monthly averages for confirmed cases, deaths, and recoveries, helping to pinpoint specific periods where the virus had its most significant impact.

One of the key parts of the analysis involved statistical calculations. I computed variance and standard deviation for confirmed cases, deaths, and recoveries to understand the spread and fluctuation of the virus’s impact across regions and time periods. For each month, I calculated the most frequent number of confirmed cases, deaths, and recoveries to identify typical patterns in the data. These calculations provided insights into which months experienced the highest and lowest infection rates, and helped in understanding the severity of the pandemic in different phases.

The final step was to analyze how the pandemic evolved over the years 2020 and 2021. I extracted the minimum and maximum values for confirmed cases, deaths, and recoveries in each year, which showed the progression of the pandemic. Additionally, I used SQL queries to compute the total confirmed cases, deaths, and recoveries each month, offering a cumulative view of how the virus spread over time.

Outcome of the Project:

The project successfully achieved its goal of providing a detailed analysis of the COVID-19 pandemic. The dataset was cleaned, structured, and analyzed, yielding key insights into the pandemic’s timeline and geographical spread. The monthly and yearly summaries allowed for easy identification of peak infection periods and recovery rates. Variance and standard deviation calculations offered deeper insights into how the pandemic's impact varied across different regions and times.

The project demonstrated the power of combining SQL for data querying with Python for advanced statistical computations. The outcome not only provided a clear understanding of the pandemic's progression but also highlighted the importance of data analysis in public health decision-making. 