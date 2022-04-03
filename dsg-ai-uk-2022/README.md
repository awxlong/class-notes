# Solution to Data Science Group Task of Twitter Sentiment Classification 

I was very glad to having participated in the 3-days long event organized by the Alan Turing Institute where a lot of interesting ideas revolving AI were discussed. Topics included AI's role in tackling climate emergency, public policy making and the future of machine intelligence. I was also part of a data science group where we've been tasked on solving a machine learning problem aimed at classifying twitter messages as either pro-climate-emergency or denier of it. Sadly, I had to leave the online discussion group since I had another meeting. This notebook contains some contributions which I've liked to share on this interesting problem. The original notebook is found at https://github.com/alan-turing-institute/DSGaiuk2022. This version has been heavily modified, since the original had about 5 issues where we explore ML techniques to address them. In this notebook, I'm simply tackling the problem described above. 

We used the dataset @ https://www.kaggle.com/edqian/twitter-climate-change-sentiment-dataset to classify twitter feeds as either pro-anthropogenic climate emergency or not. We particularly faced the problem of class imbalance, whereby there was about 7 times more training instances of class 1 than 0. 

Within my allocated group, we discussed data amputation to balance out the training instances. I propose synthetising new data using MLE (or using the mean vector imputation if you don't have enough computational power like I did)

A better solution could include:

- Maybe using LSTM, recurrent neural networks for training
- We also needed to think about tokenization, especially avoiding strings of websites or at least not parsing out cryptic words. 
