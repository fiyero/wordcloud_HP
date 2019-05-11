# Generate word cloud on Harry Potter Series :smile:
https://medium.com/@patrickhk/practice-ntlk-word2vec-pca-wordcloud-jieba-on-harry-potter-series-and-chinese-content-ca6f845b3293

I will briefly demonstrate how to visualize with wordcloud<br/>

## Word Cloud:
Visualization by word cloud is easy and eye catching. It visualizes the top k frequent words in corpus. I encounter problem when I first run the word cloud because there are many junk words, as you can see in below even “said” , “n’t” are highlighted.<br/>
![p1](https://cdn-images-1.medium.com/max/800/1*zoB4FnLTPBgRVHIXt5aYbw.png)<br/>

![p2](https://cdn-images-1.medium.com/max/800/1*fw30J6saQs_ve3JsEDLHig.png)
Although I have already used nltk.corpus.stopwords, there are still a lot of stopwords and junk words. I have to edit the custom stop word list to filter away more useless words. Here is the word cloud after second filtering.<br/>
![p3](https://cdn-images-1.medium.com/max/800/1*F7nxP2VXlqIujQIzHbcd6Q.png)



-------------------------------------------------------------------------------------------------------------------------------------
### More about me
[[:pencil:My Medium]](https://medium.com/@patrickhk)<br/>
[[:house_with_garden:My Website]](https://www.fiyeroleung.com/)<br/>
[[:space_invader:	My Github]](https://github.com/fiyero)<br/>
