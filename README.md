How Fertility rates affects the ranking of the most populated countries of the world (1960-2050)
-----------------------------------------------------------------

### Summary

This visualization is the representation of how the fertility rate of the countries affects their ranking based on the population. Here fertility rates and ranking of all the countries who were, who are and who will be in top 10 between 1960-2050 are represented. This also gives us the complete picture about how some countries with very high fertility rates for longer period of time and how some countries moved down the ladder due to low fertility rates.

Countries like Nigeria, Ethopia, Pakistan and Philippines with high fertility rate for decades climb up the population ranking. Also countries like UK, Japan, Germany and Russia with low fertility rates for decades go down the ladder. Its really amazing how some of the world powers go out of the top 10 and how some of the poor-developing  countries move up. With majority of the developed countries going gray, its really a very good data set to give us insight on one of the causes which is causing this decline in the population growth in the countries which used to be among the highly populated countries. 


### Design
After getting the feedback for the last submission of Population pyramid which was as pointed out was more of exploratory. In order to make it explanatory I had to show what was causing the change in the movement of the countries up and down the ranking. I started looking for the cause which was playing very important role.  Fertility rates is one of the leading causes of the population growth of any country. So decided to show how the ranking of the countries depending on the fertility rates. 

Now I have to show the ranking and fertility rate in the same chart for each country. Initial thoughts were to have two charts. One bar chart with the ranking and other line chart for the fertility rate. But with two different charts it will be very difficult to compare how one affects the other. I needed a way to show both the charts in the one single chart. 

1) Decided to create on chart with two y axis 
2) One y axis for the fertility rate and other one for ranking.
3) Bars were selected for ranking as it is more of a categorical value
4) Line chart selected for fertility rates as wanted to show the trend.
5) Different colors were selected for each as should differentiate from each other. Each represent different parameter.

Made some changes after the initial feedback from friends:

1) Added a legend for the country attribute to highlight which country is being shown.
2) Allowed Users to stop and start the animation. This should help the users to view the visualization for each country in more detail.
3) Added another legend which shows what represents ranking and what represents fertility rates.

### Feedback

Feedback for index1.html:
1) Too many graphs in one view
2) Too small to follow
3) Even though it conveys the information about each country's rank and fertility rate it looks too clumsy

Improvements made based on the feedback:
1) Removed all charts in one view and added only one chart for one country at a time
2) Added animation to display one chart at a time.

Feedback for index2.html:
1) It is difficult to follow which country visualization is being displayed
2) Color of the bar is too light and difficult to follow the change
3) There is a relationship between fertility rates and ranking.
4) There should be a way to stop the animation and view the visualization for each country.

Improvements made based on the feedback:
1) Changed the color of the bars to blue.
2) Changed the color of the line to kind of maroon.
3) Added a legend for the country attribute to highlight which country is being shown.
4) Allowed Users to stop and start the animation. This should help the users to view the visualization for each country.

Feedback for index_final.html:
1) Layout of the chart with the details of which country chart is being displayed is very nice.
2) Having option to stop and start the animation is very good way of allowing to view the chart for each country in more detail.
3) The details displayed when hovering over the bars and line gives more information of the actual data values.
4) With bars and lines chart displayed together, it is very easy to understand how the fertility rates impacts the ranking of the country.


### Resources
* http://www.worldometers.info/world-population/ - Data Source
* http://d3js.org/
* http://dimplejs.org/
* http://dashingd3js.com/
* http://alignedleft.com/
* http://animateddata.co.uk/articles/
* http://www.censusindia.gov.in/
* http://code.tutsplus.com/
* http://adilmoujahid.com/
* http://www.visualisingdata.com
