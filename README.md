# Mullti-task-Tweet-Classification-Using-BERT-Model

# Table of Contents
1. [Introduction](#Introduction)
2. [Data](#OurData)
3. [Assignment](#assignment)
4. [Help](#help)

***
# Introduction
This is the repository for the Mullti-task-Tweet-Classification-Using-BERT-Model. It consists of three tasks in Twitter, all framed as multi-task tweet classification. 

# Our Data

These are the three datasets for this project, with its corresponding labels (more details about the format in the [datasets](https://github.com/cardiffnlp/tweeteval/tree/main/datasets) directory):

- **Emotion Recognition**: [SemEval 2018 (Emotion Recognition)](https://www.aclweb.org/anthology/S18-1001/) - 4 labels: `anger`, `joy`,`sadness`, `optimism`

- **Irony Detection**, [SemEval 2018 (Irony Detection)](https://www.aclweb.org/anthology/S18-1005.pdf) - 2 labels: `irony`, `not irony`

- **Sentiment Analysis***, [SemEval 2017 (Sentiment Analysis in Twitter)](https://www.aclweb.org/anthology/S17-2088/) - 3 labels: `positive`, `neutral`, `negative`

### How to use

This code was created in Google Colab, and by default it should run smoothly on any program. 
Before use, we advise you change the file path to the path your file is stored. 
The script takes the TweetEval gold test labels and the predictions from the "predictions" folder by default, but you can set this to suit your needs as optional arguments.

(this script would output the evaluation analysis only, and not an actual classification task.)



