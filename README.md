# Lab 02: Web Data Collection and Visualization
## 1. Topic & Parameters:
- Topic Keywords: "climate change", "global warming", "greenhouse gases"
- Platform: YouTube
- Data collected:
    - 'video_url': Url link of video
    - 'user_url': Url link of user
    - 'username': YouTube username
    - 'title': Video title
    - 'view_num': Number of views
    - 'created_at': Time the video was created
    - 'shortdesc': Short description of the video
    - 'collected_at': When the video was collected by crawler
## 2. Purpose of Comparison:
I wanted to compare these three different search terms to see how the data collected compared to each other because they all emphasize the same topic but may carry different connotations or understandings. Although _climate change_ and _global warming_ are typically used interchangeably, global warming is mostly understood as a result/consequence of climate change. I also selected _greenhouse gases_ as my third search term because it represents a more specific underlying factor that contributes to climate change and global warming.
## 3. Word Cloud Comparison
### Climate Change
![Climate Change Wordcloud](img/wordcloud-1.png)
Other than 'climate change' itself, some of the bigger words that caught my eye were _warming_, _emissions_, _human_, _impact_, and _issue_. Because these words were some of the most prominant words in each video description, it seems like climate change is usually framed as a manmade problem. These words highlight both scientific aspects as well as social and environmental significance. I would say this word cloud accurately reflects what people discuss when talking about climate change. Some smaller words I noticed were _glaciers_ and _penguins_ which tend to trend on social media because they evoke emotional responses among animal lovers who spread awareness on Antartica glaciers melting (home for the penguins and other animals like polar bears).
### Global Warming
![Global Warming Wordcloud](img/wordcloud-2.png)
Some of the most prominant words in the global warming word cloud are _climate change_, _increasing_, _greenhouse_, and _emissions_. Some smaller words that caught my eye include _rising_, _temperatures_, _levels_, _catastrophic_, and _consequences_. The words in this word cloud carry a similar underlying tone of urgency and warning, suggesting the idea that global warming is often discussed in terms of factors that cause rising temperatures and their consequences. 
### Greenhouse Gases
![Greenhouse Gases Wordcloud](img/wordcloud-3.png)
In the greenhouse gases word cloud, there are many big and prominant words such as _human_, _change_, _effect_, _industry_, _warm_, _levels_, and _atmosphere_. It seems like the descriptions collected from this specific search term tend to talk about effects of the human industry and how these activities impact the atmosphere. This word cloud is a bit different compared to the previous two word clouds as this one seems less urgent in tone and more explanatory. Smaller words include _animals_, _sea_, _habitable_, _sustainable_, _comfortable_, and _planet_, which suggests broader conversations about environmental conditions.
### Overall Comparison
Overall, it appears that while _climate change_ and _global warming_ are typically described with a stronger sense of urgency and consequence, _greenhouse gases_ is framed in more of an explanatory manner. 
## Pattern Reasoning
One possible reason for these patterns is that each search term may be used in different contexts. For example, _climate change_ is the most broad term that is used not only in scientific discussions, but political and social discussions as well. _Global warming_ is typically discussed in relation to its consequences which explains its urgent word cloud. Lastly, _greenhouse gases_ is a much more technical term that is used when discussing educational content which can explain why its word cloud focuses the least amount on emotional language.
## Future Research Improvement
Although using video descriptions did provide an overall understanding into the way these search terms are perceived, the next steps could be including comments in the data collected to get an even more widespread perspective since the comment section can reveal even more opinions from the community. Besides that, analyzing based on location would be a good idea too because environmental laws differ between countries, so this could reveal how differently these search terms are perceived. I think comparing different time frames would also be a good idea for future research because it may potentially show how the tone and words used have changed over time. Especially for _global warming_, seeing as it has become more of a pressing issue as time goes by. 
## Unexpected Findings
One thing that stood out to me was how different the word cloud for _global warming_ was compared to the other two. I originally expected all three word clouds to have the same sense of urgency/danger but I didn't realize that _greenhouse gases_ is typically used in educational settings and the results focused more on long-term sustainability rather than dire consequences. I was also surprised that _polar bears_ didn't show up in any of these word clouds because they are typically the main subject on many social media platforms when it comes to rising temperatures and sea levels. 
## CSV Files:
- [Climate Change Search Results](assets/search-result-1.csv)
- [Global Warming Search Results](assets/search-result-2.csv)
- [Greenhouse Gases Search Results](assets/search-result-3.csv)
