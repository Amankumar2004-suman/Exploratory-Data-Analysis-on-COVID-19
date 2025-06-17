# Exploratory-Data-Analysis-on-COVID-19
🦠 COVID-19 Data Analysis (India)
   This project is a beginner-friendly Exploratory Data Analysis (EDA) of COVID-19 data in India, created as part of my learning journey in Data Science. By following a YouTube tutorial and enhancing it with my     own understanding and visualizations, I analyzed the impact of the pandemic across Indian states and union territories over time.
📌 Project Objectives
   Understand the structure and trends in COVID-19 data in India
   Analyze the rise in confirmed, cured, and death cases
   Identify the top affected states/UTs
   Visualize daily and cumulative case progress
   Practice real-world data cleaning, aggregation, and plotting
🗂 Dataset Used
   File: covid_19_india.csv
   This dataset includes:
   Column Name	Description
               Sno	                        Serial number
               Date                         Date of the record
               Time	                        Time of the record
               State/UnionTerritory	        Name of the state or union territory
               ConfirmedIndianNational	    Confirmed cases among Indian nationals
               ConfirmedForeignNational	    Confirmed cases among foreign nationals
               Cured	                      Number of cured cases
               Deaths	                      Number of deaths
               Confirmed	                  Total number of confirmed cases

🧰 Tools & Libraries Used
  Python
  Pandas – Data manipulation
  NumPy – Numerical operations
  Matplotlib and Seaborn – Data visualization
  Jupyter Notebook – Interactive analysis environment
🔍 Analysis Workflow
  1.Loading the Dataset
  Read the dataset using Pandas and inspect its structure.
  2.Understanding the Data
  Review column types, summary statistics, and missing values.
  3.Data Cleaning
  Remove duplicates and handle null values
  Convert date columns to proper datetime formats
  4.Statistical Analysis
  Calculate average, median, and trends in confirmed, cured, and death cases
  Identify daily and cumulative case changes
  5.Data Visualization
  Plot daily and total confirmed/cured/death cases over time
  Visualize top affected states using bar plots and heatmaps
  Show growth trends and comparisons between states/UTs
  6.State-wise Analysis
  Aggregate data by State/UnionTerritory
  Highlight top 5 or 10 states based on confirmed cases
📈 Sample Visualizations
  📊 Line plot of total confirmed vs cured vs death cases
  📍 Bar plot of top affected states
  🔥 Heatmap showing intensity of spread across states over time
🎯 What I Learned
  How to perform data cleaning and preprocessing on real-world health data
  Use of Pandas and Seaborn for efficient data analysis and visualization
  Gained confidence in working with time-series data and trend analysis
  Improved ability to communicate insights through charts and graphs
🙏 Acknowledgement
   This project is inspired by a YouTube tutorial that provided the base logic and structure. I built on top of it by modifying the code, exploring different visualizations, 
   and developing a better understanding of data analysis.
🚀 Future Improvements
   Add interactive charts using Plotly or Dash
   Automate data updates using a live API
   Create a web-based dashboard using Streamlit

