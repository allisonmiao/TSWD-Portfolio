| [home page](https://allisonmiao.github.io/TSWD-Portfolio) | [visualizing debt](https://allisonmiao.github.io/TSWD-Portfolio/visualizing-debt) | [critique by design](https://allisonmiao.github.io/TSWD-Portfolio/critique-by-design) | [final project I](https://allisonmiao.github.io/TSWD-Portfolio/final-project-I) | [final project II](https://allisonmiao.github.io/TSWD-Portfolio/final-project-II) | [final project III](https://allisonmiao.github.io/TSWD-Portfolio/final-project-III) |

# Part III: Final project and presentation

Final Project Part 3 Overview

## The final data story

<div class='tableauPlaceholder' id='viz1728705998323' style='position: relative'><noscript><a href='#'><img alt='Understanding What Makes a Video Game Success ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Un&#47;UnderstandingWhatMakesaVideoGameSuccess&#47;UnderstandingWhatMakesaVideoGameSuccess&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='UnderstandingWhatMakesaVideoGameSuccess&#47;UnderstandingWhatMakesaVideoGameSuccess' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Un&#47;UnderstandingWhatMakesaVideoGameSuccess&#47;UnderstandingWhatMakesaVideoGameSuccess&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1728705998323');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='1016px';vizElement.style.height='991px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

[Link](https://public.tableau.com/views/UnderstandingWhatMakesaVideoGameSuccess/UnderstandingWhatMakesaVideoGameSuccess?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This storyboard explores how critical acclaim, brand loyalty, gameplay quality, and platform choices influence the commercial success and longevity of video games and game series.

## Changes made since Part II

First, I modified the Platform-Specific Success by Score visualization to Platform-Specific Success by Genre. This change was driven by the feedback that grouping platforms by average critic score wasn’t intuitive or providing clear insights into the relationship between genres and platform success. By focusing on genres, the visualization now offers a clearer understanding of which game types perform best on specific platforms, helping to identify trends across different systems.

Second, I disabled the animation button for the Genre Preferences by Region graph. The previous animation feature was found to be less intuitive, making it harder to compare genres across regions. By removing the animation, I allow for a static view that simplifies comparisons between regions, making the data more accessible and easier to interpret.

Finally, I added a new dashboard that dives into specific, highly popular game series like Grand Theft Auto and Super Mario. This change provides a deeper look into how certain game series consistently achieve commercial success over time, combining the insights from top-rated individual games with the power of recognizable and beloved series. This addition enhances the analysis by showing how these game series dominate sales, further supporting the narrative that brand loyalty and consistent quality drive long-term success in the gaming industry.

These changes were implemented to improve the overall usability and storytelling of the dashboard, ensuring that both casual users and industry professionals can easily understand the key factors driving success in the video game market.

### The audience

For the final data story, I identified two primary audience groups: game developers and publishers as well as gaming industry analysts. Both groups have a vested interest in understanding the relationship between game quality, platform preferences, and commercial success. Game developers need insights to better align their game development and marketing strategies with player preferences and successful trends, while analysts are focused on identifying patterns that can inform future investments and strategies in the gaming market.

**Audience Insights**:

- Game Developers and Publishers: Developers need to know which platforms and genres are most successful in different regions to guide their creative and business decisions. By providing clear data on how platforms and genres drive sales, this story directly helps them understand which combinations perform best globally. The focus on game series success highlights the importance of long-term engagement and consistent quality, which helps developers strategize for their own franchises.

- Gaming Industry Analysts: Analysts, especially those who track sales trends and market performance, need to see how critical acclaim correlates with commercial success. The Critical Acclaim vs. Sales Performance visualization directly addresses this, offering them a clear view of how top-rated games align (or don’t) with sales performance. This helps analysts understand whether they should weigh critical reception or brand power more heavily when making predictions about future game performance.

**Adjustments Based on Audience**:

1. Simplifying Visuals: Based on feedback from interviews, I simplified certain elements. For example, I disabled the animation in the Genre Preferences by Region visualization to make the comparison between regions easier to grasp. This was especially important for analysts and developers who need to make quick and clear assessments of data without unnecessary distractions.

2. Focusing on Genres and Platforms: I changed the Platform-Specific Success by Score to Platform-Specific Success by Genre to better align with what developers and analysts care about most—understanding which game genres perform best on which platforms. This adjustment provided a clearer, more actionable takeaway.

3. Adding Game Series Analysis: I included an additional dashboard focusing on the performance of major game series like GTA and Super Mario, based on insights that franchises and established game series tend to drive long-term success. This was key to helping developers see how brand loyalty impacts sales and longevity, and it gives analysts a concrete example of how brand recognition can influence market performance.

### Final design decisions

Several important design decisions were made to improve usability and clarity for the target audience:

1. Simplifying Interaction: I disabled the animation feature in the Genre Preferences by Region chart, which made comparisons clearer and easier for users to interpret without distractions.

2. Switching to Platform by Genre: I changed the Platform-Specific Success chart from being grouped by critic scores to being grouped by genre, as it provided more relevant insights for developers and analysts, showing which platforms perform best in specific genres.

3. Balancing Critical Acclaim and Sales: The Critical Acclaim vs. Sales Performance chart was designed to clearly show average scores and sales, providing quick reference points for users to understand whether games were outperforming or underperforming industry averages.

4. Adding Game Series Focus: The inclusion of a dashboard highlighting GTA and Super Mario game series provided valuable insights into the long-term success of iconic franchises, underscoring the importance of brand loyalty in the gaming industry.

5. Clear Navigation: I enhanced the visibility of the Instruction to Understand the Dashboard button, ensuring all users could easily navigate the dashboard and access the insights.

### References

Dataset:

[Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales/data)
[Video Game Sales with Ratings](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings)
[IGN games from best to worst](https://www.kaggle.com/datasets/kapturovalexander/ign-games-from-best-to-worst)

Image:

[Super Mario](https://www.nintendo.com/en-gb/Games/Characters-hub/Super-Mario-Hub/Super-Mario-Bros-Hub-Mario-Games-627604.html)
[Grand Theft Auto V](https://en.wikipedia.org/wiki/Grand_Theft_Auto_V#/media/File:Grand_Theft_Auto_V.png)

## Final thoughts

While this analysis provides valuable insights into the relationship between critical acclaim, genre preferences, and global sales, it has limitations. One of the key factors missing from the story is information about the production costs for each game, which would help determine the return on investment (ROI) for game developers. Without understanding how much companies invested in developing and marketing these games, it’s difficult to assess their true commercial success beyond sales numbers. Knowing the ROI could offer a more complete picture of whether these critically and commercially successful games were also financially efficient for the companies that produced them.

Additionally, while I’m excited about how this project came together, I would have liked more time to explore other variables, such as how marketing budgets or player engagement metrics (like playtime or DLC sales) influence game success. Overall, the project helped me gain a deeper understanding of the gaming industry’s complexities, and I hope these findings will be useful to developers, publishers, and analysts alike.
