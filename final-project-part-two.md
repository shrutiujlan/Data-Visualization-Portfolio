| [home page](https://shrutiujlan.github.io/tswd-portfolio/) | [visualizing debt](https://shrutiujlan.github.io/tswd-portfolio/visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three)
# Wireframes / storyboards

I worked on developing wireframes, and dashboards, and conducting user research to refine my storytelling concept. The artifacts for this stage were created using Python and Tableau. 

This project focuses on analyzing New York City's restaurant inspection data to uncover food safety trends and assess customer satisfaction through Google ratings. The goal is to provide insights that can help diners make informed decisions about where to eat, balancing safety and quality.

The analysis starts by identifying the safest areas to dine in NYC, visualized through a geographical heat map. Alongside, we reveal the cuisines that tend to violate health regulations the most, as well as those with better safety records. The dashboard allows users to explore inspection grades by borough and cuisine, highlighting patterns of food safety across different regions and dining styles.

Moving deeper, trends in food safety over time are displayed, showing fluctuations in restaurant grades and how these may correspond to external factors or city-wide initiatives.


### Dashboard 1:

<div class='tableauPlaceholder' id='viz1727902305484' style='position: relative'><noscript><a href='#'><img alt='NYC Restaurant Health ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book8_17278909253210&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book8_17278909253210&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book8_17278909253210&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                   
  var divElement = document.getElementById('viz1727902305484');  
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1000px';vizElement.style.height='827px';            
  var scriptElement = document.createElement('script');              
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);              
</script>



Next, in order to analyze the relationship between inspection scores, customer ratings, and price categories, I used Python to clean and merge two datasets: NYC restaurant inspection data and Google ratings data. This involved handling missing values, standardizing formats, and ensuring compatibility between both datasets. The combined dataset helped me in getting insights into dining safety and customer satisfaction.

Finally, I examine the relationships between inspection scores, customer ratings, and price categories. Contrary to common assumptions, the data reveals a very weak correlation between these factors, challenging the idea that higher prices or higher ratings always equate to safer dining environments. This analysis, along with calculating correlation values for the same, helps debunk myths surrounding dining quality and food safety.

### Dashboard 2

<div class='tableauPlaceholder' id='viz1727902397001' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book7_17278907144350&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book7_17278907144350&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book7_17278907144350&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>             
<script type='text/javascript'>                   
  var divElement = document.getElementById('viz1727902397001');                   
  var vizElement = divElement.getElementsByTagName('object')[0];                  
  if ( divElement.offsetWidth > 800 ) { 
    vizElement.style.width='1000px';
                                       vizElement.style.height='827px';
                                      } else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';
                                                                                  vizElement.style.height='827px';
                                                                                 } else { vizElement.style.width='100%';vizElement.style.height='1277px';
                                                                                                                         }                     var scriptElement = document.createElement('script');                   
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);              
</script>





Below are the code snippets showing the data merging and correlation analysis that I did using python.

#### Calculating Correlation between Google ratings and price category

<img width="808" alt="image" src="https://github.com/user-attachments/assets/01966341-97da-484d-8002-3e522ad427ae">


#### Calculating Correlation between Google ratings and inspection scores

<img width="779" alt="image" src="https://github.com/user-attachments/assets/eea510f0-4eca-48b8-a24c-a96ba877f72d">

#### Calculating Correlation between inspection scores and price categories

<img width="780" alt="image" src="https://github.com/user-attachments/assets/8c41a4b5-d89b-4c15-9e81-2f77c76ea3cc">



Call-to-Action: By exploring these visualizations, users can better understand the safety landscape of NYC’s restaurants and make informed choices.


# User research 

## Target audience and Participant Demographics

The primary audience for my story are:
Consumers/Diners/Visitors: NYC locals who frequently eat out and want to make informed choices about where to dine based on food safety and customer satisfaction. Also, visitors to NYC who are unfamiliar with the city's dining scene might appreciate having a data-driven resource to ensure they pick both safe and well-reviewed restaurants
Restaurant Owners and Managers: They can use the insights from these dashboards to gauge how their establishments compare with competitors in terms of food safety and customer perception. They could also use the information to improve their operations, focusing on areas of weakness revealed by the data.


My data analysis can also be useful for Health Inspectors and Regulators who can get insights from the data can aid in policy-making and enforcement strategies.

For the purpose of this user research, I picked three participants belonging to the same target audience particularly the audience. The participants were chosen on the basis of their demographics, dining frequency, and familiarity with data dashboards.

## Interview script


| Goal | Questions to Ask |
|------|------------------|
|   Background Questions      |       1. How often do you eat out at restaurants? 2. What factors influence your choice of restaurant? 2. Are you aware of health inspection scores when choosing where to eat? 3. Do you prioritize price, quality, or safety when dining out?            |     
|  Clarity and Usability    |   1.  Were you able to quickly understand each of the visualizations? 2. Did you find any part of the dashboard confusing or unclear?              |
|   Insights and Engagement   |         1. What insights did you gain from the dashboard? 2. Did any particular visualization spark your curiosity or interest? 3. Is there anything you were left wondering about after exploring the dashboard?         |
|   Content, Presentation   and design |       1. Does the order and flow of information make sense to you? 2. Are there any words or phrases that were difficult to understand? - Do the images and visualizations contribute to your understanding?    3. Can you recognize a theme or color scheme? How effective is it?          |
|   Target Audience and Design   |       1. Who do you think is the target audience for this dashboard? |
|   Suggestions and Improvements   |         1. What changes would you suggest for this dashboard and why? 2. Is there any additional information or data you would like to see included?         |




## Interview findings

### Interviewee 1: Asian, Student, M(25) , Planning to visit Nyc
#### Key Insights:
- Most visualizations understandable and will be really useful for NYC consumers and restaurant managers.
- Suggested reordering legends for clarity and using a consistent color theme ( Red, Peach and Green) so that I won’t have to add multiple legends 
- Not familiar with the term "BORO" and "Correlation".
- Didn’t understand the purpose of a chart in Dashboard 2 with the current storyline. 
- Try Highlighting top 10 Cuisines to avoid the cluttering of labels in the Inspection Grade by Cuisine in Dashboard 1
#### Key Quotes: *“Legends should be placed in way its easier for the eyes to interpret graphs”*
#### *“I am new to the concept of correlation, maybe look a simpler way so that a wider audience can understand”*


### Interviewee 2: Asian, Working Professional, M(28) , NYC
#### Key Insights:
- The first dashboard was easy to understand and provided interesting insights. 
- However, the scatterplot in particular in the Dashboard  2 was difficult to understand in the flirst glance ; a box plot might be clearer.
- The "Inspection Grade by Cuisine and Boro" graphs  sparked their curiosity.
- Legends should be ordered correctly, and a consistent color theme is recommended. 
- The map and bar graph showing grades by boro both are representing the same data or idea; consider removing one.
- Provide context about the scoring system in Dashboard 2 with a brief explanation.
- Use catchy titles for scatterplots to highlight findings instead of just stating correlation values in the subtitle.
Ensure Dashboard 2 clearly indicates it's about NYC.
#### Key Quote: *“Give some context to the viewers in Dashboard 2 about the scoring system by writing a small paragraph”*

### Interviewee 3: : Asian, Working Professional, F(37), New Jersey
#### Key Insights:
- I like the color theme being used for the map and bar chart in the Dasbboard 1, but try to use the same color theme for ther graphs as well
- Line graph does not have a axis label
- The alignment of the charts in the Dashboard 1 are not quite right
- The idea of myth busting dashboard is really good
- The title are great in Dashboard 1
- In Dashboard 2 , the story telling is missing, try to change the titles for the graphs so that they talk more about the story and not just show data
#### Key Quote: *“I’m not quite sure what correlation means here, you can probably define it on the dashboard”*

# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

Text here!

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Interviewee suggested using a consistent color theme across all graphs. | I will apply the same color palette (Red, Peach, Green) to all visualizations for uniformity |
|   Legends and labels not placed correctly found confusing and cluttered.                                       |          Reorder legends for clarity. Since I'll have a common color theme I can use the same legend for most the charts in the Dashboard. I'l also add labels for the line chart axis.                                                               |  Users were unclear about the concept of correlation.
|               Add a brief explanation/defination of correlation on the dashboard to aid understanding and use more descriptive titles that depict the correlation findings                       |      The map and bar graph showing grades by boro present the same data.                                                                           | Remove one of these graphs to streamline information.
|                Dashboard 2 lacked storytelling element                          |                                                              Revise titles to be more descriptive and narrative-focused. Provide context about the scoring system with a short paragraph.                   |  Misalignment of charts in Dashboard 1 was noted.
|  Adjust graph alignment for better visual flow and coherence. |                                                               Make sure Dashboard 2 tells that viewers that the infromation is about nyc                  | I'll make sure that Dashboard title mention NYC  |
|          Dashboard 1's  Inspection Grade by Cuisine  chart looks cluttered           |                  Display only top 10 cuisines to reduce clutter in the y-axis       |



## Final Thoughts
These changes aim to enhance clarity, engagement, and usability and enhance the storytelling of the dashboards, making it more informative and accessible to the audience. By addressing these key areas, the dashboard will better serve its intended purpose of about making diners and restaurant managers aware of the the restaurant inspection data debunking myths about restaurant safety and quality.


