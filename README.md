# Crowdfunding-ETL

## Objective

   Goal of the project is to analyse crowd funding data set using python, SQL ETL and query skills to answer key questions
    - Each contact of every live campaign to inform them of how much of the goal remains
    - Each backer of every live campaign to let them know how much of the goal remains for each campaign that they’ve pledged

## Deliverables

1. Extract Data:
      Extract data from the source file and create data frame
      
      ![](https://github.com/SuniAnalytics/Crowdfunding-ETL/blob/main/ScreenShot1_Deliverable1.png)
      
2. Transform & Clean Data
      Covert cd_id into int and split name as first and last name
   ![](https://github.com/SuniAnalytics/Crowdfunding-ETL/blob/main/ScreenShot2_Deliverable2.png)

3. Prepare Database (Create ERD, Schema and load data)
    Using SQL: create backers table, alter tables to add keys, load backers table
    ![](https://github.com/SuniAnalytics/Crowdfunding-ETL/blob/main/crowdfunding_db_relationships.png)

4. SQl Analysis:

   - Retrieve # of backer counts for each live campaign (sort descending order)
   - Retrieve number of backers for each cf_id (desc sort)
   - List contacts for all live campaign and pending goal amount
   - List backers for all live campigns, pledged amount & remaining goal
  
  Screenshot of SQL Queries
![](https://github.com/SuniAnalytics/Crowdfunding-ETL/blob/main/ScreenShot3_Deliverable4.png)

