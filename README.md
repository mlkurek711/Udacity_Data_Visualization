# Udacity_Data_Visualization

# Summary
I chose the baseball dataset provided by Udacity to create two visualizations using d3 and dimple.  The datatset contained 1157 players with their batting side (handedness), height, weight, batting average, and home runs.  Since height and weight had a positive correlation I used just height to explore any correlation with batting average and then with homeruns.  I also explored batting side with batting average and homeruns.

# Design
I made the bar-bubble chart for height vs averages of batting average and home runs, but it did look weird as was commented in the feedback.  
I added dots to the batting side vs batting and home runs chart as it was commented the line alone got lost in the bar charts.
I found it interesting that two people thought the batting average difference between right-handers and the rest was significant while one did not, yet all noted the difference in homeruns.  I agreed with the two in my summary at the top of the page that right-handed hitters batting average was lower according to the chart.  I'm not sure how to make that more clear.
Comments were made about how many people make up each group on the x-axis.  I felt like adding any more numbers to the x-axis would make it difficult to read, and changing the bar width might not be intuitive considering I'm already using size for the home run bubbles.

# Feeback
I used the questions provided by Udacity to get feedback on my visualizations.

Person 1
What do you notice in the visualization?
By providing a visual representation, it allows me to notice both non-intuitive relationships in data as well as how each data point fits in to the other data. An example of this with number of home runs represented by circle size in the Batting Average/Home Run vs Height chart.

What questions do you have about the data?
What is the size of each discrete value in the x-axis of each chart?

What relationships do you notice?
In the left chart, the Number of Home Runs can be broken down into 4 groups with multiple heights: small (77in and 80in), medium (66in, 68in, 79in), large (everything left minus 67in), and then huge (67in). The "huge" group is the only instance with one value. Also on the same chart, there is a noticeable drop in Home Runs with players over 74in tall.
The right chart indicates that hitters whom are only right-handed have a remarkable drop in batting average.

What do you think is the main takeaway from this visualization?
Physical attributes such as height and batting side make a difference in player performance.

Is there something you don’t understand in the graphic?
No, I understand everything about the graphic.

Person 2
What do you notice in the visualization?
I have never seen data represented as a circle over a column. It was not intuitive. In the second chart, the line data is lost in the large columns.

What questions do you have about the data?
The number of home runs are not indicated in the first graphic, so my question would be with regard to scale. How many home runs are depicted?

What relationships do you notice?
In the first graphic, I notice that above 74 inches height, batters aren’t as good and home runs peak dramatically at a height of 67 inches. (which is a joke since I’m 67 inches and can’t bat for squat) In the second graphic, I see that batting average is pretty much unaffected by which side batters hit from, but home runs are higher for left hand hitters compared to right, and switch hitters do the worst.

What do you think is the main takeaway from this visualization?
There are strong correlations between height and batting performance, but not between left and right hand batting and batting performance.

Is there something you don’t understand in the graphic?
No

Person 3
What do you notice in the visualization?
There appears to be a significant correlation between a players height and there batting average.

What questions do you have about the data?
What the time frame that the data is pulled from?
Is there much of a difference in the results of say players in the 50's verse players in the past decade?
What does the data look like when you take out the high and low outliers? 

What relationships do you notice?
A player's height seems to have a connection to a player's batting average 

What do you think is the main takeaway from this visualization?
A player's height can be used to get a general idea of how that player's batting average may be.

Is there something you don’t understand in the graphic?
What could cause the difference in home runs between left and switch hitters  if the rating stays relativity that same? Could it be a few outliers throwing the average off or could it be that when a right handed hitter hits with the left to get an advantage over the pitcher that they are not as strong so cannot get the distance to make a home run?

# Resources
I Googled for other examples of the data visualization and found another's project to be extremely helpful with mine as I was looking for similar correlations.
http://bl.ocks.org/rgilredondo/4580cf3269e5461efb866d47a6e94c4c
