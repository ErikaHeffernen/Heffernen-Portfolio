# Assignment: Visualizing Government Debt Using Tableau

## Data from OECD Website 
<iframe src="https://data.oecd.org/chart/7kmA" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7kmA" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>

## Average Government Debt as % of GDP Table
<div class='tableauPlaceholder' id='viz1706558355653' style='position: relative'><noscript><a href='#'><img alt='Japan&#39;s government debt per % of GDP remains high and continues to grow.  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_17065583441560&#47;HighlightTable&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='VisualizingGovernmentDebt_17065583441560&#47;HighlightTable' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_17065583441560&#47;HighlightTable&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706558355653');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Average Government Debt from 1995 to 2022 World Map
<div class='tableauPlaceholder' id='viz1706558439189' style='position: relative'><noscript><a href='#'><img alt='Japan has consistenty had the largest government debt as a % of GDP. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_17065583441560&#47;WorldView&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='VisualizingGovernmentDebt_17065583441560&#47;WorldView' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_17065583441560&#47;WorldView&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706558439189');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Decisions Behind the Data Visualization
My first thought after seeing all this data was "what does this look like on a world map?". With that inspiration, I wanted to use the data provided and create a world view of all the countries. From there, I decided to use the average of the % of GDP for each country. I toyed around with the idea of doing just the most recent year but concluded that audiences might want a historical average for each country. This way, audiences would be able to see which countries were consistently good with low government debt in terms of % of GDP or bad with high government debt in terms of % of GDP. 

From there, I chose the color of the heatmap. I thought about using one color like orange, but that made it difficult to differentiate which countries were worse compared to others. I tried the blue to orange hue but saw that the orange would stand out while the blue did not shine through as much. For this visualization, I wanted to make sure audiences easily saw the difference between the best and worst countries in terms of government debt per % of GDP. Eventually, I landed on a green to orange hue. Green represented the lower end of the spectrum while orange represented the higher end. With these colors, audiences can quickly understand the dark green countries have lower values and are "good" while coutries in a dark orange had higher values and are "bad", tapping into heuristics. Both the green and oranges colors pop out of the map attracting the audience's attention. 

## Different Methods of Visualization
#### Visualization 1
The first bar graph visualization shows from least to most total debt for countries in terms of the % of GDP specifically for the year 2022. I think this graph does a good enough job of stating the data, but there are certain parts that could be improved. The audience's eyes immediately go to the left which has the countries with the most debt with little emphasis anywhere else in the graphic. I think the colors are fine, but again, there is nothing that really sticks out here. I think it still gets the job done.

#### Visualization 2
The second heat map graphic shows a country's debt as a % of GDP and how it changes over time. This includes more of historical factor to show audiences if certain countries got worse or better over time. This graphic utilizes different colors to emphasize "bad" vs "good". Similar to the bar chart, this chart orders the country in descending order, starting with Japan. This graphic is able to show us more historical context while also including color to draw our attention to certain regions of the heat map. One issue that the audience might have is how many numbers there are which may be overwhelming. Although we have great attributes, the audience might not be able to takeaway the key concept with so much going on. 

#### Visualization 3
The last graphic of the world map places each country with the average government debt per % of GDP. Since not all countries were included in this data, I was interested to see the locations of the selected countries on a world map. This may give more context if certain areas of the world are struggling while others are not. Although the average was taken from 1995 to 2022, this graphic does not show as much historical context as the heat map. Instead, this graphic shows which countries over time have been struggling with government debt compared to others. The green to orange hues stand out to audiences and draw their attention to the dark orange Japan, Italy, and Greece while the dark green draws attention to Eastern European countries. The downside to this visualization is that the larger countries will get more immediate attention because eyes gravitate toward them. 

The data used in all three visualizations was pulled from OECD Data. All three visualizations show in some way that Japan, Greece, and Italy have the largest government debt while countries like Estonia, Luxembourg, and Denmark have the smallest government debt per % of GDP. The important variables we used in these analyses were the location (country), value (government debt, % of GDP), and time (year). The reason I chose the visualization that I did was because I was curious where these countries were geographically. The heat map and bar graph were good as displaying information, but I wanted a visualization that showed the countries and their government debt altogether on a map. This final visualization shows the geographical context that the other visualizations did not accomplish. The audience is able to see the cluster of Eastern and Northern European countries with less government debt compared to Mediterranean countries and Japan.  

### Return Back to Home Page 
[Click this link to head back home!](/README.md)
