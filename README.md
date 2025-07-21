Project Overview:
To analyze and visualize Covid-19 data across different countries and time periods, with the aim of identifying trends, patterns, and key insights related to the spread, recovery, and mortality rates of the virus.

Problem Statement:
The business wanted to understand its Which Country has maximum Total cases, Deaths, Recovered & active cases, what is the trend of Confirmed Deaths Recovered Active cases, 
find 20 most effected countries, countries that are badly affected by corona,Visualize Confirmed,  Active,  Recovered , Deaths Cases(entire statistics ) of a particular country to improve inventory decisions.

Dataset Information:
-CSV files containing daily records of confirmed cases, deaths, and recoveries per country/region.
-It includes Country/Region, Continent, Population, TotalCases, NewCases, TotalDeaths, NewDeaths, TotalRecovered, NewRecovered, ActiveCases, SeriousCritical, WHO Region

Goal:
1. Which Country has maximum Total cases, Deaths, Recovered & active cases.
2. what is the trend of Confirmed Deaths Recovered Active cases.
3. find 20 most effected countries.
4. 20 countries that are badly affected by corona.
5. Pie Chart Representation of stats of worst affected countries.

1] Which Country has maximum Total cases, Deaths, Recovered & active cases.
<img width="700" height="360" alt="newplot (1)" src="https://github.com/user-attachments/assets/01190c2d-4d61-48c8-87fa-c8c1b97ddbe4" />.
<img width="700" height="360" alt="newplot (2)" src="https://github.com/user-attachments/assets/8fa4eedf-7dfe-4413-8b75-d9d392f8da87" />.
<img width="700" height="360" alt="newplot (3)" src="https://github.com/user-attachments/assets/0f3753ba-c99f-4724-a71d-3803a46b3246" />.
<img width="700" height="360" alt="newplot (4)" src="https://github.com/user-attachments/assets/1a166768-5601-4a1f-a8af-c46f59688be8" />.

- since from the data USA has most number of total cases,**
- USA has most number of deaths rate.
- USA has most number of recovered cases.
- USA has most number of ActiveCases.

2] what is the trend of Confirmed Deaths Recovered Active cases.
<img width="700" height="360" alt="newplot (5)" src="https://github.com/user-attachments/assets/c841d4cf-7faf-4d6a-9ce3-3f861687e75e" />

Overall Trend: The number of confirmed deaths is steadily increasing over time.

Growth Pattern:The growth starts very slowly in early 2020 (February to March).From around April 2020 onward, the number of deaths rises more sharply.The curve continues to grow at a nearly linear to slightly exponential rate through to July 2020.

Magnitude: Compared to the other variables (like Confirmed or Recovered), the total number of deaths is significantly lower, as seen by its relatively flatter curve.

3] Find 20 most effected countries.
<img width="700" height="360" alt="newplot (6)" src="https://github.com/user-attachments/assets/909d751b-90d9-42ce-bb9f-01eb202a33f4" />.

Mexico and Bangladesh have highest population-to-test ratios, indicating poor testing. USA, Russia show strong testing coverage. Others vary moderately.

4] 20 countries that are badly affected by corona.
<img width="700" height="360" alt="newplot (7)" src="https://github.com/user-attachments/assets/f71636f5-9b69-4228-9198-22fbbcaaa051" />.

USA and Brazil lead in total COVID-19 cases. India follows. Most countries show fewer serious, active, or critical cases comparatively.

5] Pie Chart Representation of stats of worst affected countries.
<img width="700" height="360" alt="newplot (8)" src="https://github.com/user-attachments/assets/985a073e-48c6-4838-855b-2715a88cc45f" />.
<img width="700" height="360" alt="newplot (9)" src="https://github.com/user-attachments/assets/d7c0ce28-dcfa-4844-b4ab-e1216b319d50" />.
<img width="700" height="360" alt="newplot (10)" src="https://github.com/user-attachments/assets/ac7bbf13-cc55-4cba-b703-98380b1baea8" />.
<img width="700" height="360" alt="newplot (11)" src="https://github.com/user-attachments/assets/01856a56-be32-4f37-b24f-2b85eadbd0df" />.

The USA consistently leads in total cases (33.9%), active cases (50.2%), recoveries (28.2%), and deaths (31%). Brazil and India follow across all categories. Mexico and Russia also rank high in deaths and total cases. Recovery rates vary, while active case proportions remain highest in the USA, showing ongoing infection spread.

Technologies and Libraries Used:
I used Python throughout the project. To merge the monthly files, I used the os library, then performed all the data cleaning and transformations with pandas. For calculating totals and other stats, I used NumPy. And to present insights visually, I built charts using matplotlib and seaborn.
While working on the project, I faced a few challenges, like merging large files efficiently and visualizing some complex patterns. So, I referred to documentation, used Google, and even took some help from ChatGPT to understand certain techniques better. It helped me speed up my learning and apply best practices.

Conclusion:
As a result of the analysis, I found the USA leading in total, active, recovered, and death cases, indicating the highest overall COVID-19 burden. Brazil and India follow across all categories. Testing is more extensive in the USA and Russia, while countries like Mexico and Bangladesh show poor testing ratios. Recoveries are high in the USA, Brazil, and India, but active cases remain significant. Treemaps further confirm the USA’s dominance in both active and recovered cases, reflecting both high infection rates and healthcare response capacity.













