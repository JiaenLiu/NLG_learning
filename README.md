# KPG_learning
This repository's purpose is to record some insprition while learn the KPG

## Abstract
The reason why I decide to write this document is that I want to record something I discover during reading these papers. I think these paper is very helpful while doing some NLP research, more specifically, just in Keyphrase generation. To catch the latest technology, these material is very necessary to learn. Without future ado, Let's begin.

## Material
Deep Keyphrase Generation (https://arxiv.org/abs/1704.06879)  
Does Order Matter? An Empirical Study on Generating Multiple Keyphrases as a Sequence (https://arxiv.org/abs/1909.03590)  
One Size Does Not Fit All: Generating and Evaluating Variable Number of Keyphrases (https://arxiv.org/abs/1810.05241)    
An Empirical Study on Neural Keyphrase Generation (https://arxiv.org/abs/2009.10229)  
PositionRank: An Unsupervised Approach to Keyphrase Extraction from Scholarly Documents (https://www.aclweb.org/anthology/P17-1102.pdf)  
Keyphrase Generation (built on OpenNMT-py)  
(https://github.com/memray/OpenNMT-kpg-release/tree/6725b530d52b756db7b60c69b261f9a8c372ce88)  
PositionRank (https://github.com/ymym3412/position-rank)  

## Introduction
As we all know, keyphrases are phrase that summarize and highlight important information in a piece of text. So keyphrase generation (KPG) is a task that automatically predicting such phrase in the given source text. More specifically, one source text can have mupltiple keyphrases and these keyphrase can just be in the original text (i.e., sub-string of) or absent from the source text.   
So this problem is very interesting and important to research. I recommend readers read these papers in the order that I have given. No.1 to No.4 is in the same frame (They use the same code to finish the research.) and No.5 is try to solve this problem is a differnet angle but it does not cover some situations that previous 4 papers have covered. In detial, PositionRank is based on Graph neural network (GNN) which is a novel and light solution for KPG and actually it did a great job compare with previous solutions.  
