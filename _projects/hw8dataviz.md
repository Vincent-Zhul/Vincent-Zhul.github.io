---
name: HW8 Visualization
tools: [Python, Altair, Vega-Lite]
image: assets/pngs/scatterplot.png
description: This project showcases interactive visualizations using Vega-Lite.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---
# My Interactive Visualizations

Below are the interactive charts that created using Python, Altair and vega-lite:

## Scatter Plot

<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter_plot.json" style="width: 100%"></vegachart>


## Scatter Plot Design Description

This plot is an interactive scatter plot visualizing the frequency of UFO sightings over time, differentiated by country. In this plot, the x axis represents the time (year) extracted from the datetime column, encoded as a temporal field (T). The y axis shows the count of UFO sightings, quantitatively encoding (Q) the number of occurrences. The color encoding is categorical (N) based on the country, which helps in distinguishing sightings between different countries. This color scheme enhances the plot's clarity by allowing quick visual discrimination of data points from different countries. Interactivity is implemented through pan and zoom features, allowing users to explore specific time periods or observe trends over time more closely, thereby making the visualization more engaging and informative.

## Bar Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/bar_chart.json" style="width: 100%"></vegachart>

## Bar Chart Design Description

This is a bar chart showing the number of UFO sightings by the shape of the observed phenomenon. Here, the shape field is encoded as a nominal category (N) on the x axis, and the count of sightings is quantitatively encoded (Q) on the y axis. The color encoding is also by shape, providing a consistent visual cue across the chart. An interesting design choice is the conditional opacity, which highlights bars representing 'light' shaped UFOs, while dimming others, thus focusing attention on a specific category. Interactivity is introduced via a selection feature, allowing users to click on the legend to filter the dataset by UFO shapes. This interaction enhances the user's ability to perform a detailed examination of the sightings distribution across different shapes, making the data exploration process more dynamic and user-driven.


<div class="left">
{% include elements/button.html link="https://github.com/Vincent-Zhul/Vincent-Zhul.github.io/blob/main/assets/json/scatter_plot.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Vincent-Zhul/Vincent-Zhul.github.io/blob/main/python_notebooks/HW8.ipynb" text="The Analysis" %}
</div>

