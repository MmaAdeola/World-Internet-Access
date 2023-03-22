# World-Internet-Access
A DataCamp Competition to discover how much of the world has access to the internet.
A fictitious background for a policy consulting firm was created.
The following questions were answered:
1. What are the top 5 countries with the highest internet use (by population share)?
2. How many people had internet access in those countries in 2019?
3. What are the top 5 countries with the highest internet use for each of the following regions: 'Middle East & North Africa', 'Latin America & Caribbean', 'East Asia &    Pacific', 'South Asia', 'North America', 'Europe & Central Asia'?
4. Create a visualization for those five regions' internet usage over time.
5. What are the 5 countries with the most internet users?
6. What is the correlation between internet usage (population share) and broadband subscriptions for 2019?

Three datasets were made availbale. Link to datasets: ([source](https://ourworldindata.org/internet))
💾 The data

- internet:
"Entity" - The name of the country, region, or group.
"Code" - Unique id for the country (null for other entities).
"Year" - Year from 1990 to 2019.
"Internet_usage" - The share of the entity's population who have used the internet in the last three months.

- people:
"Entity" - The name of the country, region, or group.
"Code" - Unique id for the country (null for other entities).
"Year" - Year from 1990 to 2020.
"Users" - The number of people who have used the internet in the last three months for that country, region, or group.

- broadband:
"Entity" - The name of the country, region, or group.
"Code" - Unique id for the country (null for other entities).
"Year" - Year from 1998 to 2020.
"Broadband_Subscriptions" - The number of fixed subscriptions to high-speed internet at downstream speeds >= 256 kbit/s for that country, region, or group.

Acknowledgments: Max Roser, Hannah Ritchie, and Esteban Ortiz-Ospina (2015) - "Internet." OurWorldInData.org.


## Summary of Findings
- The top five countries with the most internet usage were Bahrain, Qatar, kuwait, United Arab Emirates and Denmark.
- Of the five top countries, United Arab Emirates had the most number of persons with internet access in 2019.
- Internet usage in all the regions has increased steadily over the years. The exception however, is in the African regions, while there has been steady increase as well, it is not at the same rate as other regions. Africa Eastern and Southern regions have the lowest level of increase in the Africa regions.
- China is the country with the most number of internet users in 2019.
- The correlation coefficient between internet usage and broadband subscriptions is 0.56, which is an indication of a moderate positive relationship. One would think that when internet usage increases, then there would be more broadband subscriptions.
