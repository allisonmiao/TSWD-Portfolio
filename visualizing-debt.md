# Visualizing government debt using Tableau

This is a data visualization exercise using the dataset of General Government Debt from the OECD.

## Part 1: Working with web-based visualization tools and data

![visualizing-debt-part1](https://github.com/user-attachments/assets/707da262-76cf-4726-ac4b-b05debf16bea)

The bar graph displayed here, sourced from the OECD, visualizes the general government debt as a percentage of GDP for various countries in the year 2010. It highlights the significant variation in debt levels across different nations, with Japan showing the highest ratio, significantly above other countries. This metric represents the total gross debt of a country's government relative to its GDP. Tracking this ratio could assess the sustainability of government finances, as it reflects the cumulative impact of government deficits for a specific time.

## Part 2: Working with Tableau

<div class='tableauPlaceholder' id='viz1726012023589' style='position: relative'><noscript><a href='#'><img alt='National Debt-to-GDP Ratios Over TimeSource: The Organisation for Economic Co-operation and Development (OECD)https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtVisualization&#47;NationalDebt-to-GDPRatiosOverTime&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebtVisualization&#47;NationalDebt-to-GDPRatiosOverTime' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtVisualization&#47;NationalDebt-to-GDPRatiosOverTime&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726012023589');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This heat map, sourced from the OECD, illustrates the evolution of national debt-to-GDP ratios for a selection of countries from 1995 to 2019. Each cell represents the ratio for a particular country in a given year. The color coding of the map distinguishes between debt-to-GDP ratios below and above 100%. Ratios below 100% are represented in shades of blue, where darker blues indicate lower debt levels relative to GDP, and lighter blues are closer to 100%. Conversely, ratios above 100% are shown in shades of orange, with darker oranges representing higher debt levels and lighter oranges nearing 100%. This visual representation shows how government debt levels have changed over time in response to economic conditions, policy decisions, and other factors, and helps understand the fiscal health and sustainability of government finances across these nations.

## Part 3: Create your own visualization

<div class='tableauPlaceholder' id='viz1726011849786' style='position: relative'><noscript><a href='#'><img alt='National Debt-to-GDP Ratios TrendsSource: The Organisation for Economic Co-operation and Development (OECD)https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtVisualizationTrend&#47;NationalDebt-to-GDPRatiosTrends&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebtVisualizationTrend&#47;NationalDebt-to-GDPRatiosTrends' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtVisualizationTrend&#47;NationalDebt-to-GDPRatiosTrends&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726011849786');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This line graph, sourced from the OECD, illustrates the trend of national debt-to-GDP ratios for selected countries from 1995 to 2019. It tracks the fiscal metrics of Australia, Belgium, Canada, France, Japan, and the United States, each represented by a distinct color. The graph highlights significant trends and shifts in debt levels relative to GDP and compares how each country's debt situation has evolved over the specified period.

**Summary**

The three graphs that sourced from the OECD provide varying perspectives on the national debt-to-GDP ratios across different countries, utilizing different visualization techniques that highlight unique aspects of the data. The first graph, a bar chart from 2010, offers a ranking of countries by their debt relative to GDP for a single year 2010. This allows for a quick assessment of which countries had higher or lower debt levels at that particular point in time, but does not provide any information about trends or changes over time. The second visualization, a heat map, extends the analysis across a longer period, from 1995 to 2019. It employs a color gradient to indicate the debt level, with varying colors and shades representing the scale of debt relative to GDP. This method allows audiences to track the progression and fluctuations of debt over time for each country, making it easy to see periods of increase or decrease and compare temporal patterns across countries. I specifically chose to do the third graph, a line graph, to track the debt trajectories of selected countries over the same period as the heat map. This method provides a continuous, detailed view of debt trends, highlighting how specific years of events like economic crises or changes in fiscal policy have influenced these trajectories. Unlike the static and broad perspectives offered by the first two graphs, the line graph allows for an in-depth analysis of patterns, making it possible to forecast future movements based on past data. The choice to use the line graph provides a more specific analysis by focusing on selected countries and offers a contrast about how these countries have managed their debt over two decades.
