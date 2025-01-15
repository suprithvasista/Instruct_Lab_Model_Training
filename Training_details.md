Mbb labs month on month work.
Date of joining 08-jun-2022(Team UDL)
End date of internship 28-fev-2023(Team UDL)
Confirmation to convert to FTE was initiated at 16-dec-2022(Team UDL)
From September(sprint) Swallow was also part new team PAM-2
Internship Work.
1st sprint: Juniper Berries. -25-Jun-2022
Learned about the basic frame works in udl technologies used and implemented.
1st task was to identify Data quality checks that were configured in oracle framework identifying the wrongly configured query in custom check frame work.
Picked up an excel automation using python for a requirement that used to require manual intervention of excel consolidation and insertion in to oracle tables for our application to consume.
2nd sprint: Jungfrau:- 23-jul-2022
Created a proof of concept for odi 12c meta data extraction using odi 12 c repositories.
3rd sprint: Aconcagua: 18-aug-2022
	Will update with some things.
Picked up installer preparation process through documents. Which is a manual process of packaging an installer.
4th sprint: Shivling: 18-sep-2022
Came up with an end to end design for automating the tedious manual process by automating the installer preparation using python.
Helped in seeding 3 months of redw and udl reconciliation data for sunburst chart.
5th sprint: Om paravat 25-oct-2022
My first business use case and data implementation activity came up in the form of bnmsic data changes.
Had to analyze the industry code changes at multiple layers and get read with the data and mapping changes scripts.
Based on the bnmsic changes automated this work flow of generating scripts and difference finding and generating excel report of changes and seeded data entry preparation. 
Helped in smooth transition of data throughout devproduction
6th sprint: Nanda Devi 22-nov-2022
Helped in adding additional columns in enterprise dimension and test and validate the data in this dimensions.
For this additional columns had to map the data based on the existing codes and new codes using like-like match which i used excel formulas along with python to generate the seeded entries for this table.
7th sprint: Denali  16-dec-22
First Udl component I got an opportunity to work on is data truncation frame work.
Oracle Framework coded in plsql.
Hive Framework coded in scala.
Also got to work on general ledger reconciliation framework which is developed using scala.
Had to make some changes to compute the select columns and expression columns separately to avoid mis match issues.
8th sprint: Jomulahari  13-jan-2023
Worked on balance reconciliation frame work. (Teradata)
Worked on attribute reconciliation frame work. (Teradata)
Worked on Enhancing the dq custom function in sql to support the framework for fct tables. 
Enhancing the data retention framework to handle the data discrepancy in com load history and actual physical table.
9th sprint: Fujiyama  10-Feb-2023
Recon attribute engine enhancement to support the oracle connection based on CSCM and source id passed.
Retention frame work enhancement to support month end retentions.
Took up an activity and built enterprise library to connect to different platform and query up on it. Which can be called across all the programs which will connect to different platform by just calling the method/function by just importing the library.
Achievements:
Also the first intern to get nominated for star performer of the sprint, Didn’t receive this award because I was an intern.
FTE Works
Date of joining 01-mar-2023
10th sprint: Mont Blanc 10-mar-2023
Enhancement for DQ spark frame to work with fct tables.
Achievements:
Won best employee in the quarter.
        11th sprint: Matterhorn  04-apr-2023
Helped in production deployment udl version 1.11.0.0 a major release. Without any hiccups.
And also successfully implemented the bnmsic changes in production for Malaysia and Singapore.
Achievements:
Best performing team in the sprint. 
Got nominated for star performer of the sprint, and won the award.
12th sprint: Annapurna03-may-2023
Worked on odi query and error retrieval during run time. Used spark to connect to odi repositories to extract query on run time and error during any failures and load the data into error log tables.
Created end to end engine to run queries on hive through UI by using middle man wrapper shell script and python for remediation base table creation.
Enhancement to recon engine to run the remediation queries. By querying oracle remediation view.
13th sprint: Machhapuchhare02-JUN-2023
Enhanced the industry data retrieval process. Created a new pipe line from drm to udl direct industry data flow instead of manual data seeding.
Enhanced odi procedure to have dynamic outbound generation for lima pipe lines in odi.
14th sprint: Jichu Drake28-jun-2023
Enhancement to dq spark frame work to support not null.
Enhancement to remediation wrapper to support data drop at each execution using hdfs commands.
Excel upload template generation adding readme worksheet appropriate tags based on column type using metadata and also use appropriate color coding.
Also in the data loading sheet I template reflect the same color and also provide pop up feature in excel for each column using metadata tables.
Egg: - sample values,default values,pk column info,fk column info.
15th sprint: Jungle myna26-jul-2023
Helped drm flatten the data table which provide data about the industry which helps the application to direct query the data from single table and view.
Enhanced dq spark frame work to dynamically handle the program exit on error by providing default execution parameter in respective of non-prod and production.
Generic excel consolidation utility.
16th sprint: Aquatic Warbler24-aug-2023
Helped in configuration.
17th sprint: Sandpiper21-sep-2023
Worked on closed account summary engine to count the reopened accounts on previous run during the current date execution and report the error through the automated mail system.
Created excel template generation at installer runtime using shell script which retrieves excel upload tables and create the templates leveraging the already existing excel upload engine by making some tweaks. 
Enhance the excel engine to log the session activity performed by user. Also capture the error into the audit table in oracle for ui to display run time errors.
Enhanced the gl recon engine to support both backend execution and front end execution from gl recon screen
18th sprint: Owl19-oct-2023
Enhancement to accept the new parameter unique batch id passed from ui.
19th sprint: Nightangle26-nov-2023
Enhancement the gl recon to generate unique batch id for each execution from backend instead of front end execution.
Enhancement to incremental shell script to priorities the source id which is passed instead of the default source id from properties which helps in avoiding the program exit process because of change in source for any incremental table.
Helped develop new incremental frame work end to end with proper use case and demoed to all po’s.
Create an enterprise library to calculate any table stats which can be leveraged any spark program to compute stats of partitioned or non-partitioned.
20th sprint: Dove07-dec-2023
SCD/SCD recovery performance improvements from 4hour run time for one party job to 17 minutes.
Created the library which is leveraged by many spark components to calculate the data size and data count from spark meta store.
Create a library which chooses appropriate persist mechanism based on data size at run time computation which is also leveraged by many spark engines.
Created a function to data insertion into to any table by just calling the library along with the function. It auto identifies the partition based on the table information and inserts the data into any tables.
21 sprint: Dunnock04-jan-2024
Create a frame work to extract sample data for specific subject area in our case. It can be used to extract data for any table with corresponding reference tables based on the configuration. Here I came up with complete design plan and implementation along with code.
  Created a generic utility to auto run scheduled jobs based on the sla configured.
Use case implemented is for sla where the tables load sla is configured if missed and misses the buffer period the data is auto loaded into the table to not miss sla and not cause any data issues in corresponding tables.

22nd sprint: Jamaican Oriole01-feb-2024
Enhancement to all scripts in udl to log the user id and start time in load history tables.
23rd sprint: Falcon29-feb-2024
Complete design change to dq spark frame work for parallel execution of queries.
Not null.
Enhancement to remediation to support the Teradata and oracle querying.
Leveraged the library created earlier to connect to any databased used across udl just base on connection type.
24th sprint: Magpie28-mar-2024
Implemented same changes for both reference the lov checks to run in unison.
Implemented auto exclusion of dq execution along with spark frame work based on table loads in country specific schemas.
Automated the boring setting up rsa authentication for each instance of ui deployments in different env.
Adopted view partitioning which helped in solving performance issues in data load in production which was because of lack of partition pruning.
25th sprint: Avocet25-apr-2024
Enhance the dq views that is used in dq screen in ui to display appropriate data as transposed data in ui for each execution instance of dq along with results.
Enhanced the dq frame work to log the exclusion entries into log files.
26th sprint: Merlin23-may-2024
Implemented batch frame work for dq engine.
As part of this created a shell script to handle the dq execution at batches to match the execution flow of udl batch.
27th sprint: Japanese Robin23-jun-2024
Implemented recursive incremental recovery solution end to end for bcbs use case and productionized it.
As part of this developed a wrapper to execute the incremental recovery engine recursively based on mis_date and recursive_date_exe_number.
28th sprint: Will_Map_it23-jul-2024
Implemented the Global value conversion in alt measure engine which is used to have all measure values converted to respective country values for reporting purpose and productionized it.


29th sprint: Anhinga23-aug-2024
Enhanced scd changes to close the records which are not part of stg loads in future dates as per adhoc runs and also made essential changes to improve SLA by exiting the program if no changes are found.
Implemented the same changes across the engines like incremental,alt measures to exit code if no changes are found.
30th sprint: Swallow11-sep-2024
Team UDL
Dim customer job performance improvement. 
Enhanced the dim customer spark job to give better performance reduced the job execution by 60%.
As part of this enhancement planned and designed the architecture end to end with complete data validation from development to production.
As part of the job load we populate on a daily basis of 600 Million records.

Helped Implemented NZCC project in Singapore Production by understanding the requirement and extracting the data as per the requirement posed by using the same frame work which we had developed to provide outbound.
Team PAM-2
Helped in designing the tables with complex partition but effective partition which works for the requirements.
Helped in research and develop engine to load millions of records into same oracle tables reducing the load to matter of seconds. (Where the we had to load the data into 30 tables with approximate 100 million records across each table data size spanning from 4-20 gb files in record time of 24 seconds for the biggest table and total time spanning to matter of minutes)
Created a procedure to update certain sections of table(columns) by implementing config table design.
And also devised a way to extracts all the tables processed data as out bounds utilizing spool with optimized configuration resulting in an average timing of 40 minutes for approximately over 100 million records combined.
