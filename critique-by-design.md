| [home page](https://pkraikhun.github.io/tswd-portfolio-pkraikhu/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment 3&4: Critique by design

## Part I:
[World Investment Report 2010](https://unctad.org/system/files/official-document/wir2010_en.pdf) - Page 15
<p align="center">
<img src="critique-by-design-original.png" width="800"/>
</p>

I went through World Investment Report 2010 and found this visualization with two 3d pie chart. The visualization shows the proportion of sovereign wealth funds (SWF) foreign direct investment in various sector in Y2007-2008 and Y2009-2010. 

## Part II: Critique the data visualization
The visualization is critiqued according to Stephen Few's Data Visualization Effectiveness Profile on following criteria:
-	Usefulness: 10 – The data provides information on percentage of sovereign wealth fund investment in each sector for two period reflecting the changes in proportion of the investment. 
-	Completeness: 10 – The visualization includes the right amount of data. The goal is to see changes in proportion of the FDI in two time periods. Therefore, data in level of percentage of each category is appropriate. 
-	Perceptibility: 5 – the color along with pattern used in the chart is distracting. Without looking at the value label, pie chart area is difficult to grasp. The additional 3D effect makes it even harder to compare each category of investment. Even though color and texture is used to differentiate between sectors, the position of each piece changes which takes more eye travel for audiences to notice changes. In short, looking at the pie charts, audiences do not get the message they are trying to convey right away.
-	Truthfulness: 6 – The title and footnote also make it clear that information in 2010 only available up to May. Additionally, footnote also mentions the assumption used in the calculation which makes it clear to the audience. However, the point is deducted here for the 3D effect that makes some pieces look unproportionally bigger than the other with similar value. For example, mining, quarrying and petroleum in 2009-2010 with value 26% appears much bigger than the same sector with value 20% in 2007-2008. 
-	Intuitiveness: 10 – Pie chart is quite intuitive and easy to understand despite the texture and colors used.
-	Aesthetics: 4 – The choice of color as well as the texture is not aesthetically pleasing.
-	Engagement: 6 – Texture distracts the audiences from the information presented. However, the audiences can still see and understand the data.

## Part III: Sketch out a solution
The data is copied from the two pie charts and put into csv file. Then, I started sketching some ideas for potential visualizations. The first candidate is bar chart as it could reduce the eye travel when comparing the different between FDI in two period. The clustered vertical bar chart is colored as year indicator and each cluster represents a sector. The length of bar is easier to ccompared than the area in pie chart, but it still doesn't show the changes in some sectors. There are some sectors which started off very high and went to 0 (i.e. Finance). The bar chart does not highlight this fact which can be a disadvantage in conveying the message. 

<p align="center">
<img src="critique-by-design-v1.png" width="600"/>
</p>

The next candidate for visualizing this information is the stacked horizontal bar chart. Both bars have the same length making it easier to understand that the changes are in the proportion of each sector. The color also helps to point out the same category to compare. However, the reader has to go to the legend on the right to read out the sector name and the chart is still cannot highlight the change from 36% in finance sector to 0. 

<p align="center">
<img src="critique-by-design-v2.png" width="600"/>
</p>

Finally, I picked the slope chart as the visualization of choice. As can be seen from the slope chart below, it is intuitive in terms of changes from period 2007-2008 to 2009-May2010. The draft here still needs color adjustment to highlight the sharp decrease of “finance” sector and the increase in “Mining, quarrying and petroleum” and “Motor vehicles and ither transport equipment”. 

<p align="center">
<img src="critique-by-design-v3.png" width="500"/>
</p>

## Part IV: Test the solution

After selecting the type of chart, I adjust colors and format to make it cleaner. The category names are only shown on the right side of the bar instead of both sides while the data label is shown on both sides for clarity. The colors are also adjusted to highlight the two main increasing categories in green and the one sharp decrease in red whereas the rest are grey. The title is named "SWFs shift their FDI from financial sector to transportation and electric sectors" to summarize the information on the visualization while all the data are provided.

<div class="flourish-embed flourish-slope" data-src="visualisation/15011826"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

The visualization is shown to two friends who provide me with their critique on the chart.

Friend 1: It took her sometime to figure out the meaning of the topic as she does not have expertise in economics, particularly the accronym. After some context about the SWF and FDI, she thought the chart highlight the information on the change well. However, it took her a while to notice the year lable of the axis. She also mentioned that the slope chart was not very familiar to her. Apart from that, she had some comment on the shades of color green that is used to differentiate the chart. It was too dark and appered more black. Lastly, She recommended adjusting the size of the sector legend.

Friend 2: She also faced the same problem of not understanding the SWF and FDI concept. She recommended adding subtitle to provide more clarity. She mentioned that the visualizaion aligns with the normal eye-travel pattern - from left to right. With label on the right hand side makes it not redundance. However, she expressed concern as using green-red color pair not only symbolize increase-decrease, but also good-bad. Hence, it would be better to pick some color that does not provide that impression. Additionally, the shade of grey used is also a little bit too dark making the whole visualization seems busy.

## Part V: Build your solution

<div class="flourish-embed flourish-slope" data-src="visualisation/15038109"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

The final visualization is revised according feedback and critiques. The color scheme used is blue-orange which is more neutral than green-red which could imply the good/bad meaning. Additionaly, the color of other lines are adjusted so that it wouldn't be distracting to the reader. The full information is also available as a pop-up text box when clinking or hovering over the lines. Apart from that, the title is adjusted to reflect the information presented and subtitle is added to provide more context to the reader who might not aware of the accronym. This way, the visualization could stand on its own without much context, unlike the original one which accompanied by a paragraph of text. The subtitle is cited from the original report to ensure the accuracy of the analysis. Overall, the slope chart captures the change in proportion of FDI that SWD made over two periods well. With the use of colors (blue-orange and grey), the information stands out making it easier for the reader to grasp the message that the visualization is trying to convey. 

