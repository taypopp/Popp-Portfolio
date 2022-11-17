## Original Visualization

While scrolling Twitter, I saw a [tweet](https://twitter.com/ECONdailycharts/status/1589981363666558977?s=20&t=Bb6CQG6eA0rLbPP7uwkYBA) from The Economist Data Team (@ECONdailycharts) from November 8, 2022:

![tweet](https://taypopp.github.io/Popp-Portfolio/tweet.jpg)

I followed the link in the tweet to an article from The Economist from November 7, 2022: [Meta will lay off 13% of its workforce](https://www.economist.com/graphic-detail/2022/11/07/meta-will-lay-off-13-of-its-workforce?utm_medium=social-media.content.np&utm_source=twitter&utm_campaign=editorial-social&utm_content=discovery.content&%3Ffsrc%3Dscn%2F=tw%2Fdc). This article showed a different version of the visualization:

![viz](https://taypopp.github.io/Popp-Portfolio/viz.jpg)

There is a lot going on in this visualization. The vertical axis represents different industries under the tech umbrella and the horizontal axis represents time as months in 2022. Each circle represents a company, and the size of the circle represents the number of 2022 layoffs that have occurred. The company is placed on the time axis based on the most recent layoff date, but the size represents all 2022 layoffs, regardless of date. 

The source of this data is [Crunchbase](https://news.crunchbase.com/startups/tech-layoffs-2022/). The data has been updated since The Economist article was written, and Amazon surpassed Meta in layoffs on November 14.

### Where It Went Wrong

I chose this visualization because, while the information being conveyed is interesting, there is too much information in the visualization that is not relevant to the main point. The point of the article is represented in the title: "Meta will lay off 13% of its workforce." The point is the highlight high rates of layoffs in the tech industry. 

The first thing that draws away from this goal is the number of circles in the visualization. Only the top 6 highest layoff companies are labelled, but aside from that, there are countless (literally, because they cover one another and aren't visible) other circles that have no company or layoff label. This does provide context for the six largest bubbles, but with the concept of layoffs, I think most people reading The Economist can tell that 11,000 layoffs is a lot; you don't need all the little circles to inform that.

Additionally, the time axis is not relevant. All of the data is from 2022 and the visualization is not comparing layoffs across a particular date or event, so individual dates within the year do not add to the story. Adding the additional data dimension merely draws away from the simple comparison of layoffs. 

Finally, the use of circles themselves makes the comparisons more difficult. The use of circles to represent the number of layoffs only allows the viewer to make comparisons with large discrepancies, because small discrepancies are hard to see with round shapes. 

## Initial Sketches

In sketching original ideas for the new visualization, I wanted to address the three main issues I identified above. To address the number of circles on the visualization, I limited the included companies to those with at least 300 layoffs in 2022. This left me with 42 companies rather than the original 219. 

I removed the time element by changing the chart type. I knew I wanted to use a simpler chart type that would allow me to focus on differences in layoffs. Column and bar charts came to mind, so I tried both options. This also addressed the issue of comparisons between circles; bars are far easier to compare than circles. 

Beyond the main issues with the visualization, I also wanted to play with color. I wanted to highlight the company with the most layoffs, and I figured the best way to do this was via color. I started by using blue and yellow, which plays on the blue in the original visualization. I also tried using different shades of red, since layoffs are generally considered a bad thing. The red could therefore convey the urgency of the situation. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11849340"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-chart" data-src="visualisation/11849358"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Testing the Sketches

I reached out to two individuals to test my sketches. I informed them that the two charts are different visualizations of the same data, and those visualizations were presented in the same order as that on this page. I asked them the following questions:

- What are the visualizations telling you?
- How do the visualizations make you feel about the data? Do the two visualizations make you feel differently?
- Is there anything that confuses you about the visualizations?
- Is there anything you would do differently to visualize this data?

### Student, mid 20's

**- What are the visualizations telling you?** The number of employees that different tech companies have laid off in 2022
**- How do the visualizations make you feel about the data? Do the two visualizations make you feel differently?** I’m more shocked by the second visualization, because I can see better how much higher the Amazon bar is. It’s also clearer to me, since the company names are oriented in a more easily readable way.
**- Is there anything that confuses you about the visualizations?** In the first visualization, the title highlights that Amazon is the highest. However, Amazon isn’t included in the x-axis labels. I’m also curious about more recent data, now that we know Twitter has been laying off many of its employees under new leadership. 
**- Is there anything you would do differently to visualize this data?** I think it could help to darken the axis labels just a little bit, for better legibility.

### Professional, mid 50's


### Feedback Conclusions


##


[Return to Portfolio](https://taypopp.github.io/Popp-Portfolio)
