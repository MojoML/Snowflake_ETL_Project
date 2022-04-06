# Snowflake_ETL_Project

## Project Workflow

A Snowpipe is initialized to sync with an Amazon S3 Bucket. Once Data about German Foreign Trade Statistics arrives the Bucket a Copy Command is ttriggered in Snowflake, which extracts that Data into the Staging Area of the Data Warehouse. 

In the Staging Area, the Data is cleaned and transformed for Dimensional Modeling. Once the Dimension Tables and Fact Tables have been created, the Data is copied into another S3 Bucket for possible Machine Learning Applications. Furthermore, a Microsoft Power BI Report is created.


## Solution Architecture

<img width="1481" alt="image" src="https://user-images.githubusercontent.com/60922141/161927594-d78061fd-1d28-4a85-b796-5a32cd839827.png">


## Power BI Report

Here, a Snippet of the Power BI Report is shown. It includes visual Information about Economic Trade Statistics (Import, Exports). It enables a deeper Dive into Trade Relationships with individual Countries, as well as to how different Commodities influenced the overall Economic Performance of the Country.

<img width="1297" alt="image" src="https://user-images.githubusercontent.com/60922141/161928626-09384a87-0d1e-40e5-8d9e-72afb7af6d15.png">
