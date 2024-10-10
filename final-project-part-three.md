| [home page](https://shrutiujlan.github.io/tswd-portfolio/) | [visualizing debt](https://shrutiujlan.github.io/tswd-portfolio/visualizing-government-debt) | [critique by design](critique-by-design) |  [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# The final data story

## Dashboard I

<div class='tableauPlaceholder' id='viz1728587050653' style='position: relative'><noscript><a href='#'><img alt='NYC Restaurant Health ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ny&#47;NycDiningInsights&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NycDiningInsights&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ny&#47;NycDiningInsights&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>               
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1728587050653');                   
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='1250px';
vizElement.style.height='827px';                  
  var scriptElement = document.createElement('script');                   
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>

## Dashboard II

<div class='tableauPlaceholder' id='viz1728584412475' style='position: relative'><noscript><a href='#'><img alt='Debunking Dining Myths in NYCBy Shruti Ujlan ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DebunkingDiningMythsinNewyorkCity&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DebunkingDiningMythsinNewyorkCity&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DebunkingDiningMythsinNewyorkCity&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1728584412475');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.minWidth='1000px';
  vizElement.style.maxWidth='1200px';
  vizElement.style.width='100%';
  vizElement.style.minHeight='827px';
  vizElement.style.maxHeight='1027px';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


<br>
###Quick Guide to use the dashboards

In Dashboard 1, you can use the multi-value filter to focus on a specific inspection grade, which will update most of the graphs accordingly, except for the "Culinary Caution: Top Offenders" and "Which Cuisine is Safest?" charts. For the NYC map, hover over a zip code to view detailed information, including the restaurant name, violations, cuisine type, inspection grade received, and inspection score.

If dashboards aren't rendering you can view them here:

Dahsbaord1 https://public.tableau.com/app/profile/shruti.ujlan/viz/NycDiningInsights/Dashboard1#1
Dahsboard2 https://public.tableau.com/app/profile/shruti.ujlan/viz/DebunkingDiningMythsinNewyorkCity/Dashboard1

# Changes made since Part II
### Dashboard I

Color Palette Consistency: In response to feedback, I implemented a cohesive color scheme (Red, Peach, Green) across all dashboards to ensure visual uniformity and minimize confusion.

Reordered and updated Legends and filters for Clarity: I reorganized the legends to enhance clarity, simplifying navigation through the data visualizations. By employing a common legend and filters across most charts, I reduced clutter and improved overall readability. Additionally, I removed  Null option from the Isnpection Grade filter by using a set of the Grades column (non null), as it was not adding any value and was unecessary [1]

Updated Terminology: I revised the title that previously used the term "Boro," changing it to "Neighborhood" to make it more accessible for all users.

Reduced Clutter in Inspection Grades by Cuisine: The "Inspection Grades by Cuisine" graph was adjusted to highlight only the top 10 cuisines with the highest safety violations. This reduction in label clutter makes the data more digestible.

Enhanced Legend Labels: I added a custom label to emphasize the importance of the "Inspection Grades" color legend, suggesting clear labels like A (Safe), B (Moderate), and C (Unsafe) to facilitate quick comprehension of safety levels.

### Dashboard II
Clear NYC Indication: I ensured that Dashboard II clearly indicates that the information pertains specifically to New York City.

Simplified Terminology: I removed technichal terms like "correlation" and replaced with simpler descriptions to clarify the relationships between variables such as price, ratings, and inspection scores. This adjustment enhances accessibility for a non-technical audience.

Description of the Scoring System: I included a description explaining that higher scores indicate more violations, providing context for viewers.

Updated Graphs: The "Pricier Plates, Happier Plates" graph was transformed into a line chart to better illustrate the relationship between ratings and price categories, rather than categorizing by cuisine, which didn’t significantly contribute to the narrative.

Graph Type Updates: Based on feedback regarding the bubble chart's initial complexity, I switched it to a line chart with a gradient based on scores. Line charts are inherently more intuitive, making it easier for viewers to grasp relationships at a glance.

Removal of Unnecessary Filters: I eliminated superfluous filters that could hinder user navigation.

### Common Changes in Dashboards

Key Takeaways Section: Following suggestions with professor after the presentation, I added a concise key takeaways section at the top or side of the dashboard to provide viewers with a quick summary.This change enhances the overall impact of the dashboards and reinforces the key takeaways about food safety and quality in NYC restaurants.

Axis Labels and Chart Alignment: I corrected missing axis labels in several charts (e.g., line graphs) and ensured better alignment of the charts for a smoother visual experience.

Enhanced Storytelling with Titles and Context: I revised the titles of the visualizations to be more descriptive and narrative-driven, focusing on the story behind the data rather than merely stating numerical correlations. This approach strengthens the overall narrative arc and improves viewer engagement.


## The audience
Initially, I had a broader target audience in mind, including NYC locals who frequently dine out, visitors, restaurant owners and managers, as well as health inspectors and regulators, however, as I gathered more data and insights, it became clear that the dashboards were more diner-centric. While they can also provide valuable insights for restaurant managers, my primary focus shifted toward informing diners. My call to action for them is to truly understand what guarantees food safety and how safe their dining choices are based on available information. The inspection scores I analyzed are publicly available and serve as one of the best indicators of safer dining options. By emphasizing this, I hope to empower diners to make informed decisions about where to eat, leveraging the inspection data as a vital resource in their dining experiences.

## References

[1] https://community.tableau.com/s/question/0D54T00000C6LboSAF/how-to-hide-null-from-filter-while-still-keeping-it-in-data

# Final thoughts

Reflecting on the process, I found the journey to enhance my dashboards to be enlightening. The feedback from the in-class critique and user interviews proved invaluable, guiding me towards creating a more user-centered design. While I wish I had more time to go deeper into specific analysis or expand on certain visualizations, I am excited about the final dahsboards and the insights it can provide.

Initially, I employed a straightforward approach, aiming for clarity through a traditional narrative arc. However, I soon discovered that the intended message didn’t resonate with the audience as I had hoped. This realization prompted me to adapt my strategy, leading to several iterations, additional interviews, and a re-examination of the narrative flow.As the presentation deadline approached, I faced the challenge of abbreviating my analysis and vitualizations into a concise layout for a one-minute presentation since I was not using Shorthand for storytelling. Deciding which graphs to focus on in the dahsboard within such a short timeframe was difficult, as storytelling usually takes time. Ultimately, I chose to focus on a single persona for the presentation and prioritized the graphs that presented the information in the clearest, most straightforward way.

Overall, the most rewarding aspect of this project was witnessing how data visualization can significantly influence decision-making and debunk common myths regarding restaurant safety. By focusing on clarity, engagement, and storytelling, I believe my dashboards will empower diners, visitorsand restaurant managers alike to make informed choices based on the analysis of restaurant inspection data.




