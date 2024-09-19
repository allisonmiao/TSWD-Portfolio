# Critique by Design with Tableau (MakeoverMonday)

Detailed step-by-step progress of redesigning a visualization.

## Step one: choose a data visualization from MakeoverMonday

<img width="1663" alt="Assignment3 4 part 1" src="https://github.com/user-attachments/assets/867532e0-8ec3-46f1-9e53-2d2bbc9c5100">

[Link to the Page](https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/)

The graph presents an analysis of financial performance across various Marvel movies, plotted over time from 2008 to 2024. Each movie is represented as a point on a scatter plot where the x-axis indicates the release year and the y-axis shows the percentage of budget recovered, illustrating the profitability of each film. The color coding corresponds to different movie series within the Marvel Universe, allowing for an easy comparison across different superhero series. To enrich the user experience and deliver detailed insights, each data point representing a movie is interactive. By moving the cursor onto each data point, the visualization will pop a small window showing in-depth information of the movie includes the worldwide gross revenue, the budget, the percentage of the budget recovered, critical and audience scores, and the distribution of gross earnings between domestic and international markets.

As a Marvel enthusiast and a professional exploring data visualization, I chose to critique and redesign this graph due to its relevance to both my personal interests and my academic focus on data-driven decision-making in the media industry. The graph's emphasis on the financial aspects of Marvel movies, such as budget allocation and revenue generation, aligns with my intent to delve deeper into economic evaluations within the film industry. This analysis not only feeds my passion for Marvel films but also enriches my understanding of their economic impact, serving as a practical application of data visualization techniques in assessing entertainment economics.

## Step two: critique the data visualization

Usefulness (8/10)
Completeness (8/10)
Perceptibility (6/10)
Truthfulness (9/10)
Intuitiveness (5/10)
Aesthetics (5/10)
Engagement (5/10)

### Strengths of the Data Visualization

The data visualization is excellent in its interactive design, color coding, and filtering capabilities, which significantly enhance the user experience. The interactive tooltips provide a depth of information about each Marvel movie, allowing viewers to engage with and explore detailed financial and audience reception data effectively. The use of distinct colors to represent different Marvel superhero series makes the visualization both visually appealing and easy to interpret. Additionally, the credibility of the data is reinforced by its sourcing from reputable industry databases, ensuring that viewers can trust the financial metrics and analyses presented.

### Weaknesses of the Data Visualization

The percentage scale for budget recovery is too compressed for high-performing movies, causing confusion that can mislead the interpretation of performance across most films. Furthermore, the proximity of data points, especially in years with multiple releases, results in overlaps that make it difficult to select and view specific movie details. The inclusion of extensive text within the tooltips can also be overwhelming, potentially causing readers to get bored and diminishing engagement with the data. Additionally, the lack of absolute financial figures in the primary visualization limits the immediate understanding of the actual economic impact of the movies.

### Suggestions for Improvement

Improving the visualization could involve reducing the amount of text or focusing on a specific aspect of the dataset might help maintain viewer interest and prevent information overload. For example, offering a clearer perspective on the magnitude of the budget recovered could be beneficial for showing the movie series’ performance. Finally, a timeline slider could refine the user's ability to navigate through different years, improving the visualization's usefulness.

## Step three: sketch out a solution

<img width="760" alt="Solution Sketch" src="https://github.com/user-attachments/assets/9a0aca1a-04c4-4a22-9d1c-55b366f9b06d">

This line graph displays the profitability of Marvel movies over time, categorized by superhero movie series. Each line, distinguished by color, shows how each series of movies has recovered their budgets across different release years.

## Step four: Test the solution

Respondent:
A: student, mid 20's
B: student, mid 20's

### Interview Questions and Feedback

Question 1: Could you please share your thoughts on what this visualization represents?
A: It is about how Marvel movies have been doing financially over the years, specifically looking at how much money they’ve made back compared to what they spent.
B: This is a line graph that tracks how much profit each Marvel movie series has made over time.

Question 2: What information does this visualization tell you?
A: It’s a representation of which Marvel movie series made a profit over the years.
B: It shows how well each Marvel series is doing in profitability using the aspect of recovering budget. The color legend represents different Marvel series.

Question 3: Have you encountered any aspects of the visualization that you find either surprising or perhaps a bit unclear?
A: I find it interesting but a little bit narrow since it only talks about budget recovery. There could be more to movie success, like movie ratings.
B: It’s surprising to know that Spider-Man is the only movie series that is close to recovering all its budget spent.

Question 4: In your opinion, who would be the most likely target audience for this visualization?
A: It’s probably for Marvel fans or students like us who want to know the business side of movies.
B: The primary audience would be people who are interested in the business and economics of the film industry, specifically those focusing on entertainment analytics.

Question 5: Is there any improvement in particular that you would suggest for this visualization?
A: I would suggest adding some details like how much each movie made overall and what people thought about it. Thereby it gives the audience a fuller picture instead of just looking at the cash flow.
B: Reducing overlap in more crowded areas of the graph would help in making each data point more accessible.

### Analysis of Feedback Patterns
From the interviews, a pattern emerges highlighting the desire for a more comprehensive view of Marvel movies' performance. Respondents suggest including broader metrics such as total box office earnings, audience ratings, and critical reviews, referring to the original visualization. There's also a call for improvements in the clarity and accessibility of the visualization, specifically mentioning the need to address overlapping data points in crowded areas.

### Lessons Learned from the Feedback
The feedback emphasizes the importance of comprehensive data representation in visualizations. It also indicates that enhancing readability and usability should be the priority in redesigning the graph.

### Proposed Design Changes for Final Redesign
Integrate Additional Data Details: Metrics of audience ratings will be included to provide a holistic view of each movie’s success. Movie earnings from domestic and international markets will also be analyzed.
Improve Graph Readability: Techniques like increasing spacing will be implemented.
Enhance Interactivity: The addition of a filter for movie series will allow users to tailor the visualization to their interests.

## Step five: Build your solution

**Graph 1: Profitability Over Time**

<div class='tableauPlaceholder' id='viz1726716075829' style='position: relative'><noscript><a href='#'><img alt='Profitability Over Time ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34ProfitabilityOverTime&#47;ProfitabilityOverTime&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment34ProfitabilityOverTime&#47;ProfitabilityOverTime' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34ProfitabilityOverTime&#47;ProfitabilityOverTime&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726716075829');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This line graph tracks the average percentage of budget recovered by various Marvel movie series over time. The filter box could help detect the impact on the average profitability of a superhero series from a specific Marvel movie. Color-coded lines represent different series, offering a clear visual comparison of their financial performance through the years. 

**Graph 2: Critics vs. Audience Scores**

<div class='tableauPlaceholder' id='viz1726716402414' style='position: relative'><noscript><a href='#'><img alt='Critics vs. Audience Scores ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34Criticsvs_AudienceScores&#47;Criticsvs_AudienceScores&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment34Criticsvs_AudienceScores&#47;Criticsvs_AudienceScores' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34Criticsvs_AudienceScores&#47;Criticsvs_AudienceScores&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726716402414');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This scatter plot compares the critics' scores and audience scores for Marvel movies, providing insight into discrepancies between critical acclaim and audience reception. Each point represents a movie, color-coded by different superhero series. The filter box could help detect the impact on the ratings of a superhero series from a specific Marvel movie.

**Graph 3: Domestic vs. International Earnings**

<div class='tableauPlaceholder' id='viz1726716631317' style='position: relative'><noscript><a href='#'><img alt='Domestic vs. International Earnings ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34Domesticvs_InternationalEarnings&#47;Domesticvs_InternationalEarnings&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment34Domesticvs_InternationalEarnings&#47;Domesticvs_InternationalEarnings' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34Domesticvs_InternationalEarnings&#47;Domesticvs_InternationalEarnings&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726716631317');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

A side-by-side bar chart displays the comparison of domestic and international gross earnings for each Marvel movie, illustrating the geographic distribution of revenue. Bars are color-coded by markets, making it easy to see which markets contributed more to the earnings of each film.

### Summary
These visualizations provide a holistic view of Marvel movies' performance, integrating financial metrics, critical and audience reception, and global market distribution. By presenting profitability trends, comparing perceptions between critics and audiences, and highlighting geographic revenue contributions, these graphs collectively displays the success of the Marvel superhero movie series. 
