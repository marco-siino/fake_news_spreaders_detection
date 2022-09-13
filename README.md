# Fake News Spreaders Detection: Sometimes Attention Is Not All You Need
This repo contains data and code for our journal article: "Fake News Spreaders Detection: Sometimes Attention Is Not All You Need". 
For a detailed description of our code, please see the article published by Information (MDPI), by M.Siino et al., 2022.

## Abstract
Guided by a corpus linguistics approach, in this article we present a comparative evaluation of State-of-the-Art (SotA) models, with a special focus on Transformers, to address the task of Fake News Spreaders (i.e., users that share Fake News) detection. First, we explore the reference multilingual dataset for the considered task, exploiting corpus linguistics techniques, such as chi-square test, keywords and Word Sketch. Second, we perform experiments on several models for Natural Language Processing. Third, we perform a comparative evaluation using the most recent Transformer-based models (RoBERTa, DistilBERT, BERT, XLNet, ELECTRA, Longformer) and other deep and non-deep SotA models (CNN, MultiCNN, Bayes, SVM). The CNN tested outperforms all the models tested and, to the best of our knowledge, any existing approach on the same dataset. Fourth, to better understand this result, we conduct a post-hoc analysis as an attempt to investigate the behaviour of the presented best performing black-box model. This study highlights the importance of choosing a suitable classifier given the specific task. To make an educated decision, we propose the use of corpus linguistics techniques. Our results suggest that large pre-trained deep models like Transformers are not necessarily the first choice when addressing a text classification task as the one presented in this article. All the code developed to run our tests is publicly available on GitHub.

## Code
All the code used in our experiments can be executed on Google Colab.

## BIBTEX
@Article{siino2022detection,
AUTHOR = {Siino, Marco and Di Nuovo, Elisa and Tinnirello, Ilenia and La Cascia, Marco},
TITLE = {Fake News Spreaders Detection: Sometimes Attention Is Not All You Need},
JOURNAL = {Information},
VOLUME = {13},
YEAR = {2022},
NUMBER = {9},
ARTICLE-NUMBER = {426},
URL = {https://www.mdpi.com/2078-2489/13/9/426},
ISSN = {2078-2489},
DOI = {10.3390/info13090426}
}

## Useful Links
* [Article PDF](https://www.mdpi.com/2078-2489/13/9/426/pdf?version=1662718934)
* [Official website](https://www.mdpi.com/2078-2489/13/9/426) 
