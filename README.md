<h1>The Impact of Education on Women's Fertility Rates (Globally)</h1>

<h2>ℹ️ Information About the Study</h2>
<h3>A Brief Introduction</h3>

As a <i>staunch</i> advocate of education, particularly for women, I have been contemplating the impact of education on the birth rate of women worldwide. The latest news reports indicate that Japan is grappling with a dire fertility crisis, with its birth rate failing to keep pace with the death rate. This has coincided with an increase in women's education. This has resulted in significant economic, social, and governmental challenges. I can't help but wonder if the growing prevalence of women's education is a contributing factor to this crisis. This study researches global patterns to see if there is a correlation among women's fertility rates and their average education level.

<h3>Questions to Study</h3>

- Is there a correlation between higher levels of education among women and lower fertility rates?
- How have trends in women's education and fertility rates evolved over time, and what implications does this have for future population growth?

<h3>Dataset and Project Information</h3>

Original Dataset Link: <a href = "https://www.kaggle.com/datasets/valchovalev/womenseducationalattainmentvsfertility?resource=download">Women's Educational Attainment vs Fertility</a>

Software/Tools Being Used:
- Python
  - Plotly
  - PYODBC
- <a>womens-educational-attainment-vs-fertility.csv</a>

<i><b>* Since there is a limited amount of data available, I will not be creating a dashboard for this project. Instead, I will be analyzing the data using visualizations created with the Plotly Python library. *</b></i>

<h2>🔍 The Study (Process)</h2>

<b>PowerBI Dashboard:</b> <a href="https://app.powerbi.com/view?r=eyJrIjoiOWQyOTg5ZDItOTk1OC00NmMyLTkwM2UtNTYzNWNkYTI0YzIwIiwidCI6ImU0YTdiMmYwLTRkM2QtNDI0OC05YTdiLWEyNjQ4ZTIzN2MxNSIsImMiOjF9">Fertility Rate vs. Education Level</a>

<h3>Obtaining and Cleaning the Data</h3>

To start the data cleaning process, I downloaded the Women's Education vs Fertility dataset from Kaggle. Using pandas in Python, I initiated the cleaning process by removing all countries that did not exist in 2010. To accomplish this, I utilized AI to create a list of present-day countries and cross-checked it with the CSV dataset using pandas. This ensured that only relevant countries were included in the analysis.

After filtering out the unnecessary countries, I further cleaned the data by refining the year column to only include years where both the fertility rate and education levels were tracked. This ensured that the resulting visualization tools were more informative and precise. Additionally, I rounded and grouped the data based on year and country to improve the data's readability and clarity.

Finally, I exported the cleaned data back into the CSV file and uploaded it into PowerBI to create visually appealing, interactive, and informative visualizations.
  
<h3>Creating Visualizations Using Power</h3>

Firstly, I uploaded the cleaned data into PowerBI. I decided to go with a simple and minimilastic format so as not to crowd the viewer with information overload. 


<h2>💤 TLDR</h2>
