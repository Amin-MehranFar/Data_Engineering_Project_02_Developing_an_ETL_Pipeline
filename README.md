# Data_Engineering_Project_02_Developing_an_ETL_Pipeline
In the following Data Engineering project, a complete ETL Pipeline has been constructed by scraping data from Wikipedia's list of countries ranked by GDP, transforming the dataset, and loading it into a database.

There are three types of GDPs reported on the website:

1. International Monetary Fund (IMF): This is our desired GDP, if available.
2. World Bank (WB): We extract this GDP if IMF is not available.
3. United Nations (UN): We extract this GDP if IMF and WB are not available.
