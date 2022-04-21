In this repo, you can find the data and experimental code for our NAACL 2022 paper ["Two Contrasting Data Annotation Paradigms for Subjective NLP Tasks"](https://arxiv.org/abs/2112.07475).

The **0_data** folder contains
1. 200 tweets sampled from [Davidson et al. (2017)](https://github.com/t-davidson/hate-speech-and-offensive-language) along with their original labels
2. Annotation results for those 200 tweets from each of the three groups of annotators (G1, G2 and G3) as described in our paper. There are separate columns for each of the 20 annotators in each group.

**0_guidelines** contains the annotation guidelines that were used for our annotation experiment.

**1_agreement_analysis.ipynb** can be used to reproduce the analysis of inter-annotator agreement in our experiment, which we present in our paper.