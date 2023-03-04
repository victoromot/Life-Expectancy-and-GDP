# Life Expectancy and GDP
This is a Data Visualization Project using python libraries Matplotlib and Seaborn

In this project, we will visualize data on GDP and life expectancy from the World Health Organization and the World Bank to try and identify the relationship between the GDP and life expectancy of six countries.

The dataset is saved as a csv file named 'all_data.csv'. The data includes:

    Country: the name of the nation
    Year: the year the data was taken
    life expectancy at birth (years): the amount of years a person can expect to live in years
    GDP: the gross domestic product of the nation

The data used in this analysis is a clean dataset and didn't require preparations; however, I inspected it to check for missing observations, which shows no missing data. After examination, I visualized the data using phyton libraries matplotlib and seaborn. I used line graphs and scatter plots to visualize the trends from the year 2000 to the year 2015 and the relationships between two quantitative variables(GDP and life expectancy) over this period, respectively. The visualization was followed by finding the quantitative variables' mean by country and year.

Generally, between the years 2000 and 2015, there was an increase in the life expectancy of people and GDP in the six countries considered. The average life expectancy of the six countries increased from 70.8 in 2000 to 75.7 in 2015. The life expectancy in Zimbabwe could be viewed as an outlier, as shown in the histogram and boxplot. Zimbabwe had the highest increase from about 45 years to over 60 years, indicating an approximately 25% increase in the number of years Zimbabweans expect to live. Besides having the lowest life expectancy, Zimbabwe has the lowest GDP over the years considered in this analysis.

The USA remained the number one country GDP-wise over the 15 years. However, Germany was behind the USA until China overtook it in 2007 and remained the second economy behind the US. The scatterplots show a positive relationship between GDP and life expectancy for all nations considered. The calculation of a correlation of 0.34 further solidifies this relationship.