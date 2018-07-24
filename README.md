# The happiest place on earth 
## Introduction
The World Happiness Report is a landmark survey by the United Nations Sustainable Development Solutions Network about the state of global happiness.Each year they survey people from more than 150 countries and ask questions about their happiness and other aspects in their lives such as social support, freedom, etc. The data published contains country level survey data,  as well as some data related to country performance such as GDP and life expectancy. 

The project is inspired by this report and we would like to look at what countries are happier and what makes people in a particular region happier than others through visualization. The dataset used in this project and the definition of variables can be found under 'Data' of this page.

When we look at happiness score by country, we found that people in North America, Australia, New Zealand, Western Europe are the happiest, followed by Latin America. People in Africa have the lowest happiness score in general.


<div>
    <a href="https://plot.ly/~wyr211/58/?share_key=hMo4eCbiaWI3OTqJj7NEgM" target="_blank" title="world-heatmap_2" style="display: block; text-align: center;"><img src="https://plot.ly/~wyr211/58.png?share_key=hMo4eCbiaWI3OTqJj7NEgM" alt="world-heatmap_2" style="max-width: 100%;width: 600px;"  width="80%" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    
</div>




When exploring the relationship between happiness and GDP per capita, we found that Latin Americans are outstandingly happier comparing with other countries with similar level of wealthness.


<div>
    <a href="https://plot.ly/~wyr211/120/?share_key=pTs604WpG3EeCiwBCRayQW" target="_blank" title="plot from API (4)" style="display: block; text-align: center;"><img src="https://plot.ly/~wyr211/120.png?share_key=pTs604WpG3EeCiwBCRayQW" alt="plot from API (4)" style="max-width: 100%;width: 600px;"  width="80%" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    
</div>



The rest of the project focuses on giving this unusual happiness some possible explanations through examining the relationship between happiness and different aspects. We tried the theory of religion, social support and generic gift by integrating external datasets to do further analysis.


## Next Step

Regression anaylsis by using the time series data to find out reasons for happiness.

## Index of Repository
[Code of all the graphs](https://nbviewer.jupyter.org/github/wyr211/Happy/blob/master/Happiness_Overall_Final.ipynb)<br>*World map and line chart of overall happiness level and trend, scatter plots and box plot to show relations between variables*

|Data|
|---|
|[Original_2017_full](https://github.com/wyr211/Happy/blob/master/data/Original_2017_full.csv)<br>*The original dataset of World Happiness Report which contains data from 2008 to 2017.*|
|[Original_2017_region](https://github.com/wyr211/Happy/blob/master/data/Original_2017_region.csv)<br>*Region list used by World Happiness Report*.|
|[relig_iso](https://github.com/wyr211/Happy/blob/master/data/relig_iso.csv)<br>*2016 Globle religion population percentage data.*|
|[DataSourcesAndVariableDef](https://github.com/wyr211/Happy/blob/master/data/DataSourcesAndVariableDef.pdf)<br>*Data sources and variable definitions by World Happiness Report.*|

|Visualization|
|---|
|[Heatmap_of_world_happiness](https://github.com/wyr211/Happy/blob/master/visualization/Heatmap_of_world_happiness.md)<br>*The distribution of happiness level around the world 2016.*|
|[Happiness_trend](https://github.com/wyr211/Happy/blob/master/visualization/Happiness_trend.md)<br>*Happiness scores from year 2008 to 2017*.|
|[Happiness_GDP](https://github.com/wyr211/Happy/blob/master/visualization/Happiness_GDP.md)<br>*Scatter plot to show the relationship between happiness scores and GDP per capita among regions.*|
|[Happiness_religion](https://github.com/wyr211/Happy/blob/master/visualization/Happiness_Religion.md)<br>*Scatter plot to show the relationship between happiness scores and religion percentage among regions.*|
|[Happiness_SocialSupport](https://github.com/wyr211/Happy/blob/master/visualization/Happiness_SocialSupport.md)<br>*Scatter plot to show the relationship between happiness scores and social support among regions.*|
|[Happiness_Gene](https://github.com/wyr211/Happy/blob/master/visualization/Happiness_Gene.md)<br>*Boxplot to show the difference on happiness level between two types of gene groups.*|
|[Happiness_LifeExpectancy](https://github.com/wyr211/Happy/blob/master/visualization/Happiness_LifeExpectancy.md)<br>*Scatter plot to show the relationship between happiness scores and life expectancy among regions.*|
|[Happiness_Freedom](https://github.com/wyr211/Happy/blob/master/visualization/Happiness_Freedom.md)<br>*Scatter plot to show the relationship between happiness scores and freedom level among regions.*|
|[GDP_religion](https://github.com/wyr211/Happy/blob/master/visualization/GDP_religion.md)<br>*Scatter plot to show the relationship between GDP per capita and religion percentage among regions.*|


## Inspiration
[World happiness report](http://worldhappiness.report)

[Why Are Latinos More Likely to Be Happy?](https://www.huffingtonpost.com/daniel-cubias/why-are-latinos-more-like_b_9012348.html)

[Venezuela’s not-so-happy new year](http://thehill.com/opinion/international/367204-venezuelas-not-so-happy-new-year)

[Haiti: a nation sadly familiar with hurricanes and earthquakes](https://www.cnn.com/2016/10/04/world/haiti-disasters/index.html)

[THE SECRET OF HAPPINESS: FAMILY, FRIENDS AND YOUR ENVIRONMENT](https://www.independent.co.uk/life-style/health-and-families/health-news/the-secret-of-happiness-family-friends-and-your-environment-2053053.html)

[Religion is a sure route to true happiness](https://www.washingtonpost.com/national/religion/religion-is-a-sure-route-to-true-happiness/2014/01/23/f6522120-8452-11e3-bbe5-6a2a3141e3a9_story.html?noredirect=on&utm_term=.0d916b839370)

[Genes Hold The Key To How Happy We Are, Scientists Say](https://www.sciencedaily.com/releases/2008/03/080304103308.htm)

