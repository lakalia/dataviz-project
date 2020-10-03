# Data Visualization Project

## Data

The data I propose to visualize for my project is the [data](https://gist.github.com/lakalia/ca6cc81792b9d357a20cf2f9fd4c7924) from Hans Rosling's Gapminder Population Growth: [image](https://raw.githubusercontent.com/lakalia/dataviz-project-proposal/master/Hans_Rosling_visualization.gif) 
brushed with the world regions according to the world bank:
[image](https://d3js.slack.com/files/U0199ME1BD4/F01AV760TEF/world-regions-according-to-the-world-bank.gif)
Ideally the world regions will be faded in the background until you mouse-over a country in which case the corresponding region and all other countries in the region will pop. 
I'd like to add a slider to animate population change over time instead of a static visualization and use Income per capita data on the x axis. Eventually, I will add a drop-down to choose between visualizing Total Population, Life Expectancy or Fertility against Income per capita data.



## Prototypes

I’ve created a proof of concept visualization of this data. It's a ... and it shows ...
I began translating my Vega-Lite visualization of the Hans Rosling Population Growth data:
https://vizhub.com/lakalia/fc9a5e845c3d45fc9207a6dd43cedd44
into React and D3:
https://vizhub.com/lakalia/d073269f3dae47359a3f9c57a5458c00
and I would like to use the lessons from this week to brush in the world regions in the background

[![image](https://user-images.githubusercontent.com/68416/65240758-9ef6c980-daff-11e9-9ffa-e35fc62683d2.png)](https://beta.vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)

(please put a screenshot of one or more visualizations of this dataset you already made, for previous assignments)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * (insert your question or task here) How does the X vary over time?
 * (insert your question or task here) Is there any correlation between X and Y?
 * (insert your question or task here) Are there interesting spatial patterns in X?
 * (insert your question or task here) How many X are there across different Y?

## Sketches

(insert one or more hand-drawn sketches of interactive visualizations that you imagine)
(describe each sketch - how is the data visualized, what are the interactions, and how do these relate to the questions/tasks)

## Open Questions

(describe any fear, uncertainty, or doubt you’re having about the feasibility of implementing the sketched system. For example, “I’m not sure where to get the geographic shapes to build a map from this data” or “I don’t know how to resolve the codes to meaningful names” … Feel free to delete this section if you’re confident.)
