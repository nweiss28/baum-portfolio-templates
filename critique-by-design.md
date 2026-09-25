| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design

## MakeoverMonday Project: How Has Democracy Fared? - A World Analysis (2018–2024) 

## Original Visualization: Democracy Index 2024 
<iframe src="https://archive.ourworldindata.org/20260910-011030/grapher/democracy-index-eiu.html?tab=map" loading="lazy" style="width: 100%; height: 600px; border: 0px none;" allow="web-share; clipboard-write"></iframe>

## Step 1: Why I Selected This DataViz
The data visualization used in the Economic Intelligence Unit (EIU)’s Democracy Index reminded me of my capstone research at Gettysburg College;. Although I used different data sources, I similarly studied the state of democratic systems around the world.  This familiarity with the data’s overall context made me feel as if I were part of the primary audience, which gave me a better idea of the types of visual formats that were most effective in conveying democracy and autocracy. 

## Step 2: Remaking the Visualization
Initially, I was leaning in the direction of a bubble chart. The smaller circles would represent less-democratic nations (i.e., those with lower Democracy Indices), with larger ones depicting freer nations. The rough draft looked something like this: 

<img width="auto" height="auto" alt="Screenshot 2026-09-19 022301" src="https://github.com/user-attachments/assets/1f0dfa35-be9d-445c-9a07-d8986db46383" />

Ultimately, I decided to choose something different because I was concerned that too many bubbles, packed so closely together, would confuse the reader. A possible solution was to add labels specifying each bubble’s nation. However, since they were so close together, not every bubble could be labeled; unless the reader hovered over each one, they wouldn't know which bubble corresponded to which nation. Given these potential shortcomings, the bubble chart was out. 

## Step 3: Testing the Visual
In class, I asked a few questions about possible designs and received the following responses:

| Question | Interviewee | Response |

| Is there anything you would improve upon? | Fellow Heinz-MSPPM Student | Suggestion: organize the nations by continent |

| Is there anything you find surprising or confusing? | Fellow Heinz Student | Response: the idea of a bubble chart with that many nations might be too confusing |

Synthesis: 

Although I did not go with a bubble chart, feedback from my classmates and Google Gemini pointed me in a better direction. With the help of my classmates, I was able to categorize the nations in the dataset more concisely. Their feedback also suggested that a bubble chart may not be the best format; when consulting Google Gemini, it reinforced this idea by recommending an alternative dataviz: a scatterplot. In general, my main takeaways from the given feedback were that:

-	Less is more; the data viz may be more concise if certain values are separated by page instead of displayed all at once. As indicated in my completed visualization below, I separated nations based on continent (in alphabetical order) and year (ascending order), giving readers a clear, focused view of democratic trends for the nation of their choice. 

-	Sometimes, the most optimal choice is the simple one. I wanted to create a bubble chart that had many formatting constraints regarding continent, Democracy Index, and year. While they would have likely been doable if I had a better understanding of Tableau, Google Gemini’s idea to create a scatterplot worked out better in the end. In this case, simple was better. 

## Step 4: The Finished Result
<div class='tableauPlaceholder' id='viz1789714587724' style='position: relative'><noscript><a href='#'><img alt='How Has Democracy Fared? - A World Analysis (2018–2024) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ho&#47;HowHasDemocracyFared-AWorldAnalysis20182024&#47;Story1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HowHasDemocracyFared-AWorldAnalysis20182024&#47;Story1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ho&#47;HowHasDemocracyFared-AWorldAnalysis20182024&#47;Story1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'> var divElement = document.getElementById('viz1789714587724'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='1016px';vizElement.style.height='991px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

## References
_https://ourworldindata.org/grapher/democracy-index-eiu_

## AI acknowledgements
_I used Google Gemini to initially suggest formatting options for the bubble chart; in its response, it mentioned using a scatter plot instead, which ended up looking cleaner._

