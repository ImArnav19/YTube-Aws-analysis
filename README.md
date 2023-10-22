# YTube-Aws-analysis
End to End Youtube dataset analysis with Aws

**1. Fetching Dataset from Kaggle**, 
https://www.kaggle.com/datasets/datasnaek/youtube-new

Saving the dataset values with csv and json different in S3 storage

**2.Creating Crawlers for json then Using lambda function for auto Cleaning**
<img width="549" alt="Screenshot 2023-10-22 203701" src="https://github.com/ImArnav19/YTube-Aws-analysis/assets/117253613/11c5db8a-43db-4a09-bceb-7c22c7fff7ea">

Use of triggers and thus data stored at new S3 cleaned

**3.Csv data cleaning, crawlers for storing intermediated in Catalog and then use of ETL Jobs(Pipeline) for cleaning**
Spark COde Attached

<img width="741" alt="Screenshot 2023-10-22 204208" src="https://github.com/ImArnav19/YTube-Aws-analysis/assets/117253613/998f1e15-ce36-458d-81ad-8c9a483878bb">

Thus both data now cleaned in different tables in GLue Catalog

**4.Last Step Join all the cleaned data gathered in a single S3 storage (Parquet file) then create dynamic catalog table for Athena and Quicksight for Analysis**

Done Entirely with ETL Pipeline(Visual ETL)


<img width="598" alt="Screenshot 2023-10-22 204620" src="https://github.com/ImArnav19/YTube-Aws-analysis/assets/117253613/c3427da1-1643-4103-89e9-323bdd710310">

Thus we can now query data after cleansing and proceed with Analysis


