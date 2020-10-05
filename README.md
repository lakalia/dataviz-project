# Data Visualization Project

## Data

The data I propose to visualize for my project is the [data](https://gist.github.com/lakalia/ca6cc81792b9d357a20cf2f9fd4c7924) 
from Hans Rosling's Gapminder: 
[![Hans_Rosling_visualization](Hans_Rosling_visualization.gif)](https://www.gapminder.org/tools) 

brushed with the world regions according to the world bank:
[![world-regions-according-to-the-world-bank](world-regions-according-to-the-world-bank.gif)](https://ourworldindata.org/grapher/world-regions-according-to-the-world-bank)

Ideally the world regions will be faded in the background until you mouse-over a country in which case the corresponding region and all other countries in the region will pop. 
I'd like to have a slider to animate population change over time and a drop-down to choose between visualizing Total Population, Life Expectancy or Fertility on the y axis against Income per capita on the x axis.



## Prototypes

I created an initial proof of concept visualization in Vega-Lite of the Hans Rosling Population Growth data over time:
[![proof of concept visualization in Vega-Lite](GapminderPopulationGrowth_Vega-lite.png)](https://vizhub.com/lakalia/fc9a5e845c3d45fc9207a6dd43cedd44)

I then began translating and refining that visualization in React and D3:
[![translating and refining that visualization in React and D3](GapminderPopulationGrowth_React_D3.png)](https://vizhub.com/lakalia/d073269f3dae47359a3f9c57a5458c00)
and I would like to use the techniques from [Datavis 2020](https://www.youtube.com/watch?v=AmOz08_Fh8Q&list=PL9yYRbwpkykuK6LSMLH3bAaPpXaDUXcLV&index=29) to:
* brush in the world regions in the background
* add the slider to animate population growth over time against income per capita
* and add a drop-down to change the attribute used to populate the y axis

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is there a correlation between Population, Life Expectancy or Fertility and a nation's Income per capita?
 * Does the world region of a country have any impact on those relationships? How much/what kind?
 * Are there any interesting correlations within the world regions?

## Sketches

Hans Rosling's Gapminder data visualization with drop-down for Total Population, Life Expectancy or UN Fertility on the y axis and slider for animation over time:
![image](Hans_Rosling_visualization_w_dropdown_slider.jpg)

## Open Questions

Although Hans Rosling's visualization on which this project is initially based has been implemented in React and D3 and the code is available on the internet, I'd like to be able to implement this project myself entirely from scratch. Based on the amount of time it has taken me to implement each feature so far, however, I am concerned the project is too ambitious to complete in the time we have. I will continue until it is completed because it will be a great learning exercise and a great way to showcase what I have learned when it is done.
