# Spooky Text Analysis: Lovecraft is the winner (and more)
### A story of sentiment analysis 

Edgar Allan Poe, Mary Wollstonecraft Shelley, and H.P. Lovecraft are famous for their tales of mystery and horror. The files contain my investigation of the authors' texts using various text mining approaches, including sentiment analysis and character exploration. 

I began my spooky text study with a exploratory data analysis that analyzed word frequencies. 

The three distinct and rather dissimilar patterns that surfaced from the word frequency analysis prompted me to do a deeper dive on sentiment analysis, to find out if these themes indeed map back to the entire narrative. 

Word-level analysis presented the overall sentiment score (between positive and negative) as well as changes in sentiment throughout the trajectory of each author's narrative. Lovecraft's text champions negativity and maintains it throughout his entire narrative. Mary Shelley's text, the most positive in nature, exhibits extremes, indicating greater fluctations between positive and negative moods, while Poe's is relatively stable. 

A bi-gram sentiment analysis was then performed to account for the effect of negating words in erroneous contributions to the sentiment score. For example, negating words like "never" and "not" that precede "doubt" and "fail" (both with negative sentiment scores) should actually be reversed. Indeed, the bigram analysis corrected the initial sentiment scores. What's more interesting to note, however, is that the bigram analysis revealed more negativity in Lovecraft's while making Poe's and Shelley's texts more positive. 

Finally, for my last chunk of analysis, I examined the role that gender may play in each author's text, by way of the ratio of "significant" female and male characters, defined as those whose names were mentioned 20+ times in the text. Shelley's text had more "significant" female characters than male characters, while Poe and Lovecraft had very few if any "significant" female characters that were distinguishable based on name alone. 

The above results inspired me to investigate Shelley's characters - how their development, roles, and personalities differ. I chose Raymond and Perdita as subjects for this additional analysis; by isolating words that follow the mention of Raymond and Perdita's names, I deduced that Perdita may exhibit more subdued and docile tendencies than Raymond, who was followed by more action verbs than Perdita. 



