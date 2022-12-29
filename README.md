# DA-Project
> I'll put things from my Data Analytics Career Accel Studio project here.

  [Deepnote](https://deepnote.com/workspace/uni-b780-ef93fdef-c706-47b3-b054-4b4a1e6442fe/project/NU-project-be108f48-4df2-4c72-9193-d5ea684325ba/notebook/Notebook%201-ff9ba100ee414f2ab5dfee49f8f05310)
# Stage 1 - Discovery

> "Assess the available resources":
> 
  * Both Kaggle and Analytics Hub on BigQuery have datasets put together. I've decided to pull a dataset from BigQuery since it supports larger datasets, and       I'm able to access a multitude of other datasets if I so choose.
  
  [congestion dataset](https://console.cloud.google.com/bigquery?project=stalwart-topic-372019&ws=!1m18!1m4!4m3!1sbigquery-public-data!2scovid19_google_mobility!3smobility_report!1m4!4m3!1sbigquery-public-data!2scovid19_geotab_mobility_impact!3scity_congestion!1m3!8m2!1s969132371377!2s12eb8ac73aab45439c9e07cfdbb3e4da!1m3!8m2!1s969132371377!2s443349a901e64a429d62e942433449b0)
  
  [accident dataset](https://console.cloud.google.com/bigquery?project=stalwart-topic-372019&ws=!1m18!1m4!4m3!1sbigquery-public-data!2scovid19_google_mobility!3smobility_report!1m4!4m3!1sbigquery-public-data!2snhtsa_traffic_fatalities!3s%20accident_2020!1m3!8m2!1s969132371377!2s12eb8ac73aab45439c9e07cfdbb3e4da!1m3!8m2!1s969132371377!2s443349a901e64a429d62e942433449b0)
  
> "Frame the problem" (Describe the problem in my own words)

  * Traffic collisions are a cause of personal injury and financial hardship. 
  
> "Develop initial hypothesis"

  * Car accidents are less likely to occur during congested hours.
  
> "Identify potential data sources"

  * I found a BigQuery dataset from the nhtsa that recorded the number of accidents, causes, dates, times, and other details relating to car accidents; with datasets going back to 2015. 
  * Another dataset (listed above) showing congestion data during 2020.
  
> "Consider data ethics"

  * It's important to respect the persons that make up this data. They aren't just numbers, and every person has had their lives affected by motor vehicle collisions in one way or another. Peoples' privacy is also important to protect. Although this dataset doesn't give any names out, it's imperative to keep in mind in future projects. Transparency with collecting, analyzing, and explaining findings from data while not overstepping legal and business laws/rules are another way; though not limited to these examples, to exercise data ethics. *
  
# Stage 2 - Data Preparation
"Learn about the data, check for gaps, and identify datasets that may be useful"
 
> "Identify the data inputs for analysis and perform the migration"

  * Narrowed down both datasets to show what I need. Migrated results to deepnote. Dropped Mexico City from the congestion dataset and all but 7 in the accident dataset.
 
> "Prepare data for analysis - Clean data, normalize datasets"

![7_cities_accidents csv](https://user-images.githubusercontent.com/114529109/209414465-973b2cd7-e2a4-40e5-9886-0f3bfb27ed07.png)

![7_cities_cong](https://user-images.githubusercontent.com/114529109/209414469-5ebfde53-57c9-4412-ba97-b092fb848704.png)

Data cleaning in excel. Changed date formatting and city_name capitalization in both datasets, respectively. This helps python in combining the datasets.
![Screenshot 2022-12-26 135557](https://user-images.githubusercontent.com/114529109/210015659-6aa575ef-f762-472d-94b3-b672fe97e9b2.png)

![Screenshot 2022-12-26 135538](https://user-images.githubusercontent.com/114529109/210015668-786684c6-9da3-4216-9a8c-df06df033b4d.png)

# Stage 3 - Data Analysis
"Compare different models for the analysis"
"Identify models/techniques/tools to analyze the data"
"Ensure the analytical techniques will meet the project requirements"
"Execute the data analysis using models/techniques/tools identified"
# Stage 4 - Result Communication
"Create a set of presentation slides and insert graphical representations to show the results of the data analysis"
Present the project
