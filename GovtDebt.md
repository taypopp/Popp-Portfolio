## Government Debt

The following visualizations depict debt-to-GDP ratios for a variety of countries. The first visualization uses a bar chart, which is an effective way of showing how individual countries compare to each other. When placed in increasing order as shown, it is easy to see that Estonia has the lowest ratio while Japan has the highest. I also gave North and South American countries their own colors to show where this region stacks up in the rankings. The second visualization is a grid of line charts. This is a useful method for comparing trends, as the viewer will quickly identify differences in shapes of the lines. However, it is not as useful in comparing absolute values; when two grids are in different rows, it is not immediately evident how they differ on the vertical axis. The final visualization is a map. This visualization is helpful in understanding relative geographic trends. It's easy to see that Eastern European countries tend to have low ratios, Western Eurpean and North American countries tend to have moderate ratios, and Japan and Greece have unusually high ratios. This kind of visualization is not as useful, however, in comparing differences between individual countries.

All debt-to-GDP ratio data was obtained from the [Organisation for Economic Co-operation and Development](https://data.oecd.org/gga/general-government-debt.htm). Geographic data used for the third visualization comes from the default dataset for World Map on [Flourish](https://flourish.studio/). 

# General Government Debt of North and South American Countries, 2019

<iframe src="https://data.oecd.org/chart/6RZl" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6RZl" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

# General Government Debt by Country, 1925-2021

<div class="flourish-embed flourish-chart" data-src="visualisation/11688945"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# General Government Debt of Selected Countries, 2019

This visualization shows the debt-to-GDP ratio of available countries in a map format. I thought this would be a useful way to display the data because it allows the viewer to see any potential geographic trends in the data. To do this, I filtered the data to only those values from 2019, then I merged it with Flourish's default GEOJSON for a world map. 

I struggled with the popups; I was not able to disable popups for countries without debt data. I also struggled with the colors. Ideally, the diverging color scheme would have made its shift at 100%. This would distinguish between countries with less debt than GDP and those with more debt than GDP. However, I think the current color scheme is still helpful identifying those countries with the lowest and highest ratios. I chose a gradient from green to red because it shows a distinction between low debt-to-GDP ratios to high debt-to-GDP ratios. There is an argument to be made that debt is not necessarily good or bad, so perhaps a different color scheme would have been momre accurate; however, the current color scheme matches what most people probably think about debt, and therefore plays into the audeience's preconceived notions and understanding.

<div class="flourish-embed flourish-map" data-src="visualisation/11689205"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

[Return to Portfolio](https://taypopp.github.io/Popp-Portfolio)
