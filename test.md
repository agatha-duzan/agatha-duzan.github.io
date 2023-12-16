---
layout: page
title: "Data Story"
permalink: /Data Story/
main_nav: true
---

<p style='text-align: justify;'>  
YouTube is one of the major social media platforms of our generation and people everywhere use it to keep in touch with the world. But how is YouTube used in the light of politics? Do users use YouTube just to catch up with recent news while having breakfast or is it more than that? Our approach is to first analyze the general political interaction on Youtube and compare it to the watching-behaviour of different video categories. Showing that there are indeed differences in the interaction behvaiour in political vs non-political videos, we narrow our research down to understand the differences within the category of political videos. More precisely, we analyze the differences in watching behaviour regarding views about politicians (Trump, Clinton and Obama) and also political orientation (left, center and right). Using the results, we examine how these are in line with the election results in the US. In our last part, we analyze the differences in political topics used by the three groups and test whether the respective sentiment disceprancies are statistically significant between the political orientations.
</p>
  
## About YouNiverse
<p style='text-align: justify;'>  
YouNiverse is a large dataset collection of channel and video metadata from English-language YouTube. The metadata covers over 136k channels and 72.9M videos providing information about the videos realated to their categories, upload date, description ,and interactions statistics. The time frame considered is between May 2005 and October 2019. In addition, YouNiverse provides a time series dataset focusing on channels and the evolution of their views, subscribers, and number of videos over time from early January to the end of September. 
</p>

## About Radicalization Dataset
<p style='text-align: justify;'>  
The radicalization dataset combines a total of 676 politically oriented channels on Youtube, together with their channel id and the respective political category. The dataset also provides information about the videos included in these channels with respect to the upload date and interactions statistics. The channels are then classified according to their affiliation into right, left, or center. 
</p>

## More Politics on Youtube!
<p style='text-align: justify;'>  
In our first part of our analysis, we are examining the general interest in political videos on YouTube. Therefore, we focus on the three categories which potentially could include political videos, that is "News & Politics", "People & Blogs", and "Nonprofits & Activism" and plot the amount of quarterly released videos and the quartaly total views per category. One interesting finding from our analysis of YouTube videos is that the "News & Politics" category seems to be experiencing rapid growth. Specifically, the number of videos in this category appears to be increasing exponentially, and the number of views is following a similar trend. 
</p>

{% include QuarterlyVideos.html %}

{% include QuarterlyViews.html %}

<p style='text-align: justify;'>  
This suggests that there is a high level of interest in this type of content among YouTube users.
</p>

<p style='text-align: justify;'>  
There are a few potential reasons for this growth. It could be that more and more people are turning to YouTube for their news and political information, or that the quality and diversity of content in this category is improving. Alternatively, it could be that the algorithms used by YouTube are promoting this type of content more heavily, leading to increased visibility and engagement.
</p>

<p style='text-align: justify;'>  
Overall, the exponential growth of the news and politics category on YouTube highlights the important role that this platform plays in the distribution of information and the formation of public opinion. It will be interesting to see how this trend continues to evolve over time.
</p>

### It is all Gloom and Doom in politics
<p style='text-align: justify;'>  
In the previous part, we have seen that the interest in political videos is growing rapidly. Thus, we are interested in analyzing the user behaviour and the general interaction with political videos in comparison to non-political videos. Therefore, we analyze the general sentiment per video category and the so defined "Heat metric", which is calculated as follows:
</p>


<img width="550" src="assets/r.jpg">{:style="display: block; margin: 0 auto" }

<p style='text-align: justify;'>  
According to our analysis of the sentiment of 74m YouTube video descriptions, it looks like it is all gloom and doom in news&politics category. In fact, when we compared the sentiment scores of videos across different categories, the news and politics category came out with the lowest scores of all.
</p>
  
<img width="500" src="assets/r.jpg">{:style="display: block; margin: 0 auto" }

  
<p style='text-align: justify;'>  
It was also always the worst overtime.
</p>

{% include QuarterlySentiment.html %}

<p style='text-align: justify;'>
And if that wasn't enough, it also had the highest Heat Metric.
</p>

<img width="500" src="assets/r.jpg">{:style="display: block; margin: 0 auto" }

<p style='text-align: justify;'>
It consistently had the highest Heat overtime.
</p>

{% include QuarterlyHeat.html %}

<p style='text-align: justify;'>
Looks like people are not too happy with current political topics and events happening around the world - It looks like it could use a little bit of good vibes!
</p>


