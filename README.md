# Eylem Yildirim
**`Data Analyst / Digital Marketer / Gym Rat / Mother`**
I’m a data analyst with a passion for turning numbers into narratives and optimizing everything—whether it's ad performance, machine learning models, or even my kids’ Uno strategy. With over 20 years in data analytics, performance marketing, and ad-tech, I thrive on uncovering insights that drive real business impact. I specialize in SQL, Python, big data, and machine learning, helping businesses maximize ROI, improve KPIs, and optimize LTV.

When I’m not diving into datasets or fine-tuning predictive models, you’ll find me staying active—whether it’s working out, sprinting around the park in epic races with my kids, or outthinking them in a heated Uno showdown (spoiler: they win more than I’d like to admit). I also love reading and constantly exploring ways to refine strategies, not just in business but in life. My goal? To keep pushing boundaries, solving complex problems, and making data-driven decisions that matter.

## Languages and Tools
SQL, PostgreSQL, SQLAlchemy, NoSQL, MongoDB, Flask, PyMongo, Python, Jupyter Lab, Machine Learning, TensorFlow, Scikit-learn, Big Data, Hadoop, PySpark, Hive
AWS SageMaker AI, Google Colab, Databricks


## Projects 
### Tableau
#### Tableau citibike project

Designed and developed an interactive dashboard to help Citi Bike officials analyze usage trends, optimize operations, driving increased awareness and program efficiency.

**Tech Stack:** Tableau Public, Jupyter Lab, Python, Pandas

- Developed an interactive map and conducted station ID analysis, along with monthly, weekly, and daily usage statistics, enabling data-driven decisions to enhance the Citi Bike NYC's efficiency and performance.

[View Tableau Dashboard](https://public.tableau.com/app/profile/eylem.yildirim/viz/citybikeproject_17400059229000/Story1)

[View Repository](https://github.com/skythelimitdt/tableau-citibike-analysis)



### Machine Learning & Neural Networks
#### Credit Risk Classification Model via Machine Learning

**Tech Stack:** Jupyter Lab, Python, Pandas, Numpy, Scikit-learn

- Loan Risk Prediction with Logistic Regression and SVM: Built and evaluated models using Logistic Regression and Support Vector Machines (SVM) on a peer-to-peer lending dataset to classify borrowers as low-risk or high-risk.
- SVM Outperformed Logistic Regression in Recall: While both models achieved 99% accuracy, SVM demonstrated higher recall (98%) for high-risk loans, reducing false negatives and improving classification balance.
- Recommended Model – SVM for Financial Decision-Making: Due to its superior recall and macro-average score (96%), SVM was the preferred model, minimizing the misclassification of high-risk loans as low risk—critical for lending risk assessment.

[View Repository](https://github.com/skythelimitdt/credit-risk-classification)

#### Crypto Clustering via Unsupervised Machine Learning Algorithm, K-means clustering

**Tech Stack:** Jupyter Lab, Python, Scikit-learn, Pandas, Hvplot

- Optimized Clustering with K-Means and PCA: Applied K-Means clustering on normalized cryptocurrency data, identifying an optimal k-value of 4 using the elbow method.
- Dimensionality Reduction Improved Cluster Separation: Performed PCA (3 components, 89% variance retained), leading to tighter, more compact clusters and reducing noise while preserving key data patterns.
- Enhanced Cluster Definition with PCA: Post-PCA clustering showed lower inertia (256.87 vs. 287), confirming improved cluster cohesion and a more defined structure in the data.

[View Repository](https://github.com/skythelimitdt/CryptoClustering)

#### Predicting Success of a Company with a Neural Network

**Tech Stack:** Python, Scikit-learn, TensorFlow, Matplotlib, Pandas

- **Objective:** Created a neural network to predict the success of organizations applying for funding from Alphabet Soup, using features such as application type, affiliation, and funding amount.
- **Optimization Techniques:** Applied various methods like feature selection, dropout regularization, early stopping, and hyperparameter tuning using Keras Tuner to improve model performance.
- **Results:** The best model achieved an accuracy of 0.7335, with further improvements limited by model complexity and dataset alignment. Alternative models like Logistic Regression and Random Forest could be considered for better efficiency and performance.

[View Repository](https://github.com/skythelimitdt/deep-learning-challenge)

#### Predicting Flight Delays with Machine Learning

**Tech Stack:** Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, TensorFlow

- **Objective:** Developed a machine learning model to predict flight arrival delays for flights departing from Arizona airports using 3 years of flight data, employing models like Random Forest, Gradient - Boosting, and Neural Networks.
- **Data Analysis & Visualization:** Conducted data cleaning, feature engineering, and created visualizations using Tableau to identify patterns such as delay causes, carrier frequencies, and time-of-day impacts on delays.
- **Best Model & Results:** The Random Forest model, optimized with SMOTE and hyperparameter tuning, achieved 89% accuracy and 91% OOB score, accurately predicting on-time and delayed flights with high precision and recall.

[View Repository](https://github.com/wrighang/predicting_flight_arrival_delay_ml/tree/main)

### Databases
#### Flask API Climate App with SQLAlchemy

**Tech Stack:** SQLAlchemy, Python, Pandas, Matplotlib, Numpy

- **Climate Data Analysis for Honolulu:** Conducted an exploratory analysis of precipitation and temperature trends in Honolulu using Python, SQLAlchemy, Pandas, and Matplotlib. Queried 12 months of precipitation data, identified the most active weather station, and visualized temperature observations.
- **Flask API Development for Climate Data:** Built a Flask API to serve climate data via multiple endpoints, including precipitation records, weather stations, and temperature observations for the most active station. Implemented JSON responses for user-defined date ranges.
- **Interactive Data Exploration & Visualization:** Created line plots and histograms to analyze precipitation patterns and temperature distributions, helping users interpret historical climate trends for better vacation planning.

[View Repository](https://github.com/skythelimitdt/sqlalchemy-challenge/tree/main)

#### Employee Database Analysis with SQL

**Tech Stack:** SQL, PostgreSQL, quickdatabasediagrams.com

- **Database Schema Design:** Created an Entity Relationship Diagram (ERD) to model relationships between employees, departments, salaries, titles, and managers. Defined primary and foreign keys to ensure data integrity.
- **Data Engineering & SQL Table Creation:** Designed and implemented a relational database schema using SQL. Created six tables with appropriate data types, constraints, and relationships, then imported CSV data into the database.
- **SQL-Based Data Analysis:** Conducted complex queries to retrieve employee and department-related insights, including salary details, hire dates, department managers, employees in specific departments, and common last names. Optimized queries for performance and accuracy.

[View Repository](https://github.com/skythelimitdt/sql-challange)

#### UK Food Hygiene Ratings Analysis with MongoDB

**Tech Stack:** MongoDB, Jupyter Lab, Python, PyMongo, pprint

- **Database Setup & Data Import:** Imported food establishment data from a JSON file into MongoDB, set up a database (uk_food), and confirmed data integrity.
- **Data Cleaning & Updates:** Added a new restaurant, updated incorrect data types (e.g., converting rating values and coordinates to numerical format), and removed establishments from Dover as per client request.
- **Exploratory Data Analysis:** Queried and analyzed food hygiene ratings to identify high- and low-rated establishments, focusing on London and new restaurant recommendations.

[View Repository](https://github.com/skythelimitdt/nosql-challenge/tree/main)

#### Crowdfunding Data Pipeline: ETL, Database Design, and Analysis

**Tech Stack:** PostgreSQL, quickdatabasediagrams.com, Python, Pandas, Numpy

- Developed an ETL pipeline using Python and Pandas to extract, transform, and load data into a PostgreSQL database from four CSV files: Category, Subcategory, Campaign, and Contacts.
- Created DataFrames for each CSV, including columns like category IDs, campaign details (goal, pledged amount, launch and end dates), and contact information, then exported them to CSV files.
- Designed and implemented a PostgreSQL database schema with appropriate primary and foreign keys, ensuring proper relationships between tables, and successfully imported the data into the database for analysis.

[View Repository](https://github.com/skythelimitdt/Crowdfunding_ETL)


### Python

#### Statistical Analysis: Capomulin Drug Analysis

**Tech Stack:** Jupyter Lab, Python, Matplotlib, Seaborn, Pandas, Numpy, SciPy

- **Statistical Analysis & Visualization:** Analyzed data from an animal study of SCC tumor treatment, generating summary statistics, and visualizations (bar charts, pie charts, box plots) to compare the efficacy of Capomulin against other drug regimens.
- **Correlation & Regression:** Performed correlation analysis and regression to assess the relationship between treatment and tumor development, providing insights into the performance of Capomulin in comparison to other drugs.

[View Repository](https://github.com/skythelimitdt/matplotlib-challange)

#### Global Energy Consumption Analysis and Trends

**Tech Stack:** Jupyter Lab, Python, Matplotlib, Pandas, Hvplot, Numpy, SciPy, Seaborn, Statsmodels.api, Holoviews

- **Analyzed global energy trends** using the World Energy Consumption dataset to explore relationships between energy production, consumption, GDP, and environmental factors.
- **Investigated correlations** between renewable energy use and economic indicators, as well as how energy trends align with major global events.
- **Forecasted future renewable energy consumption** for the next 50 years based on historical data.

[View Repository](https://github.com/skythelimitdt/data_analytics_proj1)

#### Weather Patterns and Vacation Planning by Latitude

**Tech Stack:** Jupyter Lab, Python, Matplotlib, Hvplot, Pandas, Numpy, SciPy, Geoapify API

- **Weather Analysis by Latitude:** Used OpenWeatherMap API to retrieve weather data for over 500 cities, and created scatter plots to visualize how latitude influences weather variables like temperature, humidity, cloudiness, and wind speed.
- **Linear Regression & Insights:** Computed linear regression for each relationship (temperature, humidity, cloudiness, wind speed) based on latitude, splitting the data into Northern and Southern Hemispheres for detailed analysis.
- **Vacation Planning:** Created an interactive map that displays cities with humidity data, narrowed down cities with ideal weather, and used the Geoapify API to find nearby hotels, displaying them on the map with additional details for easy vacation planning.

[View Repository](https://github.com/skythelimitdt/python-api-challange/tree/main)

### Javascript & HTML

#### Interactive Dashboard in Javascript

**Tech Stack:** Javascript, HTML

- **Microbial Diversity Analysis:** Explored the Belly Button Biodiversity dataset to understand microbial species distribution across individuals. Identified a small number of dominant bacterial species while most were rare.
- **Interactive Data Visualization:** Developed an interactive dashboard using D3.js to allow users to explore microbial diversity per individual. Created a dropdown menu to select participants and dynamically update visualizations.
- **Data-Driven Insights:** Implemented a horizontal bar chart to display the top 10 bacterial species per individual, a bubble chart to show the distribution of all OTUs, and a metadata panel to present participant demographic details.

[View Dashboard](https://skythelimitdt.github.io/belly-button-challenge)

[View Repository](https://github.com/skythelimitdt/belly-button-challenge)

#### Map with leaflet

**Tech Stack:** Javascript, Leaflet.js, D3.js, HTML, CSS

- Created an interactive map using Leaflet.js to visualize real-time global earthquake data and tectonic plate boundaries.
- Earthquakes are represented by circle markers where size indicates magnitude and color reflects depth, with popups providing detailed information.
- Integrated interactive layer controls for toggling earthquake and tectonic plate data, offering various base map options (Satellite, Grayscale, Outdoors), and a legend for depth color-coding.

[View The Interactive Map](https://skythelimitdt.github.io/leaflet-challenge)

[View Repository](https://github.com/skythelimitdt/leaflet-challenge)

#### Mars Data Scraping and Climate Analysis

**Tech Stack:** Jupyter Lab, Python, Splinter, Beautiful Soup, Pandas, Matplotlib, JSON

- **Web Scraping for Mars News:** Used Splinter and Beautiful Soup to extract article titles and preview text from the Mars news website, storing the data in a structured format.
- **Scraping and Analyzing Mars Weather Data:** Collected temperature and atmospheric pressure data from a Mars weather site, structured it into a Pandas DataFrame, and conducted analysis to identify climate trends on Mars.
- **Data Visualization & Insights:** Explored seasonal variations on Mars, identified the coldest/warmest months, examined atmospheric pressure trends, and estimated the length of a Martian year in Earth days.

[View Repository](https://github.com/skythelimitdt/WebScraping)
