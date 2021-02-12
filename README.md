# Project in TDDE16
Final project in course in Text Mining, NLP

## Files
- ext_summaries.ipynb contains model and test code
- dataset_analysis.ipynb contains code to analyse the dataset used
- TDDE16.pdf is the project report

## Evaluation of Unsupervised Text Summarization Algorithms
This work investigates the potential performance gains of using sentence embeddings from S-BERT when using extractive unsupervised text summarization models such as LSA, Clustering and TextRank compared with using TFIDF. The CNN/Daily Mail dataset is used for evaluation with ROUGE scores as metrics. The performance of these models are also measured over the number of sentences allowed in the summary, to study how well the algorithms scales with summary length.

Models that utilize sentence similarity as the main metric for summary generation, such as Clustering, sees the largest performance increase at around 20\% compared to using TFIDF. However, the models that performs better with TFIDF, TextRank and Weighted LSA, still performs best on the dataset. TextRank performs better on shorter summaries, while weighted LSA performs better on summaries with four sentences.

## Evaluation outcome
![perf](https://user-images.githubusercontent.com/46990011/107773112-75b28b00-6d3d-11eb-91da-0e4c1b8b948f.png)  
Read more about evaluation, models, and discussion in the report.

