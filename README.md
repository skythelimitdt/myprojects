# My Portfolio
A showcase of my Data Analytics projects, demonstrating a diverse skill set in Python, JavaScript, Machine Learning, SQL, NoSQL, and more.

Email: me@eylemy.com
Linkedin: [Eylem Yildirim](https://www.linkedin.com/in/eylemy/)

## Tableau
### Tableau citibike project

Designed and developed an interactive dashboard to help Citi Bike officials analyze usage trends, optimize operations, driving increased awareness and program efficiency.

**Tech Stack:** Tableau Public, Jupyter Lab, Python, Pandas

- Developed an interactive map and conducted station ID analysis, along with monthly, weekly, and daily usage statistics, enabling data-driven decisions to enhance the Citi Bike NYC's efficiency and performance.

[View Tableau Dashboard](https://public.tableau.com/app/profile/eylem.yildirim/viz/citybikeproject_17400059229000/Story1)

[View Repository](https://github.com/skythelimitdt/tableau-citibike-analysis)



## Machine Learning
### Credit Risk Classification Model via Machine Learning

**Tech Stack:** Jupyter Lab, Python, Pandas, Numpy, Scikit-learn

- Loan Risk Prediction with Logistic Regression and SVM: Built and evaluated models using Logistic Regression and Support Vector Machines (SVM) on a peer-to-peer lending dataset to classify borrowers as low-risk or high-risk.
- SVM Outperformed Logistic Regression in Recall: While both models achieved 99% accuracy, SVM demonstrated higher recall (98%) for high-risk loans, reducing false negatives and improving classification balance.
- Recommended Model – SVM for Financial Decision-Making: Due to its superior recall and macro-average score (96%), SVM was the preferred model, minimizing the misclassification of high-risk loans as low risk—critical for lending risk assessment.

[View Repository](https://github.com/skythelimitdt/credit-risk-classification)

### Crypto Clustering via Unsupervised Machine Learning Algorithm, K-means clustering

**Tech Stack:** Jupyter Lab, Python, Scikit-learn, Pandas, Hvplot

- Optimized Clustering with K-Means and PCA: Applied K-Means clustering on normalized cryptocurrency data, identifying an optimal k-value of 4 using the elbow method.
- Dimensionality Reduction Improved Cluster Separation: Performed PCA (3 components, 89% variance retained), leading to tighter, more compact clusters and reducing noise while preserving key data patterns.
- Enhanced Cluster Definition with PCA: Post-PCA clustering showed lower inertia (256.87 vs. 287), confirming improved cluster cohesion and a more defined structure in the data.

[View Repository](https://github.com/skythelimitdt/CryptoClustering)

## Databases
### Flask API Climate App with SQLAlchemy

**Tech Stack:** SQLAlchemy, Python, Pandas, Matplotlib, Numpy

- **Climate Data Analysis for Honolulu:** Conducted an exploratory analysis of precipitation and temperature trends in Honolulu using Python, SQLAlchemy, Pandas, and Matplotlib. Queried 12 months of precipitation data, identified the most active weather station, and visualized temperature observations.
- **Flask API Development for Climate Data:** Built a Flask API to serve climate data via multiple endpoints, including precipitation records, weather stations, and temperature observations for the most active station. Implemented JSON responses for user-defined date ranges.
- **Interactive Data Exploration & Visualization:** Created line plots and histograms to analyze precipitation patterns and temperature distributions, helping users interpret historical climate trends for better vacation planning.

[View Repository](https://github.com/skythelimitdt/sqlalchemy-challenge/tree/main)

### Employee Database Analysis with SQL

**Tech Stack:** SQL, PostgreSQL, quickdatabasediagrams.com

- **Database Schema Design:** Created an Entity Relationship Diagram (ERD) to model relationships between employees, departments, salaries, titles, and managers. Defined primary and foreign keys to ensure data integrity.
- **Data Engineering & SQL Table Creation:** Designed and implemented a relational database schema using SQL. Created six tables with appropriate data types, constraints, and relationships, then imported CSV data into the database.
- **SQL-Based Data Analysis:** Conducted complex queries to retrieve employee and department-related insights, including salary details, hire dates, department managers, employees in specific departments, and common last names. Optimized queries for performance and accuracy.

[View Repository](https://github.com/skythelimitdt/sql-challange)

### UK Food Hygiene Ratings Analysis with MongoDB

**Technologies Used:** MongoDB, Jupyter Lab, Python, PyMongo, pprint

- **Database Setup & Data Import:** Imported food establishment data from a JSON file into MongoDB, set up a database (uk_food), and confirmed data integrity.
- **Data Cleaning & Updates:** Added a new restaurant, updated incorrect data types (e.g., converting rating values and coordinates to numerical format), and removed establishments from Dover as per client request.
- **Exploratory Data Analysis:** Queried and analyzed food hygiene ratings to identify high- and low-rated establishments, focusing on London and new restaurant recommendations.

[View Repository](https://github.com/skythelimitdt/nosql-challenge/tree/main)

## Python

### Statistical Analysis: Capomulin Drug Analysis

**Tech Stack:** Jupyter Lab, Python, Matplotlib, Seaborn, Pandas, Numpy, SciPy

- **Statistical Analysis & Visualization:** Analyzed data from an animal study of SCC tumor treatment, generating summary statistics, and visualizations (bar charts, pie charts, box plots) to compare the efficacy of Capomulin against other drug regimens.
- **Correlation & Regression:** Performed correlation analysis and regression to assess the relationship between treatment and tumor development, providing insights into the performance of Capomulin in comparison to other drugs.

[View Repository](https://github.com/skythelimitdt/matplotlib-challange)

### Global Energy Consumption Analysis and Trends

**Tech Stack:** Jupyter Lab, Python, Matplotlib, Pandas, Hvplot, Numpy, SciPy, Seaborn, Statsmodels.api, Holoviews

- **Analyzed global energy trends** using the World Energy Consumption dataset to explore relationships between energy production, consumption, GDP, and environmental factors.
- **Investigated correlations** between renewable energy use and economic indicators, as well as how energy trends align with major global events.
- **Forecasted future renewable energy consumption** for the next 50 years based on historical data.

[View Repository](https://github.com/skythelimitdt/data_analytics_proj1)

### Weather Patterns and Vacation Planning by Latitude

**Tech Stack:** Jupyter Lab, Python, Matplotlib, Hvplot, Pandas, Numpy, SciPy, Geoapify API

- **Weather Analysis by Latitude:** Used OpenWeatherMap API to retrieve weather data for over 500 cities, and created scatter plots to visualize how latitude influences weather variables like temperature, humidity, cloudiness, and wind speed.
- **Linear Regression & Insights:** Computed linear regression for each relationship (temperature, humidity, cloudiness, wind speed) based on latitude, splitting the data into Northern and Southern Hemispheres for detailed analysis.
- **Vacation Planning:** Created an interactive map that displays cities with humidity data, narrowed down cities with ideal weather, and used the Geoapify API to find nearby hotels, displaying them on the map with additional details for easy vacation planning.

[View Repository](https://github.com/skythelimitdt/python-api-challange/tree/main)

## Javascript & HTML

### Interactive Dashboard in Javascript

**Tech Stack:** Javascript, HTML

- Designed an interactive dashboard exploring cultured bacteria using javascript.

[View Dashboard](https://skythelimitdt.github.io/belly-button-challenge)

[View Repository](https://github.com/skythelimitdt/belly-button-challenge)

### Map with leaflet

**Tech Stack:** Javascript, Leaflet.js, D3.js, HTML, CSS

- Interactive map for global earthquake & tectonic plate visualization.
- Displays global earthquake data from the past 7 days.

[View The Interactive Map](https://skythelimitdt.github.io/leaflet-challenge)

[View Repository](https://github.com/skythelimitdt/leaflet-challenge)

### Mars Data Scraping and Climate Analysis

**Tech Stack:** Jupyter Lab, Python, Splinter, Beautiful Soup, Pandas, Matplotlib, JSON

- **Web Scraping for Mars News** – Used Splinter and Beautiful Soup to extract article titles and preview text from the Mars news website, storing the data in a structured format.
- **Scraping and Analyzing Mars Weather Data** – Collected temperature and atmospheric pressure data from a Mars weather site, structured it into a Pandas DataFrame, and conducted analysis to identify climate trends on Mars.
- **Data Visualization & Insights** – Explored seasonal variations on Mars, identified the coldest/warmest months, examined atmospheric pressure trends, and estimated the length of a Martian year in Earth days.

[View Repository](https://github.com/skythelimitdt/WebScraping)
