# An Analysis of Kickstarter Campaigns.

## Background

In this project, we will analyze the kickstarter campaign data. The objective is to determine:

* Which campaign categories and subcategories are more successful than others
* Discover any other attributes affect the campaign outcomes such as:
  * Geographic location
  * Campaign start month
  * Goal amount
* Analyze the data by calculating descriptive statistics and draw inferences.
* Visualize the data to discover trends.

## Approach to analyzing the kickstarter campaign data

The first analysis is to uncover the impact of a campaign's start month on its eventual outcome (successful or otherwise).

We make the following observations on this campaign data:

* A campaign is successful if the pledged amount is greater than or equal to the goal amount.
* Campaigns are run in many forms (such as theatre, music and television) and each form has further subcategories. Moreover, campaigns are run in many countries. All these factors could contribute to the eventual outcome of a campaign.
* Overall, there are a total of 4113 campaigns. Each campaign has the following important attributes which could potentially impact its outcome:
  * Location
  * Category
  * Subcategory
  * Goal amount
  * Launch date
* This is not a large data set to analyze. Excel is a perfect tool to run analyses. For this data set, not many potential difficulties were encountered.
* In general, the following difficulties could arise while analyzing data:
  * **Scale** - many data sets have billions of rows and thousands of columns. Not only it is hard to run quick analyses, it is not even clear which columns are useful.
  * **Lack of clean data**: Many a times, several data points are missing or invalid. Before running any analyses, a program must remove all rows consisting of invalid data points.
  * **Outliers**: If the data set has many outliers, data analysis inferences could be wrong. A program must remove all rows consisting of outliers.

## Analysis one - outcomes for Threatre by launch date

In this analysis exercise, we considered only the **Threatre** campaigns. We want to determine if the **Launch Date** of the Threatre campaigns influences their outcomes.

* First, we constructed a pivot table in which we counted all possible outcome values for every month. 
* Then, we plotted those outcome results for every month as a **line graph**. The graph is shown below.

![image_name](Theater_Outcomes_vs_Launch.png)
