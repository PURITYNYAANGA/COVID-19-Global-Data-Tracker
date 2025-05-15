# COVID-19-Global-Data-Tracker

Project Description:
This project aims to build a data analysis and reporting tool (Jupyter Notebook or app) that tracks and visualizes global COVID-19 trends over time. Using real-world datasets, learners will:

Clean and process data

Analyze cases, deaths, recoveries, and vaccinations

Generate visual insights

Communicate findings through graphs and narratives

The final output will be a polished, insight-rich report ready for presentation or publishing.

🎯 Project Objectives:
✅ Import and clean real-world COVID-19 data
✅ Analyze time-based trends (cases, deaths, vaccinations)
✅ Compare metrics across countries and regions
✅ Visualize data using informative charts and maps
✅ Summarize and report insights in a reproducible format

🗂️ Project Segments (Step-by-Step):

1️⃣ Data Collection
Source: Our World in Data (OWID)

File: owid-covid-data.csv

Action: Download and save locally for use with pandas

2️⃣ Data Loading & Exploration
Load the data with pandas.read_csv()

Inspect columns: df.columns

Preview data: df.head()

Identify missing values: df.isnull().sum()

🔧 Tools: pandas

3️⃣ Data Cleaning
Filter specific countries (e.g., Kenya, USA, India)

Drop rows with missing dates or key values

Convert date to datetime with pd.to_datetime()

Handle missing numerics with fillna() or .interpolate()

4️⃣ Exploratory Data Analysis (EDA)
Plot total cases, deaths, and new cases

Calculate and visualize death rate = total_deaths / total_cases

Compare countries over time

🔧 Tools: matplotlib, seaborn
📊 Visuals: Line charts, bar charts, optional heatmaps

5️⃣ Vaccination Progress
Plot cumulative vaccinations over time

Compare % of vaccinated populations

📈 Charts: Line charts, optional pie charts
🔧 Tools: matplotlib, seaborn

6️⃣ (Optional) Choropleth Mapping
Use Plotly Express or GeoPandas to map total cases or vaccination rates globally

🔧 Tools: plotly express (easy), geopandas (advanced)

7️⃣ Insights & Reporting
Write 3–5 key takeaways (e.g., "India saw the sharpest spike in mid-2021")

Highlight outliers or interesting trends

Use Markdown cells to narrate findings

📤 Deliverables:

✅ Clean, commented Jupyter Notebook

✅ Includes code, visuals, and narrative

✅ Export to PDF or PowerPoint (optional)

🛠 Recommended Tools & Libraries
Jupyter Notebook (or VS Code with Jupyter)

pandas

matplotlib, seaborn

Optional: plotly, geopandas

Optional: Streamlit/Dash for dashboards

⭐ Stretch Goals
Interactive user inputs (country/date filters)

Dashboard with Streamlit or Dash

Add ICU/hospitalization metrics (if data available)

Achievements Upon Completion

Imported, cleaned, and explored COVID-19 data

Performed detailed EDA and comparisons

Built informative visualizations

Summarized findings clearly and professionally

