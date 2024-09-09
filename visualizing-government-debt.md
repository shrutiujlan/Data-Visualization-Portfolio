| [home page](https://shrutiujlan.github.io/tswd-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt

## Part one: Working with web-based visualization tools and data

![image](https://github.com/user-attachments/assets/33bc26ca-2b71-4e52-8714-007fa714d948)

For Part 1, I used the OECD’s online visualization tool to create a bar chart that displays government debt-to-GDP ratios for several countries for the year 2022. From the website I downloaded the chart as a .png file and placed it in my GitHub portfolio page.

This chart provides a clear view of the debt-to-GDP ratios for various countries for the year 2022, making it easy to quickly compare their financial situations based on the bar's height.

## Working with Tableau

<div class='tableauPlaceholder' id='viz1725842261045' style='position: relative'><noscript><a href='#'><img alt='Trends in General Govenement Debt as % of GDPSource: https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html?oecdcontrol-3122613a85-var3=2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment2_17258422362600&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment2_17258422362600&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment2_17258422362600&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1725842261045');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Steps in Tableau:

1. Imported the OECD dataset and configured the Time column as a Date field.

2. Placed Time on the Columns shelf, Value on the Rows shelf, and Location on the Marks card to represent data by country.

3. Sorted countries by their average debt-to-GDP ratio in descending order to highlight those with higher debt levels.

4. Applied the Orange-Blue Diverging gradient with 100 as the center point, to make it easy to distinguish between countries with debt above or below 100% of GDP.

5. Filtered the data by removed countries with missing data (such as Colombia)

6. Added a clear title, source of data.

7. After publishing to Tableau Public, I copied the embedded code and inserted it into this Markdown file to render the chart in my Github portfolio.

Observations:

1. High Debt Levels: Countries like Japan and Greece consistently show high debt-to-GDP ratios, highlighted in darker shades, indicating persistent fiscal challenges
2. Comparative Analysis: The heat map allows for easy comparison between countries, identifying which ones have maintained stable debt levels and which have fluctuated.
3. Economic Events: Periods of economic crisis or recovery can be observed through shifts in color intensity.

## Part three: create your own visualization

<div class='tableauPlaceholder' id='viz1725900825582' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP Ratio Trends in European CountriesSource: https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html?oecdcontrol-3122613a85-var3=2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment2-part3_17258544812150&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment2-part3_17258544812150&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment2-part3_17258544812150&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>             
<script type='text/javascript'>                  
    var divElement = document.getElementById('viz1725900825582'); 
    var vizElement = divElement.getElementsByTagName('object')[0];    
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';   
    var scriptElement = document.createElement('script');            
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';     
    vizElement.parentNode.insertBefore(scriptElement, vizElement);       
</script>

## Visualization Comparison and Analysis

### Dataset
For part 3, I have chosen a subset of the dataset - General government debt, I have selected data from three European countries specifically: Ireland, Belgium, and Greece—due to their distinct trends in government debt over the given period.Ireland has seen a big increase in debt, especially after the financial crisis. Belgium, on the other hand, has managed to reduce its debt over time. Greece experienced a sharp rise in debt during its financial crisis. Comparing these countries helps us understand how different economic situations and government policies can affect a country's debt.

### Bar Chart (Part 1)
The bar chart provides a clear, straightforward comparison of general government debt as a percentage of GDP for multiple countries in 2022. This visualization is effective for quickly identifying which countries have the highest and lowest debt levels.

### Heat Map (Part 2)
The heat map offers a different perspective by focusing on the intensity of debt levels across countries and time periods. It allows for a quick assessment of which countries have consistently high or low debt-to-GDP ratios over the years. The use of a color gradient makes it easy to spot trends and outliers, providing a comprehensive overview of the dataset.

### Line Chart (Part 3) 
I chose the line chart for part 3 to illustrate the trends in debt-to-GDP ratios over time for European Countries Greece, Belgium, and Ireland over the period from 1995 to 2019. Greece (blue line) shows a significant increase in its debt ratio, particularly during the financial crisis around 2010, reflecting severe economic challenges. Belgium's (orange line) debt ratio remains relatively stable with slight fluctuations, indicating consistent fiscal management. Ireland (pink line), on the other hand, experienced a sharp rise in its debt ratio during the crisis, followed by a notable decline, highlighting its recovery efforts. I chose this visualization as it highlights trends, peaks, and troughs, allowing for a detailed examination of each country's fiscal trajectory. It is especially useful for identifying long-term patterns and the impact of economic events, making it the best choice for analyzing trends in debt-to-GDP ratios. In the vitualization I chose distinct colors (Blue, Pink, Orange) to enhance clarity and help convey the data's story by visually distinguishing between different countries and trends. Additionally, I've added a title, which is specific to enhance clarity and implies as comparative analysis, which can help set the context for viewers.

Review and Reflection
After reviewing my work, I ensured that the process is clear and easy to follow for someone unfamiliar with the dataset. Starting with getting the data, I filtered the data by location to focus on Greece, Belgium, and Ireland, and then selected a line chart to illustrate their debt-to-GDP trends. This visualization effectively highlights the contrasting fiscal trajectories of these countries in Europe. I'm pleased with how the chart clearly communicates key insights, making it a strong example of my analytical work.


