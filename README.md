# Data Visualization Project

## Data

The data I used for my project came from the Top Football League Scorers dataset. This dataset has player statistics including goals, shots, shots on target and games played for the top football goal scorers across a variety of leagues from 2016 to 2020. 
Dataset: [Top Football League Scorers](https://www.kaggle.com/datasets/mohamedhanyyy/top-football-leagues-scorers)


## Questions & Tasks

After examining the data, I developed several key questions to drive the visualization and interaction decisions for the project. These questions included: Which players have scored the most goals? Which players are most efficient in scoring goals (more goals with less shots)? How have the statistics of players changed over time? What leagues have the highest goal scorers?

At first, I was mainly focused on creating visualizations related to the goals statistic. As I learned more about interactive visualizations, I found that I could offer a user views of many other statistics with the same charts using a menu. This allowed for exploring and visualizing other stats available in the dataset. 

## Sketch

The first step in my project was to sketch an outline. In my sketch, there were four visualizations all connected to each other through interaction. A menu existed on the side to show different statistics on the graphs (for example change from goals to shots on target). There were also menus to filter by year and league. 
![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/outline_2.png)


## Visuals

I created each of my visualizations separately at first, before combining into one final dashboard at the end. 

The first visualization is a scatter plot that can be modified to show the relationship between two stats (specified using the menu's above the plot) for a given year. A user can hover over a circle to see the name of the player and also filter the plot by league by double clicking on a league in the chart's legend. This plot was originally created to answer the question of "Which players are most efficient in scoring goals?" by visualizing the goals vs shots, but with the menus other statistics can be explored. This plot also answers the question of "What leagues have the highest goal scorers?" as the color of the circles indicates the league. 
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/scatter_plot2.png)](https://vizhub.com/eschuman20/scatterplotwithmenus)

The second visualization is a bar chart of the top 5 players in a specified league and year. Different statistics, leagues, and years can be explored using the menus. This chart was orginally created to answer the question of "Which players have scored the most goals?" but can be utilized to answer many other questions related to other stats. 
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/bar_chart_2.png)](https://vizhub.com/eschuman20/a8852f0040ea442181e2beb970e5e7e4)

The third visualization shows player statistics over time. Each line in the chart represents a different player, with the x-axis showing different years and the y-axis representing the performance of a player for a given statistic. The y-axis can be modified using the menu at the top of the graph to display different statistics. Additionally, when a user hovers over the line, a tooltip reveals the name of the player. This visualization answers the question of "How have player statistics changed over time?"
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/line_chart.png)](https://vizhub.com/eschuman20/goalscorersovertime)

The last visualization is a parallel coordinates plot. This plot allows the user to compare players across several different stats that can be changed using the menus. The user can filter the stats to certain ranges by dragging on the plot. Additionally the plot allows users to compare stats across leagues through the plot's legend.
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/Parallel_Coordinates_2.png)](https://vizhub.com/eschuman20/topfootballscorersparallelcoordinates)


## Dashboard

To combine all of the visuals into one nice interactive visual, a dashboard was created. The dashboard was split into four quadrants, with one for each visualization. At the top of the dashboard there are four menus. The first menu is used to change the y-axis on the scatter plot, line chart, and bar chart. The second menu is used to change the x-axis on the scatter plot (the x-axis for the line chart will always be "year" and the x-axis for the bar chart will always be "player name." The third menu can be used to alter the year. This menu alters the scatter plot, bar chart and parallel coordinates plot as the data for each of those visuals is filtered by year. The fourth menu enables the user to change the league for the line and bar charts. These charts are filtered by league, while the other two visuals show all leagues.  
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/dashboard.png)](https://vizhub.com/eschuman20/footballscorersdash)
