# TED TALK (1970-2022)
A Descriptive Analysis of TedTalks from 1970-2022 with Microsoft Excel

## Introduction
TED Talks are popular videos with subtitles in more than 100 languages featuring knowledgeable speakers on topics like business, science, technology, and creativity. This dataset contains 6 different features of each talk available on TED's website which consists;

	•Title - Title of the Talk
	•Author - Author of Talk
	•Date - Date when the talk took place
  	•Views - Number of views of the Talk
	•Likes - Number of likes of the Talk
	•Link - Link of the talk from ted.com


## Content
	1. Project Objectives: Problem Statement
	2. Data Sourcing
	3. Data Cleaning
	4. Findings 
	5. Data Visualization: Putting it all together

## 1. Project Objectives:
The project seeks to identify the;

	•Total number of Ted Talks over the years under review
	•Most sucessful Ted Talk per likes and views
	•Trends of viewership over the years under review

	
## 2. Data Sourcing
 The data set was downloaded via this [link](https://www.kaggle.com/datasets/daisyhart/tedtalk-dchallenger)

## 3. Data Cleaning
	The data was uploaded into Power Query in Excel,
	![tedtalk](https://user-images.githubusercontent.com/107724453/178152840-aa2b1fd4-fa84-4b5b-b187-dd5436ebb7dd.png)
![TEDTALK_TRANSFORMED](https://user-images.githubusercontent.com/107724453/178153659-949d4de2-401f-408b-8b21-428df8fb85e3.png)

	The data contained the date column - which was twice and transformed to obtain the Year and Month.
	The percentage of TED Talks that surpassed the 10 million views will also be vital to analysis. Thus, a calculated conditional column was created
	![views](https://user-images.githubusercontent.com/107724453/178336993-07e730f0-ca10-416e-9e0c-4e20c23d834e.png)
	
## 4. Findings
	A pivot chart was inserted to make the following analysis
	•Total TED Talks over the years =SUM(TEDTALK_DATA[TITLE])
	•Total Views =SUM(TEDTALK_DATA[VIEWS])
	•Total Likes =SUM(TEDTALK_DATA[LIKES])
	•Total Speaker = =COUNTA(UNIQUE(TEDTALK_DATA[AUTHOR]))

![header](https://user-images.githubusercontent.com/107724453/178351555-e4171487-9b45-4990-b321-c399d1a588b9.png)


A bar chart was used to visualize the Top 5 Viewed and Like Speakers. Here, Alex Gendler appeared the most viewed and liked speaker with 187 BILLION Views and 6M Likes.
	![image](https://user-images.githubusercontent.com/107724453/178349348-6b2a9e97-9c88-47a6-8a24-f15b0291d2aa.png)
	
A line chart was used to represent the Total Views Per Months and over the Years where we notice the month of February recording the highest views of 2 BILLION. Additionally, 2019 was the most popular year to record 1 BILLION views
	
![line](https://user-images.githubusercontent.com/107724453/178351339-323b33c7-8d1b-42a5-928a-8c241bb84b5d.png)

Another bar chart was used in representing the Top 5 viewed TED Talks where "Do schools kill creativity" receives the highest view of 72 Million. An analysis of of the TED TALKS that had above 10 million views was done and represented with a Waffle chart to conclude that 72% of all TED Talks surpassed the expected mark.

![wc](https://user-images.githubusercontent.com/107724453/178351481-6259a4f6-66cd-460a-be34-0de59c816521.png)

	
## 5. Data Visualization 
### Bringing it all together
![image](https://user-images.githubusercontent.com/107724453/178350451-81a772ec-6e86-4474-887c-7ca381d8185a.png)



	
	





	
	
	
