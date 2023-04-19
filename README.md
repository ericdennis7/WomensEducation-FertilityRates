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

  To begin, I first downloaded the dataset from Kaggle on WOmen's Education vs Fertitlity. I then used pandas in Python to clean the data. The first step of the cleaning process was to remove all countries that are not currently around in 2010. I managed to do this by using AI to form a list of present day countries and used pandas to check if the country was in the CSV dataset file. If the country was not in the present day country list, it was removed.
  Next, I cleaned the year column to only include values where years where both the fertility rate and education levels were tracked to create clearer visualizations tools. Furthermore, I cleaned the data by rounding and grouping values based on year and country.
  Finally, I exported the clean data back into the CSV file to be uploaded into PowerBI to create visualizations.
  
<h3>Creating Visualizations Using Power</h3>

Firstly, I uploaded the cleaned data into PowerBI. I decided to go with a simple and minimilastic format so as not to crowd the viewer with information overload. 


<h2>💤 TLDR</h2>
