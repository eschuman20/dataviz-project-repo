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

The first visualization is a scatter plot that can be modified to show the relationship between two stats (specified using the menu's above the plot) for a given year. A user can hover over a circle to see the name of the player and also filter the plot by league by double clicking on a league in the chart's legend. This plot was originally created to answer the question of "Which players are most efficient in scoring goals?" by visualizing the goals vs shots, but with the menus other statistics can be explored. 
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/scatter_plot2.png)](https://vizhub.com/eschuman20/scatterplotwithmenus)

The second visualization is a bar chart of the top 5 players in a specified league and year. Different statistics, leagues, and years can be explored using the menus. This chart was orginally created to answer the question of "Which players have scored the most goals?" but can be utilized to answer many other questions related to other stats. 
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/bar_chart_2.png)](https://vizhub.com/eschuman20/a8852f0040ea442181e2beb970e5e7e4)

The third visualization shows player statistics over time. Each line in the chart represents a different player, with the x axis showing different years and the y axis representing the performance of a player for a given statistic. The y axis can be modified using the menu at the top of the graph to display different statistics. Additionally, when a user hovers over the line, a tooltip reveals the name of the player. This visualization answers the question of "How have player statistics changed over time?"
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/line_chart.png)](https://vizhub.com/eschuman20/goalscorersovertime)

The last visualization is a parallel coordinates plot. This plot 
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/Parallel_Coordinates_2.png)](https://vizhub.com/eschuman20/topfootballscorersparallelcoordinates)


## Dashboard

Here is a dashboard of the four viz's together:
[![image](https://github.com/eschuman20/dataviz-project-repo/blob/master/dashboard.png)](https://vizhub.com/eschuman20/footballscorersdash)

## Midterm Reflection

So far I have created all four of the viz's I would like in my final project. While they are all working properly on their own I would like to combine them in one viz, so a user can view and interact with all of them at the same time. This is what I plan to prioritize with for the rest of the course. In addition, there is some fine tuning I can do to make the visuals more visually pleasing, such as editing the column names to make them more readable. 

## Open Questions

At the moment my main concern revolves around how to connect the visualizations so that if you click on one, it will cause the others to change. 

## Milestones

Week 12: Add interaction across viz's
Weeks 13-14: Final testing and fine tuning
