# **AI MidTerm**
## 1. Clustering Football Players: Is Mbappé More Similar to Ronaldo Than Messi?

There are thousands of professional football players across the world, each with specific skills and unique playing style. Given their quantitative playing attributes, however, it might be possible to determine players with similar playing styles, and find groups of players with (almost) identical qualities.



![Clustering football player.png](https://github.com/alimirash/AI-MidTerm/blob/main/Football%20Player.png)


To accomplish this task, we make use of FIFA 23 player ratings. The dataset contains the information corresponding to over 18000 football players, each with 87 various features. Our goal is to investigate how these players can be assigned to distinctive clusters. First, we assume the players with a rating above 85 (91 players in total), and discard all non-numeric features.




## 2. MDC for OCR: An Attempt to Classify Farsi Digits

A Minimum Distance Classifier attempts to classify an unlabelled sample to a class which minimise the distance between the sample and the class in multi-feature space. As minimising distance is a measure for maximising similarity, MDC actually assigns data to its most similar category.



While MDC might look too basic, it works pretty well in some problems. One of them could be Optical Character Recognition (OCR), where the goal is to distinguish handwritten or printed text characters inside digital images of documents. Here, we aim to apply this technique to the problem of Farsi digits classification. We use a dataset named Hoda, which contains 102353 samples of digits written by candidates of Karshenasi Arshad entrance exam in their registration forms, Figure 2. You are given a shorter version of this dataset in which the images are binary.

