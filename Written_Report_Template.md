# Kickstarting with Excel

## Overview of Project
-Louise’s play, Fever, came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns performed in relation to their launch dates and funding goals. 


## Analysis and Challenges
-[Kickstart_Challenge copy](path/to/Kickstart_Challenge copy.xlxs)

### Analysis of Outcomes Based on Launch Date
-In order to visualize the campaign outcomes ("successful," "failed," and "canceled") based on the launch date, I first extracted the year from the “Date Created Conversion” column using the YEAR() function. 
-![image1](path/to/image1.png)
-Next, I created a Theater Outcomes by Launch Date pivot table and filtered the "Parent Category" to show only the data for "theater."
-Then, I sorted the campaign outcomes in descending order so "successful" is first.
-![image_name](path/to/image2.png)
-Next, I created a line chart from the pivot table to visualize the relationship between outcomes and launch month.
-![image_name](path/to/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
-In order to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount I collected the outcome and goal data for the “plays” subcategory.
-In the “Goal” column of the table, I created dollar-amount ranges so projects can be grouped based on their goal amount.
-Then, counted the number of successful, failed, and canceled plays in each dollar range.
- After that I found the total number of projects in each dollar range in order to find the percentage of successful, failed, and canceled plays in each dollar range.
-![image_name](path/to/image3.png)
-Then I created a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges and the percentage of successful, failed, or canceled projects.
-![image_name](path/to/Outcomes_based_on_goals.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	-Overall, there have been more successful theater campaigns than failed campaigns. The most successful launch dates are in the summer with May having the most successful campaigns. The amount of failed campaigns and successful campaigns follow the same trend. 

- What can you conclude about the Outcomes based on Goals?
	-The theater campaigns with goals of $45,000+ have the highest percent of failed campaigns. Theater campaigns with goals in the range $1000-$4999 and under $1000 have the highest percentage of successful campaigns.

- What are some limitations of this dataset?
	-

- What are some other possible tables and/or graphs that we could create?
	-
