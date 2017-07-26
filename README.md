# T-SNE-python
T-SNE python is that technique for dimensionality reduction that is particularly well suited for the visualization of high-dimensional datasets.

I was looking for interesting relationships between categories, for example) I can say when the weather is hot electricity usage is higher than normal days.
For this project, I got the dataset from the Portland Criminal report
There were 75 values for each categories, and tried to get the central points for all the categories' values
When I get the one central point for each category, I found which categories have same relationship.
So that I could figured out what do I have to prepare for the next criminal.
When I run the python, the map will be change but the relationships between categories will stable.

With this commends, I added very small values to def Hbeta sumP, because if they have 0 then they can't calculate the values.
So, I put very small value which will not going to effect to results.
To get the results, first, need to change X data text which is values, and labels text which is categories. 
                    second, change Y = tsne data, Y = tsne(X, 2, how many data in a row, perplexity) if we put the reasonable perplexity, then the map will show stable relatioinship map. The perplexity should be lower than number of data in a row. 
                    Third, I put the label commend which can show labels for all the categories. However, the label only can show numbers for the categories.

This images are run the same date and same categories, but different perplexity. You can see which one is more stable image however, similar relationships between categories.

<blockquote class="imgur-embed-pub" lang="en" data-id="a/bjpEP"><a href="//imgur.com/bjpEP"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
