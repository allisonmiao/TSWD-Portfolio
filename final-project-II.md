| [home page](https://allisonmiao.github.io/TSWD-Portfolio) | [visualizing debt](https://allisonmiao.github.io/TSWD-Portfolio/visualizing-debt) | [critique by design](https://allisonmiao.github.io/TSWD-Portfolio/critique-by-design) | [final project I](https://allisonmiao.github.io/TSWD-Portfolio/final-project-I) | [final project II](https://allisonmiao.github.io/TSWD-Portfolio/final-project-II) | [final project III](https://allisonmiao.github.io/TSWD-Portfolio/final-project-III) |

# Part II: Final project wireframes/storyboards and user research

Final Project Part 2 Overview

**The Relationship Between Video Game Quality and Sales Across Genres, Platforms, and Regions**

**Introduction**: Video game success can be measured both by critical reception and sales performance. However, how do these metrics align across different genres, platforms, and regions? Are highly-rated games always the top sellers, or do certain regions or platforms prioritize different aspects of gaming?

## Wireframes/storyboards

<div class='tableauPlaceholder' id='viz1728012748554' style='position: relative'><noscript><a href='#'><img alt='Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDProjectPart2&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWDProjectPart2&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDProjectPart2&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1728012748554');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( 
    divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { 
    vizElement.style.width='100%';vizElement.style.height='1527px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## User research

### Target audience

1. Game Developers & Publishers:

  - Who they are: Decision-makers at studios, responsible for game development and resource allocation.
  - Why they care: They can use insights on the relationship between ratings and sales to better focus on genres, platforms, and regions that drive success.
  - How to reach them: Through industry conferences, reports, and articles on professional platforms like Gamasutra or IGDA.

2. Marketing & Business Analysts:

  - Who they are: Analysts in gaming companies or consulting firms assessing market trends and game performance.
  - Why they care: Understanding how ratings and sales intersect can refine market strategies, helping them make more data-driven decisions.
  - How to reach them: Via industry reports, business journals, and analytics conferences.

3. Gaming Enthusiasts & Media:

  - Who they are: Journalists, content creators, and gamers interested in game quality and commercial success.
  - Why they care: The story offers insights into whether high-rated games match what players enjoy or what sells.
  - How to reach them: Through gaming websites, social media, and interactive visualizations shared in online communities.

### Interview script

| Goal | Questions to Ask |
|------|------------------|
|Clarity of the Story|Does the narrative of the dashboard come through clearly? If not, which aspects are unclear or confusing?|
|Effectiveness of Visualizations|Do the visualizations clearly represent the relationships between critical acclaim, sales, platform success, and genre preferences? Are there any elements that need improvement?|
|Completeness of Insights|Do you feel that the dashboard covers all key insights, or are there additional details (e.g., filters or breakdowns) that could provide a more complete analysis?|
|Usability and Interactivity|How easy is it to navigate and interact with the dashboard? Are the filters and interactive elements intuitive, or could they be more user-friendly?|
|Design and Layout|What are your impressions of the design and layout? Do the charts, text, and filters feel well-balanced, or are there areas where the design could be improved?|

### Interview findings

| Questions               | Interview 1 | Interview 2 |
|-------------------------|--------------------------------|-------------|
|Does the narrative of the dashboard come through clearly? If not, which aspects are unclear or confusing?	|"Yes, the overall narrative is clear. The relationships between video game quality, sales, and platform-specific success are well communicated. It’s easy to follow the story and see the trends."	|"Yes, the story is clear, but I think there's too much text in the introduction. It’s a bit overwhelming for users at first glance. Streamlining the text might help make the narrative easier to absorb."| 
|Do the visualizations clearly represent the relationships between critical acclaim, sales, platform success, and genre preferences? Are there any elements that need improvement?	|"The visualizations are effective for the most part. However, I think the Critical Acclaim vs. Sales Performance graph could be improved by excluding the outliers, as they skew the view of the majority of the data points."	|"The visualizations work well in general. However, the Platform-Specific Success by Score graph is not intuitive when it’s grouped by the average critic score. It feels a bit disconnected from the sales data."|
|Do you feel that the dashboard covers all key insights, or are there additional details (e.g., filters or breakdowns) that could provide a more complete analysis?	|"It covers most of the key insights well, but I think the genre preference graph doesn't need a shifting years button. It makes the graph harder to understand because the animation isn’t very intuitive—it might be better to show a static comparison across regions instead."	|"The insights are well-covered, but too much text can make it harder to engage with the dashboard quickly. Perhaps the descriptions could be shortened or moved to tooltips."|
|How easy is it to navigate and interact with the dashboard? Are the filters and interactive elements intuitive, or could they be more user-friendly?	|"The interactivity is mostly good, but the 'Instruction to understand the dashboard' button is hard to see. Making it more prominent would help users better understand how to navigate the dashboard."	|"It's mostly easy to navigate, but some elements, like the genre preferences graph, become less intuitive with the shifting years button. I think a static comparison would be clearer."|
|What are your impressions of the design and layout? Do the charts, text, and filters feel well-balanced, or are there areas where the design could be improved?	|"Overall, the layout is visually appealing and balanced. Just focus on making some of the instructional elements more visible for a better user experience."	|"The design is clean and visually appealing, but the amount of text detracts from the overall simplicity. Reducing the text and improving the grouping in some of the graphs would make the dashboard easier to use."|

## Identified changes for Part III

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
|Finding 1: Difficulty seeing the 'Instruction to understand the dashboard' button	|Make the "Instruction" button more prominent by increasing its size, color contrast, or repositioning it in a more visible location on the dashboard.|
|Finding 2: Critical Acclaim vs. Sales Performance graph has outliers that skew the view	|Exclude or provide an option to filter out outliers in the Critical Acclaim vs. Sales Performance graph to ensure clearer insights from the majority of the data.|
|Finding 3: Genre preferences graph doesn't need shifting years button, and it becomes less intuitive	|Replace the animated year-changing function in the Genre Preferences by Region graph with a static comparison of different regions without the shifting years button. This will make the graph more intuitive and easier to understand.|
|Finding 4: Platform-Specific Success by Score graph is not intuitive when grouped by the average critic score	|Reorganize the Platform-Specific Success by Score graph by grouping platforms based on total sales or some other metric instead of the average critic score, which feels disconnected.|
|Finding 5: Too much text in the introduction	|Reduce and streamline the introduction text to make it less overwhelming for users. Consider moving some of the detailed descriptions into tooltips or side notes to maintain focus on the visuals.|

**Final Thoughts:**

The interview responses provided valuable insights into improving the dashboard's usability and clarity. The main focus will be simplifying the visuals and instructions, particularly making the Critical Acclaim vs. Sales Performance and Genre Preferences by Region graphs more intuitive by removing unnecessary elements like outliers and the shifting years button. Streamlining the text will also help make the dashboard more user-friendly and engaging. These changes aim to enhance both the user experience and the effectiveness of the storytelling.
