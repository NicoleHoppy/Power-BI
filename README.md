# Power-BI

This repository will contain the Power BI project of Netflix dataset from [kaggle.com](https://www.kaggle.com/datasets/shivamb/netflix-shows)

# Abstract

Without questioning, Netflix is one of the most popular platform for video streaming. The dataset of Netflix production is great to visualise and analise the data. In this project I will create analysis of Netflix dataset. 

# Table of Contents
1. [Looking into data in Excel](#introduction)
2. [Cleaning data](#cleaning)
3. [Power BI Analysis](#analysis)
4. [Results](#results)
5. [Conclusions](#conclusions)

<a name="introduction"></a>
## 1. Looking into data in Excel

In this project I am using dataset provided by website kaggle.com (https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download).

Firstly I wanted to look into dataset. In order to do that I opened the Excel file and went to Data > Get & Transform Data > Get Data > From Text/CSV. Then I got the following:

![CSV opened in Excel](Images/01_image.png)

I have table with 12 columns that contains the following informations:

- show_id
- type 
- title 
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

When we look into data we can see some issues that we will need to take care of. But we are not working on original datatset. Every modification will be made in Power BI. We do it that way because we do not want to destroy original dataset.

Now I upload the Excel file into Power BI and intead clicking to load data, I chose to transform data. I want to make some modifications to the original data before starting working with data.

![Excel opened in Power BI](Images/02_image.png)

Looking into data we can see that the first row is not considered as header so we can click on Home > 
