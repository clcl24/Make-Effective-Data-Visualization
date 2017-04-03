# Make Effective Data Visualization

**Li Cai**

### Summary

The dataset - baseball_data.csv contains 1,157 baseball players including balsball players' handedness (right handed, left handed,or both handed), height, weight, batting average, and home runs. Players' performance can be measured as their batting average and the number of home run, and their characteristics are handedness, height and weight.

Some observations from the final chart shows as below:

1. Smaller players are better at batting, especially for those heights that are lower than 76 inches. For the 67 inches height, players has highest batting average and highest home runs except for 67 inches height.

2. Medium players whose heights are 68 inches and 75 inches are more constant in their home run rates. Also, among these players, who are left handed seems like having higher batting average except for who are 69 inches height.

3. Left-handed players are better at both, batting and doing HRs. Both-handed plyesrs are not good at home runs except for height 67 and 76 inches. Right-handed players have lowest batting average compared to other two types of handedness.



### Design

##### First version

Initially, I tried to represent the relationship between batting, handedness, height and weight using a bar chart because it is easy to compare the differences by bar heights and colors. Y-axis will be the bating average, and handedness and height will be on the x-axis. Height will locate along the x-axis, handedness and weight will be distinguished by color. In addition, the bar chart will be named as Batting Average vs. Handedness.

#### Second Version

According to first friend's feedback, I improved my chart. First I removed the weight from x axis, and give the chart much
clearer naems of x label(Player's Height(inches)) and y label(Average of player's batting performance (avg)). And handedness was removed from x labels because it has a legend this time and can be clearer distinguished by colors.

#### Third Version

This time, I chose line chart to replace bar chart, because the relationship between batting average and height is clearer. What's more I used bubble to represent the Home run, the bigger bubble, the more home runs. Also, I add the grid to the chart, have the the grid it is easier to determine the location of the points in the chart.

#### Final Version

In the final version of this chart, I added the text to explain the plot, including what it is and what information it shows. Also, I adjusted the font style and color. I increased the width from '1400 - margin' to '1500 - margin', and increased the height from '600 - margin' to '1000 - margin' to make a clearer comparison between different handedness. Additionally, I resized the areas of bubble by reducing the radius of bubble to the square root of home run. That make the bubble's size more reasonable for actual home run number.

### Feedback

##### Friends 1 (version 1)

- There are numbers of bars in the chart, but they are actually in a mess, what information can be seen from it?
- What do the x label and y label mean? For example, only "avg" on y label? Does it mean the bating average? What's more, the title of chart is confusing as well.
- Why does x axis has three parameters? Removing the weight or height maybe has a better result because they are supposed to be positively correlated.

#### Friends 2 (version 2)

- The handedness is clear because of color but the bar chart cannot demonstrate the relationship directly.
- There are another data "HR" in the dataset, why the chart don't reflect this? It can tell the performance of the player, so add it to the chart is a good option.

#### Friends 3 (version 3)

- The chart looks like good, the relationship can be found from the plot, but the line of different handedness are a little bit close, if the gaps between them can increased, the comparison will be easier and more straight.
- In addition, some comments of the plot can be added to explain the what you want to show.

## Resources

https://github.com/PMSI-AlignAlytics/dimple

http://dimplejs.org/

http://htmlcolorcodes.com
