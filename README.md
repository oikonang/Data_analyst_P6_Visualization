# P6---Visualization
Dimple.js and D3.js project

## Summary
When trying to compare survival rate between genders for the Titanic disaster, females had more chances to survive compared to males. As far as the socio-economic status of the passengers, those travelling in 1st class were more likely to survive than those travelling in 2nd class, which inturn were more likely to survive than 3rd class passengers. Children and Adult (< 40 years-old) passengers were more likely to survive compared to the rest age groups.

## Design
The number of peolpe survived and the gender of the passengers are the two most important information in the dataset, so they were included along the y and x axis respectively. I chose "sex" to plot along the x-axis, so that the viewer can easily differentiate between the number of passengers surviving in each group. As far as the plotting is concerned, a bar chart, was the ideal solution as "sex" is a categorical variable and survival rate is a continuous variable.

A third feuture which was equaly valuable as the rest, was "age_group" which has been added in the plot as well. As a categorical variable, this feauture was encoded it using the color hue, in order to facilitate the viewers' percpective. A legend has been added as well on the top of the chart.

A fourth variable "Pclass" which represents the socio-economic status of the adequate customer, has been added to the plot as well. This feature has been integrated with animation and automatic rotation upon a prompt of a user, who can switch between each class using the navigation link provided in the slide.

I also modified the tooltip provided by dimple to show the percentage of different age groups people surviving in each category. I included a title and some text at the right bottom of the graph to give an overview to the users about what the graph represents.

After been provided with some feedback from frinds and coleagues concerning the graph, I made some changes. I eliminated null values, I gave real names to the age groups, I changed the legends of the plot in order for the viewer to have a better understanding of the context without spending a lot of time, I used aggragate node grouped by two consecutive variables in order to i.e. subgroup the survived males of 19-40 years-old, I tuned the D3 attributes to have the best possible visualization, and I eliminated the grid lines to make good use of white spaces.
In addition after the first Udacity review, I fixed some code indentation styling issues, I fixed a miscalculated variable (survival rate) on the data and lastly I fixed the bar ordering according to labels.

## Feedback
Andreas Grivas: I spent a lot of time to understand the story beneath this visualization. Try to change the legends and titles to for an more accurate first impresion.

Christina Ikonomaki: I suppose that age group 1, 2, 3 and 4 are ascending groups of 20 years each. Put a legend on these.

Dimitris Mantrokas: Try to eliminate any possible null values and make use of the minimal style of white spaces. 

Udacity 1st Review:  
What do you notice in the visualization?
Sort age groups in the visualization same way as it is in the legend. Currently there are children and adults groups switched.

What questions do you have about the data?
The visualization centers on specific finding in the data, however, I have to mark this section as requiring changes because there is some error in the data.

What do you think is the main takeaway from this visualization?
Nice animation and tooltips.

The code uses formatting techniques in a consistent and effective manner to improve code readability?
I marked several places where improvement needed in code review. Consider reformatting according to code styling recommendations.

## Resources
https://www.kaggle.com/c/titanic
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
http://www.w3schools.com/css/default.asp
https://github.com/mbostock/d3/wiki