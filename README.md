# COVID-19 What's all the fuss?
Design with data project

## Overview
An inevitable topic this year, we wanted to explore the effects of the global pandemic as it has affected our home city, Toronto. Our aim was to demonstrate patterns between COVID-19 case counts and the ongoing discussion of the virus on social media. 
We sought to potentially identify links between social media activity and actual daily cases, and the hopeful outcome that discussions regarding the virus mean people are taking the situation seriously, keeping up with the news, and not being fatigued by its constant mention or the never-ending safety measures being implemented. Our demonstration was to ideally be depicted through an easy to comprehend, text-based visual animation. 

# Main process
* Demonstrated patterns between COVID-19 case counts and the ongoing discussion of the virus on social media 
* Scraped key phrases in tweets regarding COVID by ScrapeStorm, filtering them by tweet location (Toronto) and months (March to December)
* Found the most frequent words by calculating word frequencies using WriteWords
* Represented the varying frequency (number of appearances) of words within tweets by months by the Height of words
* Represented death cases in Toronto during the same time period by hospital bed changes in size
* Visualized the variation of word frequencies and death cases in Grasshopper:  
- Created a list containing all data (number of words and cases) by month (8 months in all), extruded them using the data as the height (scaled death cases by 0.001 due to its huge amount)
- Visualized those changes by changing number slider, from the first month to the final month
- Applied materials to texts and the hospital bed
* Represent the rate of social activity of the Toronto Public Health account by birds flying around the words, according to data found on SocialBlade
* Analyzed limitations, subjectivity, data bias and the potential of this project

## Potential improvements:
This project could be repeatedly undertaken with data from other cities. 
Studying the relationships between social media activity versus actual case count and pandemic severity in different cities around the world would have differing results.
Increasing the timespan of this project would yield interesting results.
Free-flowing, organically moving birds with more natural appearance yet still linked to representing social network activity. 
Enhancing the representation of case count with different versions of hospital animation.
Adding background design elements and illustrations to create a more complete total scene.

## Conclusion:
What we have learned:
We thought the words with highest frequencies should be “mental health” and “depression” etc., but it turns out to be “support”, “love”, “help”, “thank”, and “vaccine”. Toronto is a warm place with love.
Social media can be both a place for spreading factual truths that people should understand in today’s society, but should also uplifting others through words and support. Unless we manually analyze the tweets containing these words, we don’t know if they have a positive or negative connotation with COVID. Therefore, we are biasing them towards positivity but we won’t know unless we view each tweet individually. Also, the dataset for now is not large enough to conclude the accurate social media trend, a larger dataset is needed to reach a comprehensive understanding.


