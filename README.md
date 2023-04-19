<h1>The Impact of Education on Women's Fertility Rates (Globally)</h1>

<h2>ℹ️ Information About the Study</h2>
<h3>A Brief Introduction</h3>

As a <i>staunch</i> advocate of education, particularly for women, I have been contemplating the impact of education on the birth rate of women worldwide. The latest news reports indicate that Japan is grappling with a dire fertility crisis, with its birth rate failing to keep pace with the death rate. This has coincided with an increase in women's education. This has resulted in significant economic, social, and governmental challenges. I can't help but wonder if the growing prevalence of women's education is a contributing factor to this crisis. This study researches global patterns to see if there is a correlation among women's fertility rates and their average education level.

<h3>Question to Study</h3>

- Is there a correlation between higher levels of education among women and lower fertility rates?

<h3>Dataset and Project Information</h3>

Original Dataset Link: <a href = "https://www.kaggle.com/datasets/valchovalev/womenseducationalattainmentvsfertility?resource=download">Women's Educational Attainment vs Fertility</a>

Software/Tools Being Used:
- Python
  - Plotly
  - PYODBC
- <a>womens-educational-attainment-vs-fertility.csv</a>

<i><b>* Since there is a limited amount of data available, I will not be creating a dashboard for this project. Instead, I will be analyzing the data using visualizations created with the Plotly Python library. *</b></i>

<h2>🔍 The Study (Full Process)</h2>

<b>PowerBI Dashboard:</b> <a href="https://app.powerbi.com/view?r=eyJrIjoiOWQyOTg5ZDItOTk1OC00NmMyLTkwM2UtNTYzNWNkYTI0YzIwIiwidCI6ImU0YTdiMmYwLTRkM2QtNDI0OC05YTdiLWEyNjQ4ZTIzN2MxNSIsImMiOjF9">Fertility Rate vs. Education Level</a>

<h3>Obtaining and Cleaning the Data</h3>

To start the data cleaning process, I downloaded the Women's Education vs Fertility dataset from Kaggle. Using pandas in Python, I initiated the cleaning process by removing all countries that did not exist in 2010. To accomplish this, I utilized AI to create a list of present-day countries and cross-checked it with the CSV dataset using pandas. This ensured that only relevant countries were included in the analysis.

After filtering out the unnecessary countries, I further cleaned the data by refining the year column to only include years where both the fertility rate and education levels were tracked. This ensured that the resulting visualization tools were more informative and precise. Additionally, I rounded and grouped the data based on year and country to improve the data's readability and clarity.

Finally, I exported the cleaned data back into the CSV file and uploaded it into PowerBI to create visually appealing, interactive, and informative visualizations.
  
<h3>Creating Visualizations Using Power</h3>

After cleaning the data, I proceeded to upload it into PowerBI. To ensure a clear and concise presentation, I opted for a simple and minimalist layout, which included three cards displaying the fertility rate, primary education level in years, and population of the world/selected countries.

In addition to the cards, I created two orthographic maps to visualize the fertility rates and education levels across the globe. These maps provide a comprehensive view of the data, making it easier to identify trends and patterns (see figure 1 below).

To further explore the correlation between fertility rates and education levels, I created a scatter plot. The scatter plot showcased the relationship between these two variables with bubble sizes representing the country's population. Additionally, I added two buttons that allow the user to switch between a scatter plot for a global view and a line graph to analyze a country's rate in more depth.

To enable the user to research the data more in-depth, I also created two slicers that allow for the selection of a specific year and country (or all countries) to refine the data. These slicers make it easier to analyze trends and patterns, providing a more interactive and user-friendly experience.

Overall, the data visualization in PowerBI offers a clear and concise presentation of the information, allowing for a more comprehensive understanding of the data's relationship between fertility rates, education levels, and population.

![PowerBI](https://user-images.githubusercontent.com/130507070/233139718-7af1d270-51d3-4f02-9ff1-6ed82e7a014e.png)
Figure 1: An example of Australia.

<h3>Intepreting the Data and Answering Proposed Questions</h3>

<b>Question: Is there a correlation between higher levels of education among women and lower fertility rates?</b>

In essence, there is a compelling correlation between lower fertility rates and higher education levels. Upon examining the world line chart, a discernible upward trend in education emerges around the 1960s, coinciding with a corresponding, steady decline in fertility rates. This pattern is apparent throughout the rest of the chart: the faster and higher education levels rise, the lower fertility rates become.

This phenomenon is further supported by the scatter plot, which reveals that in 1950, the vast majority of countries had high fertility rates (~55% had above a fertility rate of 5) and lower education levels, but by 2010, most countries had lower fertility rates (75% had below a fertility rate of 5) and higher education levels. Visualizing these trends in the accompanying photos should help users better grasp this relationship.

In conclusion, the data shows a clear and significant relationship between fertility rates and education levels in women. In 1950, the average fertility rate was 5.39 and the average primary education level was only 2.77 years. However, by 2010, there was a remarkable 59.5% drop in the average fertility rate, at 2.92 children per women, and a 104.2% rise in education levels, with an average of 8.8 years of primary education. This rapid change took place over just 70 years. Based on the formula (Average drop per educational year = (5.39 - 2.92) / (8.8 - 2.77)), we can estimate that for every additional year of education, the fertility rate dropped by 0.41. This stark constrast can especially be seen with Australia in figure 1.

<b>What can we do with this data?</b>

According to the <a href="https://www.un.org/esa/sustdev/natlinfo/indicators/methodology_sheets/demographics/total_fertility_rate.pdf">United Nations</a>, the replacement level is 2.1 children per women. The data above shows that as a of 2010, the fertility rate was 2.92 children, which is 0.82 above the replacement level, which is "the level of fertility at which a population exactly replaces itself from one generation to the next" (<a href="https://pubmed.ncbi.nlm.nih.gov/7834459/">NIH</a>). This trend is good for the population, as overpopulation can cause ecological degradation, increased conflicts, and increase the risk of disasters and pandemics and their affects (<a href="https://www.populationmedia.org/blog/overpopulation-cause-and-effect">PMC</a>).

So, as the data shows above, we need to continue to invest in female education. Female education has shown to be the most effective birth control. Unfortunantly, 130 million girls are currently out of school and 15 million girls of primary school age will never learn to read or write. In fact, female education increases the rate of healthier children, female workforce participation, and delays the childbearing age, leading to parents who are in more comfortable financial position and able to care for their child without government intervention ((<a href="https://www.populationmedia.org/blog/overpopulation-cause-and-effect">PMC</a>).

<h2>💤 Conclusion / TLDR</h2>

I cleaned and analyzed the Women's Education vs Fertility dataset, which I downloaded from Kaggle and utilized pandas in Python to remove countries that didn't exist in 2010, refined the year column to include only tracked fertility rate and education levels, and rounded and grouped the data based on year and country. I then exported the cleaned data to a CSV file and created simple and minimalist visualizations in PowerBI, including two orthographic maps, a scatter plot, two slicers, and three cards displaying the fertility rate, primary education level in years, and population of the world/selected countries. Finally, I concluded that there is a correlation between higher levels of education among women and lower fertility rates and that investing in female education is necessary to maintain a healthy population. These findings are summed up with the following statistics:

  - In 1950, the average fertility rate was 5.39 and the average primary education level was only 2.77 years. However, by 2010, there was a remarkable 59.5% drop in the average fertility rate, at 2.92 children per women, and a 104.2% rise in education levels, with an average of 8.8 years of primary education. This rapid change took place over just 70 years. Based on the formula (Average drop per educational year = (5.39 - 2.92) / (8.8 - 2.77)), we can estimate that for every additional year of education, the fertility rate dropped by 0.41.
