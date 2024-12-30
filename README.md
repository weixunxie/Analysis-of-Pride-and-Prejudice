# Analysis-of-Pride-and-Prejudice

## Introduction

This project delves into Jane Austen’s beloved novel Pride and Prejudice, a timeless story exploring love, social expectations, and personal growth in Regency England. The novel follows the lives of the Bennet family, focusing on protagonist Elizabeth Bennet and her romantic relationship with the wealthy yet distant Mr. Darcy. Through themes of class, marriage, and personal growth, Austen crafts a profound commentary on human nature using wit, irony, and sharp observations.

Using modern computational tools, this project analyzes the text of Pride and Prejudice to uncover patterns, themes, and emotional dynamics that might not be immediately evident through traditional reading. The analysis includes word frequency, sentiment trends, and bigram (word pair) relationships to provide fresh insights into Austen’s narrative techniques.

## Project Objectives

The project is structured into three main analyses:
	
 1.	Word Frequency Analysis
	
 •	Highlight the 20 most common words in the text.
	
 •	Explore their connection to the novel’s themes and characters.
	
 2.	Sentiment Analysis
	
 •	Examine the emotional tone of the novel, focusing on how sentiments such as love, pride, and prejudice evolve throughout the story.

 •	Compare positive and negative word trends over time.

 3.	Bigram Analysis

 •	Identify and visualize word pairings to understand relationships and recurring themes.

 •	Use network graphs to highlight key connections between characters, phrases, and ideas.

## Key Findings

### Top 20 Most Common Words
	
 •	Most Frequent Words: The most common words include names such as “Elizabeth,” “Darcy,” and “Bennet,” indicating the centrality of characters and relationships in the story.
	
 •	Neutral Words: Many frequent words are neutral in tone, emphasizing the narrative’s focus on interactions and events rather than overt emotional language.


By analyzing sentiment distribution alongside word frequency, we can determine whether frequently mentioned topics or characters are associated with positive or negative sentiments, providing insights into their roles in key emotional moments of the story.


### Sentiment Analysis
	
 •	Positive and Negative Words:
	
 •	Positive words such as “love,” “pleasure,” and “happy” emphasize moments of joy and romance.
	
 •	Negative words like “miss,” “object,” and “impossible” reflect themes of obstacles and conflict.
	
 •	Sentiment Trends Over Time:

 •	Positive Sentiment: Shows a steady upward trend, reflecting increasing moments of resolution and optimism.

 •	Negative Sentiment: Declines steadily, suggesting a decrease in conflict and challenges as the story progresses.

These trends illustrate how Austen crafts an emotional journey, starting with tension and misunderstandings and culminating in a positive resolution.

### Bigram Analysis

Using the tidytext and igraph packages, a bigram network graph was generated to explore word pair relationships within the text. Key insights include:
	
 •	Character Connections:
	
 •	Words like “Elizabeth” and “Darcy” dominate the graph, highlighting their central roles in the narrative.
	
 •	Proximity between their names indicates their strong connection, consistent with the novel’s focus on their evolving relationship.

 •	Dialogue and Descriptions:
	
 •	Words like “reply,” “cry,” and “watch” are often used in descriptions and dialogue involving characters, revealing their narrative roles.
	
 •	Recurring Themes:

 •	Phrases such as “ten thousand pounds” and “half an hour” reflect recurring themes of wealth, time, and societal expectations.

The bigram analysis provides a visual summary of narrative structures, emphasizing Austen’s thematic focus and narrative style.

## Tools and Methodologies
	
 •	Programming Language: R

 •	Libraries Used:
	
 	tidytext: For text preprocessing and sentiment analysis.
	
 	igraph: For bigram network graph creation.
	
 	ggplot2: For visualizing word frequencies and sentiment trends.
	
 	Datasets: The full text of Pride and Prejudice was tokenized and analyzed.

## Conclusion

This project’s exploration of Pride and Prejudice through digital text analysis highlights Jane Austen’s mastery of language and storytelling. Key takeaways include:
	
 1.	Language and Themes:
	
 •	The frequent appearance of emotionally charged words and key characters’ names underscores the novel’s focus on personal relationships and social commentary.
	
 2.	Sentiment Analysis:
	
 •	The upward trajectory of positive sentiments reflects the story’s progression toward resolution, showcasing Austen’s optimistic narrative tone.
	
 3.	Bigram Analysis:
	
 •	Visualizing word pair relationships reveals underlying structures and recurring themes, offering new perspectives on the novel’s content.

This analysis demonstrates how modern computational tools can enhance our understanding of classic literature, revealing patterns and themes that deepen our appreciation of Austen’s artistry.


## Citation
	•	Jane Austen, Pride and Prejudice
	•	Libraries: tidytext, igraph, ggplot2
