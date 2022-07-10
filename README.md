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
 The data set was downloaded via this [link]

##3. Data Cleaning
	The data was uploaded into Power Query in Excel,
	![tedtalk](https://user-images.githubusercontent.com/107724453/178152840-aa2b1fd4-fa84-4b5b-b187-dd5436ebb7dd.png)

	The data contained the date column - which was twice and transformed to obtain the Year and Month.
	The engagement rate of Ted Talks will be helpful to our analysis, thus, a a customized column was created with the formula = [LIKES]/[VIEWS]*100
	![TEDTALK_TRANSFORMED](https://user-images.githubusercontent.com/107724453/178153408-adc8c6d3-fd6c-46e3-a363-857b9cbb691a.png)

