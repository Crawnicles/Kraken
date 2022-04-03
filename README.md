# Kraken

In preparation for a job interview with Kraken for a Treasury Project Management - Data Analyst role. 
The role suggests the applicant has the following technical skills, therefore I will display these: 



Advanced knowledge of SQL, scripting languages and database concepts
•
A consistent track record of performing data analysis using scripting language (Python, Javascript, etc) and/or experience with a programming language (Java, Scala, Golang, etc)
•
Experience with BI Software (Superset / Tableau / etc)
•
Familiarity with data warehouse development and best practices
•
You will transform large datasets from complex systems, generate actionable insights and share the results with stakeholders at all levels of the company
•
You will partner and lead projects with finance teams, product management, engineering, and other enterprise level teams
•
You are a self-starter, results driven and passionate to drive success of products at Kraken using the power of data analytics
•
Leverage extremely large databases maintained by the Data teams to create advanced reports & data visualizations to analyze Kraken’s international balance sheets and liquidity
•
Support the implementation of the Treasury Management System and the data requirements for integration
•
Conduct data analysis and generate actionable insights and make recommendations for improving workflows and data
•
Communicate key results with self-serve tools (dashboards, analytics tools) for Treasury and key stakeholders
•
Develop and automate reporting of key performance and risk metrics for Treasury solving for business priorities
•
Partner with Treasury teams, products and business enhance Treasury’s data and reporting capabilities
•
Collaborate with engineering teams and stakeholders to build key datasets and data pipelines using Python/ETL frameworks
•



1) Pulls data from any crypto API and converts the data into a DataFrame.

2) Uses the Dataframe to generate buy and sell signals in the crypto markets based upon multiple algorithms 

3) Displays the visuals of buy and sell signals across the historical data using Streamlit

4) Lastly append the buy/sell signals into a SQL database so as to imitate the process of a data ingestion team

5) Backtest to see if any strategies perform better within these higher volatility markets



Step 1:

In Terminal create a new conda environment:

*conda create --name krakenite python=3.7*

*conda activate krakenite*


pip install pandas
conda install matplotlib
pip install hvplot
pip install pykrakenapi



