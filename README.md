# Big-Data-Analysis-on-Los-Angeles-Crime
In this project, I will use spark for big data analysis on LA crime data from 2010 to 2019. It's based on big data platform - Spark (on Databricks). The main purpose for this project is to get familiar with using distributed file system to analyze plenty of data. I implemented two kinds of programming languages (Python and SQL) to query the result of some pre-designed problems. Also did a time series analysis on this dataset using ARIMA model to practice relevant skills.

The source code file is uploaded in .ipynb format. For better view, please use the following link and open it in a new browser window.
[Source file for this project](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1772353219017266/2267549507577016/105392983207357/latest.html)

Other references:

[Data source for this project](https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z/about_data)

[Just one click to download data](https://data.lacity.org/api/views/63jg-8b9z/rows.csv?accessType=DOWNLOAD)

OLAP: OLAP, or online analytical processing, is technology for performing high-speed complex queries or multidimensional analysis on large volumes of data in a data warehouse, data lake or other data repository. OLAP is used in business intelligence (BI), decision support, and a variety of business forecasting and reporting applications. 

Summaries about this project:
- Used crime data from the Los Angeles area from 2010 to 2019 (more than 213,000 lines) as an example, created a data
analytics workflow from data collection, cleaning, storage and analysis via \textit{\textbf{PySpark}} and \textit{\textbf{SparkSQL}} on \textit{\textbf{Databricks}}.
- Performed \textit{\textbf{online analysis processing (OLAP)}} for large volumes of crime data.
- \textit{\textbf{Visualized}} the variation of crime over time and space, gained data-driven insights on crime mechanism.
- Fine-tuned \textit{\textbf{ARIMA model}} to predict the number of crimes in acertain period and \textit{\textbf{cut down MSE by}} 4898.32.
