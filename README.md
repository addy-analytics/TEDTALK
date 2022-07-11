# TED TALK (1970-2022)
A Descriptive Analysis of TedTalks from 1970-2022

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
	4. Findings and Data Visualization

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

	
	
	
