# Project-Portfolio
A collection of data-related projects that I have completed to showcase what I have learned and how I applied the skills I acquired throughout my data journey.

- [Python](#python)
- [Data Engineering](#dataengineering)
- [SQL](#sql)
- [Machine Learning](#machinelearning)
- [Tableau](#tableau)

<a id='python'></a>
## Python
|                        Project                      |                                                                                                                                        Description                                                                                                                                       |     Scope                                                                                                                                                                  |     Requirements                                                            |     Libraries                                                                                       |     Date Completed    |
|:---------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-----------------------|
| [Customer Segmentation](https://github.com/DSKunth/Customer-Segmentation)                         | Carry out segmentation of customers using  the transaction history of an online gift store                                                                                                                                                                                               | Data extraction, data exploration,  data preprocessing, exploratory data analysis,  customer segmentation based on RFM metrics                                             | Python,  Python IDE or text editor + CLI,  Jupyter notebook                 | os, sys,   pyscopg2,  pandas, numpy,  matplotlib,  seaborn, dotenv, scipy,  sklearn, yellowbrick    | August 2023           |
| [Happy Deliveries Case Study](https://github.com/DSKunth/HappyDeliveries-CaseStudy)                      | Use the data from Happy Deliveries,  a food delivery business based in Ireland.  The company aims to utilize its data  to gain an advantage over its competitors.                                                                                                                           | Data cleaning, exploratory data analysis                                                                                                                                   | Python, Jupyter notebook                                                    | Pandas, numpy, matplotlib, seaborn                                                                  | May 2023              |
| [A/B Test – Online Store](https://github.com/DSKunth/AB-Testing-Online-Store)                            | Conduct an analysis of an incomplete  A/B test project with expected result:  Within 14 days of signing up,  users will show better conversion into  product page views, product cart views and purchases.  At each of the stages of the funnel,  there will be at least a 10% increase. | Data exploration, data preprocessing,   exploratory data analysis,  evaluation of A/B test results, and conclusion                                                         | Python, Jupyter notebook                                                    | Pandas, numpy,  matplotlib, seaborn,  ploty.express, scipy,  statsmodel.pi                          | August 2022           |
|     [Comparing Search Interest with Google Trends](https://github.com/DSKunth/Comparing-Search-Interest-with-Google-Trends)    | Analyze Google Trends data related to  the popularity of five major browsers  and the Kardashian & Jenner sisters.                                                                                                                                                                       | statistical data analysis                                                                                                                                                  | Python, Jupyter notebook                                                    | Pandas, matplotlib                                                                                  | July 2022             |
| [Data Storytelling](https://github.com/DSKunth/Data-Storytelling)                          | Build a data story from the  movies dataset of a fictitious production company                                                                                                                                                                                                           | Data collection, data preprocessing,  insights, presentation                                                                                                               | Python, Jupyter notebook, Google slides or PowerPoint  for the presentation | Pandas, numpy, ast, re, matplotlib, seaborn                                                         | May 2022              |
| [Communicate Data Findings](https://github.com/DSKunth/Communicate-Data-Findings)                         | Demonstrate the importance and value of data visualization techniques  in the data analysis process: exploratory data analysis and explanatory data analysis  using the loan data from [Proper Marketplace](https://www.prosper.com/)                                                                                 | Preliminary wrangling, univariate exploration,  bivariate exploration, multivariate exploration,  inferences, explanatory data analysis,  slideshow to convey key insights | Python, Jupyter notebook                                                    | Pandas, numpy, matplotlib, seaborn                                                                  | May 2022              |
| [Data Wrangling - Twitter Data](https://github.com/DSKunth/Data-Wrangling)                  | Perform data wrangling tasks on the  tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates),  also known as WeRateDogs                                                                                                                                                                                 | Data gathering, data quality audit,  data cleaning, analysis, and visualization                                                                                            | Python, Jupyter notebook                                                    | Pandas, numpy, matplotlib,  request, json, tweepy,  IPython.core.display                            | April 2022            |
| [Analyze A/B Test Result](https://github.com/DSKunth/Analyze-AB-Test-Results)                        | Perform A/B test and help the company decide  whether they should implement the new web page,  keep the old page, or run the experiment longer.                                                                                                                                       | Data exploration, data preprocessing,  probability analysis, hypothesis testing,  logistic regression, conclusion                                                          | Python, Jupyter notebook                                                    | pandas, numpy, random,  matplotlib, statsmodel.api, subprocess                                      | February 2022         |
| [Explore US Bikeshare Data](https://github.com/DSKunth/Explore-US-Bikeshare-Data)                   | Explore data related to bike sharing systems  for three (3) major cities in the United States: Chicago, New York, and Washington by using Python.                                                                                                                                         | Data exploration, descriptive statistics,  scripting – take in raw input to create an interactive experience  in the CLI to present these statistics                       | Python, Jupyter notebook, Python IDE or text editor + CLI                   | Pandas, time, numpy, calendar                                                                       | February 2022         |

<a id='dataengineering'></a>
## Data Engineering
| Project                            | Description                                                                                                                                                                   | Scope                                                                                                                                                                                                                                                                                                                                                | Requirements                                                                                              | Libraries                                         | Date Completed |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|---------------------------------------------------|----------------|
| [ETL Pipeline](https://github.com/DSKunth/ETL-Pipeline)                     | Build an ETL pipeline for online transactions data of an e-commerce platform                                                                                                   | Extract - connect to Amazon Redshift data warehouse and extract online transaction data with transformation tasks performed using SQL,  Transform - identify and remove duplicated records,  Load - connect to Amazon S3 cloud object storage and write the cleaned data as a CSV file into an S3 bucket,  Run ETL from the CLI and by using Docker  | Python, Dbeaver, Python IDE or text editor + CLI,  Docker, Amazon Redshift credentials, Amazon S3 details | psycopg2-binary, pandas, boto3, dotenv            | June 2023      |
|     [Data Modeling with Postgres](https://github.com/DSKunth/Data-Modeling-with-Postgres)   | Create a database schema, a Postgres database,  and develop ETL processes on song and log data collected from a music streaming app                                           | Create a database schema by defining fact and dimension tables,  create a Postgres database with tables designed to optimize queries on song play analysis, build an ETL pipeline that transfers data from files in two local directories  into these tables in Postgres using Python and SQL                                                        | Python, Python IDE or text editor + CLI, Jupyter notebook                                                 | psycopg2, os, glob, pandas, ipython-sql           | March 2022     |
| [Data Modeling with Cassandra](https://github.com/DSKunth/Data-Modeling-with-Apache-Cassandra)      | Create an Apache Cassandra database and  built an ETL pipeline on songs and user activity data  collected from a music streaming app which resides in a directory of csv files | Modeling Apache Cassandra database and build ETL pipeline                                                                                                                                                                                                                                                                                            | Python, Jupyter notebook                                                                                  | pandas, cassandra, re, os, glob, numpy, json, csv | March 2022     |

<a id='sql'></a>
## SQL
| Project                   | Description                                                                                                                                                                                            | Tasks            | Date Completed |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|----------------|
| [E-book startup](https://github.com/DSKunth/SQL-Project-Ebook-Startup)         | Provide answers to business questions  to help the startup company  create a product value proposition                                                                                                 | Data exploration | August 2022    |
| [Deforestation Exploration](https://github.com/DSKunth/Deforestation-Exploration) | Create views, simple and complex SQL queries  to answer questions from the fictitious ForestQuery management  about the deforestation’s global situation,  regional outlook, and country-level details | Data exploration | March 2022     |

<a id='machinelearning'></a>
## Machine Learning
| Project                            | Description                                                                                                                                      | Scope                                                                                                                                                                                          | Area                                    | Algorithm                  | Date Completed |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------|----------------------------|----------------|
| [Customer Segmentation based on RFM](https://github.com/DSKunth/Customer-Segmentation/tree/main/notebooks) | Carry out customer segmentation based on RFM metrics using K-means clustering                                                                    | Data exploration, data preprocessing, EDA, customer segmentation                                                                                                                               | Unsupervised learning - Clustering      | K-means clustering         | August 2023    |
| [Predicting Credit Card Approvals](https://github.com/DSKunth/Predicting-Credit-Card-Approvals)   | Build an automatic credit card approval predictor using the credit card approval dataset                                                         | Data exploration, data preprocessing (scaling, label encoding, missing value imputation),  EDA, fitting logistic regression model to the train set, making predictions, evaluating performance | Supervised learning - Classification    | Logistic regression        | August 2022    |
| Product Categorization (***updating***)          | Carry out product category identification  based on the description field of an online transaction history dataset  of an e-commerce platform    | Data exploration, data preprocessing, product categorization, product category analysis                                                                                                        | NLP, unsupervised learning - Clustering | TF-IDF, K-means clustering | August 2022    |

<a id='tableau'></a>
## Tableau
| Project/Challenge                              | Dataset                                                                                                                 | Visualization                                                                                                                                                                                                                                | Date Completed |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| [Executive Dashboard](https://public.tableau.com/app/profile/dorothy.kunth/viz/ExecutiveDashboard_16934981219780/ExecutiveDashboard)            | Preprocessed online transaction data and customer segments data from the [Customer Segmentation](https://github.com/DSKunth/Customer-Segmentation) project | Text table to show performance metrics,  top-performing products and top-performing customers bar charts,  revenue by segment pie chart,  daily revenue timeline with 7-day moving average line chart                                         | August 2023    |
| [Superstore - Executive Dashboard](https://public.tableau.com/app/profile/dorothy.kunth/viz/Superstore-ExecutiveOverview_16667718902190/ExecutiveOverview)              | [Superstore dataset](https://data.world/search?context=community&entryTypeLabel=dataset&q=superstore&type=resources)                                                                                                      | Map to visualize profit ratio by geography,  area charts to convey sales by category and by segment,  text table using measure names and measure values as the key performance indicators,  bar chart that appears when hovered over the map | August 2022    |
| [Max and Min Sales by Month](https://public.tableau.com/app/profile/dorothy.kunth/viz/WOWEssentialsMAXandMINSalesbyMonth/WOWEssentialsMAXandMINSalesbyMonth)                     | [Superstore dataset](https://data.world/search?context=community&entryTypeLabel=dataset&q=superstore&type=resources)                                                                                                      | Table showing sub-category by month:  sub-categories are sorted in descending order by total sales of the year;  for each month, highlight the min sales in red, and max sales in blue;  users should be able to filter by year and category | August 2022    |
| [Customers whose Sales have Increased Each Year](https://public.tableau.com/app/profile/dorothy.kunth/viz/WOWEssentialsCustomerswithSalesIncreaseeachyear/CustomerswithYearlySalesIncrease) | [Superstore dataset](https://data.world/search?context=community&entryTypeLabel=dataset&q=superstore&type=resources)                                                                                                      | Text table showing sales by customers and years  but only including customers whose sales have increased from 2018 to 2021  and sorting by 2021 sales amount                                                                                 | August 2022    |
