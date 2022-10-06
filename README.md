# School District Analysis

## Overview 

This analysis was conducted to support Mari, the chief data scientist for a city school district.  The purpose is to present the performance trends and patterns of students in the district.  

## Analysis 

The analysis was processed based on the dataset in csv format, and it contains all standardized test results including the school budget as well.  Additionally, the schools were categorized by types, public and charter. 

In the data cleaning process, the null values in both reading and math scores were found and removed in the csv.  Data type on the grade was converted from object to integer which made the further analysis be easier.    

- null values found 
    reading_score    1968
    math_score        982

- duplicate values found 
    1836

Analysis/jupyter notebook is [GitHub Pages](https://github.com/tomoko1T/School_District_Analysis)

## Summary 

This analysis is a good start to find out how to analize the dataset of the performance trends and patterns of students in the district.  Interestingly, the average of the school budget on the charter schools is lower than the one of the public schools.  This may tell the reason why the math score on the charter shools deteriorates as the grade level increases while the performance on the public schools is relatively stable on each grade.

Although the analysis reveals good insights of the schools' performance, it still picks only pieces of the information.  It is not enough to detemine which school's performance is betther than others.  The summary statistics of each school could be beneficial to find out which school's performance is outstanding.  Their success can lead to improve other schools' peformance as well.  



