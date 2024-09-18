| [home page](https://shrutiujlan.github.io/tswd-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique By Design - Assignment 3

## Step one: the visualization

Title: The Cheapest Ways to Get Your Protein

Link to the Vitualization: https://www.thebodybuildingdietitians.com/blog/how-cost-effective-is-your-high-protein-diet


Snippet:

![image](https://github.com/user-attachments/assets/04a46314-0158-4348-b3e4-183dbed50cdd)


### Why I chose this particular data visualization?

I chose this visualization because I'm into fitness and monitor my protein intake closely, with a particular interest in vegetarian options. The chart effectively highlights the cost per 30g of protein, allowing me to compare the cost-effectiveness of different sources.

## Step two: the critique

Critique of the Data Visualization based on Stephen Few's Data Visualization Effectiveness Profile
#### Usefulness
Rating: 8/10
The visualization effectively communicates the cost per 30g of protein for various products, which is valuable for individuals interested in cost-effective protein sources.
#### Completeness
Rating: 6/10
The visualization does not include all items from the dataset, such as canned black beans and cheddar cheese, and also whether an item is vegetarian vegan or non vegetarian ,which could provide a more comprehensive comparison.
#### Perceptibility
Rating: 8/10
The bar chart format is clear, but some items from the dataset are missing, which could lead to incomplete understanding.
#### Truthfulness
Rating: 6/10
There are discrepancies between the dataset and the visualization values (bar length ), which could affect the perceived accuracy.
#### Intuitiveness
Rating: 8/10
The chart is intuitive and straightforward, but the missing data might confuse users familiar with the dataset.
#### Aesthetics
Rating: 7/10
The design is clean, but the color scheme could be improved  for differentiating b between vegetarian vegan or non vegetarian for better differentiation between bars.
#### Engagement
Rating: 7/10
The visualization is engaging, but including more data points could enhance interest and discussion.

### What I Don't Like
Cluttered Illustrations: The food item illustrations are cluttering the visualization and can distract from the data. They add little value since the labels already indicate the food item. The chart discusses 30g portions, but the illustrations display entire packages, which may mislead users.

Discrepancies: There are inconsistencies between the bar heights and the dataset values, which could confuse viewers eg. According to the dataset  for 30g of protein from Salmon costs around 3.53 but the visualization shows it around 4 

Calorie Information: The calorie count is included but doesn't add value when the focus is on cost-effectiveness. Additionally, the dataset does not provide the calorie value for each food item, making the data source unreliable.

Missing Data: Some items, especially those relevant to vegan and vegetarian audiences, are missing from the dataset.

Bar Width: The bars are too wide, contributing to a cluttered appearance. Narrower bars would improve clarity.

Y-Axis Scale: The scale could use smaller increments (e.g., 0.5) to better highlight small cost differences.
No Data Source: The data source is not included, which affects the credibility of the visualization.

### What I Like
Intuitive Design: The bar chart is straightforward to understand it clearly does the cost comparison between various food sources

Clean Layout: Despite some clutter, the overall design is clean and organized.

Engaging Presentation: The visualization is engaging and draws the viewer's attention.

Clear Context: The chart provides context with a clear title and labels, making it easy to grasp the main idea.

### Recommendations
Simplify Illustrations: Remove the food illustrations to reduce clutter.

Enhance Color Contrast: Use more distinct colors for each food category (vegan, vegetarian, and non-vegetarian) to improve differentiation.

Ensure Data Accuracy: Align the bar heights with the dataset values to ensure consistency.

Focus on Relevant Data: Remove calorie information if it doesn't contribute to the cost analysis.

Include Comprehensive Data: Add missing items to the dataset to cater to diverse dietary preferences (vegan, vegetarian, and non-vegetarian).

Adjust Bar Width: Narrow the bars slightly for a cleaner appearance.

Refine Y-Axis Scale: Use smaller increments to make cost differences more apparent.

Include Data Source: Add the data source to enhance the reliability of the visualization.

Primary Audience

The primary audience is likely individuals interested in nutrition and cost-effective protein sources. The visualization is somewhat effective for this audience but could be improved with more comprehensive data, such as categorizing foods by type (vegan, vegetarian, and non-vegetarian)


## Step three: Sketch a solution

<div class='tableauPlaceholder' id='viz1726551811378' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17264619539730&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_17264619539730&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17264619539730&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>       
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1726551811378');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
if ( divElement.offsetWidth > 800 ) {
vizElement.style.width='1000px';vizElement.style.height='827px';
} else if ( divElement.offsetWidth > 500 ) { 
vizElement.style.width='1000px';vizElement.style.height='827px';
} else { vizElement.style.width='100%';
vizElement.style.height='727px';
}                     
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>


I chose a bar chart to represent the protein data because it clearly displays the cost per 20g of protein across different food sources, it makes it easy to compare prices at a glance and is intuitive and familiar to most viewers. The use of bars allows for straightforward visual comparison, highlighting differences in cost effectiveness.

To transform the original visualization into my first draft, I used the following process based on the recommendations above:

1. I began by importing the dataset into Tableau 
2. Placed Cost per 20 grams of protein on the Columns shelf and Protein Source on the Rows shelf.
3. Sorted protein sources by cost in ascending order to show affordability.
4. Clicked on show marked labels, change the decimal points.
5. Created a calculated field to categorize protein sources as vegan, vegetarian, or non-vegetarian. Applied these categories to the Color mark for visual differentiation.
6. Assigned specific colors to each category: light green for vegan, dark green for vegetarian, and brown for non-vegetarian.
7. Removed the grid lines.
8. Adjusted the chart title to make it clear and engaging and also added the data source.
9. Published the visualization to Tableau Public. Embedded the chart into your GitHub portfolio using Markdown.


## Step four: Test the solution

#### Script 

Questions to ask: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find confusing?
  
- Do any design elements (like gridlines, and colors) distract you from the visualization? 

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results:

| Question | Interview 1 student, early 20's | Interview 2 student, mid  20's|
|----------|-------------|-------------|
|Can you tell me what you think this is?     |     Statistical representation of the cost of various food items containing 20g protein         |   It is a bar plot representing cost of various protein sources for 20 gr of protein          |
|Can you describe to me what this is telling you? |    Various protein sources in vegan vegetarian and non vegetarian diet and their respective cost per 20g of protein.     |      It gives us the cost comparison between various foods for 20 g of protein       |
|Is there anything you find confusing?   |     It is pretty clear       |    It appears pretty straightforward   |
| Do any design elements (like gridlines, and colors) distract you from the visualization? | I find the brown color used for non-vegetarian food items too bright | No |
| Who do you think is the intended audience for this?    | General population, nutritionists, and dieticians            |   People who are looking to monitor their protein intake and their expenses |
|Is there anything you would change or do differently?   |   And add the average daily protein requirement of an adult according to body weight. The bar colors aren't of the same tint, shade, maybe change that so that its more pleasing to watch        |    I would use a different color for vegetarian bar as its similar to vegan. Also, maybe change the title, make it sound more catchy |

Synthesis: 

#### Patterns in Feedback:
1. Both interviewees correctly understood the visualization as a cost comparison of protein sources per 20g, which shows that your design is effective in communicating the primary message.
2. They identified the indended audience correctly 
3. Both interviewees mentioned some issues with the color. The first interviewer mentioned that the colors aren't as aesthetically pleasing or too bright, and the second interviewer mentioned that colors arent distinct enough for each food category.
4. The second interviewer mentioned the title could be more engaging
#### Learnings from feedback
1. Colors play a major role in the interpretation of the data in virtualization, they can also impact where the viewer will focus first
2. Title helps a lot in giving context to the viewers  
#### Updated Design Changes for Final Redesign:
Color Palette Consistency: Interview 1 mentioned that the colors should be of the same tint or shade for a more pleasing visual experience, I will try to use colors from the color palettes defined by Tableau.  Additionally, Interview 2 mentioned that the vegetarian bars look too similar to vegan bars. I’ll use a more distinct color scheme where each category (vegan - green, vegetarian - yellow, non-vegetarian - brown/red) to ensure it has clear differentiation but is cohesive in terms of style. 
Catchier Title: Instead of the current descriptive title, I’ll try something more eye-catching like "How Much Does 20g of Protein Really Cost?" This makes the chart more inviting and engaging and also tells a story.

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1726622054510' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;Protein_Cost_17265508664490&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Protein_Cost_17265508664490&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;Protein_Cost_17265508664490&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726622054510');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { 
  vizElement.style.width='1000px';vizElement.style.height='827px';
 } else if ( divElement.offsetWidth > 500 ) { 
  vizElement.style.width='1000px';
vizElement.style.height='827px';
  } else { vizElement.style.width='100%';vizElement.style.height='727px';
         }               
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


To transform my initial visualization into the final redesign, I followed this process based on the feedback:

1. Changed the title to a more engaging one, similar to the original visualization. Included the Currencytupe in the title.
2. Updated the bar graph colors using Tableau’s color palette (similar tint and shade), ensuring distinct colors for each food category.
3. Inspired by Andy Kriebel’s Monday Makeover video on the same dataset, I added an average line from the analytics tab to provide users with a baseline for cost comparison. Link to the video: https://www.youtube.com/watch?v=45pgu_SrZsg&list=PLX-uPHRG0cLb697Ie-ZGSObRLLNhxzJGK&index=54
5. Increased the font size of the title for better visibility.
6. Removed the x axis header as it was not adding any value since the currency types was mentioned in the title
7. Published the visualization to Tableau Public and embedded it into my GitHub portfolio using Markdown.


#### Final thoughts on the process:

I believe the entire process of redesigning the visualization from scratch was a practical and insightful experience. Critiquing the original visualizations allowed me to identify areas for improvement, which I incorporated into the first draft. The interview process provided diverse perspectives and helped me understand viewer needs better. Feedback from class critiques was invaluable in refining the design to be engaging and easy to understand. Overall, this iterative process was crucial in achieving the best possible design.
