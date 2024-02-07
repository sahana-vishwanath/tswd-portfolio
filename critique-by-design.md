[home page](/README.md) || [visualizing government debt](/visualizing-government-debt.md)

# Assignment 3 & 4: Critique by Design with Tableau (MakeoverMonday)

## Step 1: Choose a data visualization from MakeoverMonday
The task for this assignment was to critique and redesign an existing visualization. I started off by exploring the [Makeover Monday](https://makeovermonday.co.uk/) website, which contains links from various sources of visualizations that have the potential to be improved. The visualization and data set I decided to explore was from the UNICEF website about [child marriage around the world](https://data.unicef.org/topic/child-protection/child-marriage/).

![child marriage visualization](/child-marriage-viz-original.png)
I was intrigued by the topic of this visualization, and found that the data set for this visualization had a few different data points which would allow me to play around with different visualization options.


## Step 2: Critique the data visualization
Starting off with a critique of this visualization, I initially found it quite pleasing to look at, since there are two clear colors used and there is not an overwhelming amount of data, however, when I started to look into it further, there were some confusing elements (I also did not read the article initially because I wanted to see if I could understand the visualization without context first). The first six regions listed from the left are easy to understand, however, I was confused by the term ‘Least developed countries.’ There is no explanation for which countries this includes - are there countries from the regions previously listed included in this subset? Then the next category listed is world - this did not confuse me as much as a category, however I was confused by the number. How could the number of women married by 18 be 19 for the world, but 37 for the West and Central Africa region? I then realized that these numbers must be percentages, however there is no indication in the visualization that states this. I think instead of using bars for the world and least developed countries, since the purpose of these subsets is comparison, I would have used some sort of horizontal line in a different color.

I also found the two bars used a little confusing. The red bar indicates that it is ‘Women aged 20 to 24 years married by age 15,’ and the yellow is ‘Women aged 20 to 24 years married by the age 18’ - does the percentage of women married by 18 include the number of women married by 15, or is the yellow bar excluding women married by 15 and only has women married by 16-18? I think I would just include the ‘Women aged 20 to 24 years married by the age 18’ rather than separating the two. The notes at the bottom of the visualization also mention that there are certain regions not included in this visualization due to insufficient data, however this information is easy to miss and I think it is an important point to factor in, so I would have played around with placing it somewhere where viewers would see it but not distract from the main visualization. 

One final thing is that I feel like the impact of the fact that almost 40% of young women in certain regions and almost 20% of young women worldwide were married by the age of 18 is not fully felt in this visualization, so another thing I would want to change is hopefully finding a way to make sure that this statistic is highlighted and the full impact is delivered.

I do think overall this visualization is effective in that it gets the main point across relatively quickly of the regions that have the largest amount of women getting married by 15/18, especially since the regions are sorted from left to right, but I think there are some elements that cause confusion once you start to try to really understand the details of what the visualization is trying to say. 


## Step 3 & 4: Sketch & Test out a solution
I then began to explore potential ways to improve this visualization. The first sketch I made was a stacked bar chart. Although I mentioned in my critique that I would only include either the 18 or 15 year old data, I wanted to try to see if there was a way I could display both without it being confusing, which is why I chose a stacked bar chart. This format made it clearer to me that the data for the 15 year old children was a segment of the 18 year old data. I also removed the 'Least developed countries' subset, since I did not think it added value to the original visualization, and instead of having the world average data displayed as another subset, I decided to draw two dashed lines depicting these values. I chose 


## Step 5: Build the solution

<div class='tableauPlaceholder' id='viz1707277563273' style='position: relative'><noscript><a href='#'><img alt='Breakdown of Female Child Marriage Worldwide by RegionDoes not include data from the Middle East, North Africa, North America, and Western EuropeSource: UNICEF https:&#47;&#47;data.unicef.org&#47;topic&#47;child-protection&#47;child-marriage&#47; (2022) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ch&#47;ChildMarriage_17072775408040&#47;Sheet22&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ChildMarriage_17072775408040&#47;Sheet22' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ch&#47;ChildMarriage_17072775408040&#47;Sheet22&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707277563273');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


