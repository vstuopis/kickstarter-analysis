# Kickstarter Results Analysis

## Overview of the Project

### Purpose of this Analysis
We use this analysis to help Louise understand how project launch dates and their funding goals impact how well they do. We take a deeper look into the monthly breakdown of theater campaigns and their outcomes. Also, we review various goal segments based on the subcategory of Play.

## Completed Analysis and Challenges Faced
    
### Analysis of Outcomes Based on Launch Date
With the use of the Years function, **=YEAR()**, we are able to take the Date Created Conversion column and separate it out to obtain just the year value. We added the filters of Parent Category and Years to our pivot table along with filtering out live outcomes in our Column Labels. Our rows display the months of the year allowing us to see all of the outcomes for the theater Parent Category by month. 


### Analysis of Outcomes Based on Goals
With the use of the countifs function, **=COUNTITFS()**, we are able to add filters to our table without needing to add an actual pivot table. For the number total projects by goal range, rather than adding the 3 previous columns together we utilized the sum function, **=SUM()**. With the data we have, putting it into the line chart is an easy way to visualize how the Kickstarter Outcomes change as the Goal amounts increase.  


### Challenges and Difficulties Encountered
One of the challenges someone may face is being able to create the months in the Rows for the Theater Outcomes by Launch Date analysis. One can overcome this by either researching in Microsoft Excel documents on how to create these values in a pivot table or by trial and error using different combinations of table headings.

## Final Results

* What are two conclusions you can draw about the Outcomes based on Launch Date?
  - From our analysis, we can see that May and June by volume had the most successful theater campaigns. December was the most difficult month for theater campaigns as over 50% of them were not successful.

![Theater_Outcomes_vs_Launch](https://github.com/vstuopis/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

* What can you conclude about the Outcomes based on Goals?
  - The highest percentage of successful projects were those with goals of less than $1000 while by volume it was those between $1,000 and $4,999. There were only 42 projects with a goal more than $25,000 however 71.4% of them failed to reach their goal.

![Outcomes_vs_Goals](https://github.com/vstuopis/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

* What are some limitations of this dataset?
  - One limitation of the dataset is that we do not have information on if a project being a Staff Pick or a Spotlight impacts the amount advertising or outreach a Kickstarter gets. Another limitation of the dataset is that it doesn’t break down the subcategories any further which may leave trends undiscovered. 

* What are some other possible tables and/or graphs that we could create?
  - We could create an additional table to look at the outcomes based on the country of the project. This type of analysis would help Louise see what countries may be areas of expansion in the future. We could also create a bar graph to take a look at various funding lengths based off Parent Categories with a Subcategory filter. This will allow Louise to see how long these various campaigns have to reach their goal. 
