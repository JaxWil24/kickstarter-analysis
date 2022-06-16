# Kickstarting with Excel

## Overview of Project :

### Analyzing the relationship between outcomes of the kickstarters for "theater," and "plays," subcategory, their goals, and when they were launched. By creating graphs, these specific categories are able to be evaluated in detail.

## Analysis and Challenges :

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106329824/173353629-82796305-8a24-4ae2-aef0-209c07c5dfd4.png)
- Using a pivot chart to organize information, I ended with this line graph for a quick rundown of launch date and how successful the kickstarter was.
- Organizing the numbers by month helps us to see the day the kickstarter began and where they ended up.
- We see the month for highest failed outcomes is tied, July and October. We also see November was the lowest failed outcomes.
- The number for canceled kickstarters was so low, it ended being less than 3% of the final numbers for all theater kickstarters.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106329824/173354147-b690c349-edef-452f-8ada-3e4c184fe51d.png)
- Using a line chart, we are able to see the relationship between the outcomes and the month.
- Using the COUNTIFS formula, we are able to identify what kickstarters in the play subcategory falls into the specific goal ranges.

### Challenges and Difficulties Encountered
For Outcomes Based on Launch Date, piecing together where to move the fields to the correct areas of the chart was difficult for me.

For Outcomes Based on Goals, I had trouble with the COUNTIFS formula. It took me a little longer than I feel it should have to create the formula. I had trouble piecing together what goes into it, specifically the second part to the range. Adding the equal sign for 'greater than or equal to' allowed me to have a more accurate reading.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

After analyzing the data on the theater outcomes, I've come to the conclusion that if the kickstarter is going to be canceled, it will most likely be in January. Another consclusion I have is that the month of May is a popular launch time, possibly in correlation with being the end of winter and the start of a new season. 

- What can you conclude about the Outcomes based on Goals?

Seeing the goal range of $1,000-$4,999 73% successful, and the range $1,000 or less is 76% successful, I believe if someone were to start a Play kickstarter it's best to set a goal of under $5,000.

- What are some limitations of this dataset?
Analysing the Theater Outcomes based on Launch Date and Play Outcomes Based on Goals, you can not see what genre was most successful or the correlation of the audience in which they are trying to make sales. For example, a childs theater performance, who donated the most? Or for dramas, was the intended target audience the ones who were supporting the kickstarter?

- What are some other possible tables and/or graphs that we could create?
We could make a pivot chart to analyze what category or subcategory was the most popular for each year or month.