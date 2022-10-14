![](https://github.com/MarkMH/emojis_tweets/blob/4b6a14d95ba62b5a1a016c269f760616b0d432cb/images/banner_emojis_tweets.jpg)

<p align="justify" style="text-align:justify"> 
This project is a collaborative effort with <a href="https://www.linkedin.com/in/lennart-struth-b10524180">Lennart Struth</a>. The jupyter notebook is used to discuss the implementation details and the methodology used, since the data is not freely available as it is part of an ongoing study at the Barcelona School of Economics, Pompeu Fabra University.    
</p>


<p align="justify" style="text-align:justify"> 
Should you intend to use the same code, make sure that your data, tweets, are stored in a folder named "data":
</p>

![](https://github.com/MarkMH/emojis_tweets/blob/4b6a14d95ba62b5a1a016c269f760616b0d432cb/images/carbon_load_data.png)

---

<p align="justify" style="text-align:justify"> 
Note that we have created the list of emojis expressing positive and negative emotions. Thus, the list is certainly not exhaustive, but it is customized to our use case: First, we consider all skin tones of an emoji, if available, since the underlying Unicode is not identical for the same emoji with a different skin tone. Second, we face the obstacle of a small dataset, which is why we attempt to include as many emojis as possible. If you do not face the same problem, we recommend using less emojis in each list, reducing the list to emojis strongly associated with very clear emotions. 
 </p> 

![](https://github.com/MarkMH/emojis_tweets/blob/4b6a14d95ba62b5a1a016c269f760616b0d432cb/images/carbon_emoji_label.png)

---

<p align="justify" style="text-align:justify"> 
Lastly, be aware that we encounter a significant imbalance of 3.5 to 1 in positive to negative tweets. How we deal with this issue is discussed in the jupyter notebook.
</p>