# **O**ne-**R**estaurant-**Co**rpus (ORCo)
Opinion Summarisation concerns to obtain a structured summary which extracts knowledge from a set of opinions with regard  to  an  entity. Hence, in order to get a significant summary, the task of summarisation must be performed over an opinion set about an unique entity. As far as we know, there are not annotated datasets which are clustered by entity, making thus the workflow of opinion summarisation as an ABSA task not to be evaluable. 

We present **O**ne **R**estaurant **Co**rpus (ORCo), a new set of opinions referred to a single entity in the restaurant domain obtained from Tripadvisor. It contains 50 opinions divided into 277 sentences, being 25 opinions rated as 1  star and 25 as 5 stars in Tripadvisor. 

Each sentence of ORCo has at least an aspect category annotated (Food, Desserts, Ambience, Staff, Location, General, Price, Drinks, Desserts and None) and a sentiment polarity (-1, 0, 1) according to three annotators. We evaluate inter-annotator agreement by means of Krippendorff’s Alpha with an Alpha value of 0.7311 for aspect category annotation and multi-k annotator coefficient with a value of 0.9041 for polarity annotation.

| Features      | Value |
| ----------- | ----------- |
| Num. Sentences      | 277       |
| Num. Opinions   | 50        |
| Num. Pos. Opinions | 25 |
| Num. Neg. Opinions | 25 |
| Aspect categories | Food, Desserts, Ambience, Staff, Location, General, Price, Drinks, Desserts and None|
| Sentences Polarities value | -1,0,1|
| Interannotator Kripenddorf's Alpha for multi aspect categories annotation | 0.7311 |
| Interannotator multi-k for polarity annotation | 0.9041 |

The file consists on 4 columns: Review_id in order to group sentences by the review they belong to, Phrase which contains the text of the sentence, AspectCategory which contains the aspects categories of each sentence (separated by ‘/’ if there are various aspect categories in a sentence), Polarity which indicates the sentiment polarity of each sentence and TripadvisorReviewStarRating which contains the number of stars given by the opinion holder in Tripadvisor.

This dataset has been employed for the evaluation of an opinion summarisation methodology that it is under review. 

## Example
We show an example of annotation in ORCo dataset:

| Review_id | Phrase | AspectCategory | Polarity | TripadvisorReviewStarRating |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| 0	| The gin and tonic was very small for the price we paid and presented very averagely. 	| Drinks/Price	| -1	| 1 |

First column indicates which opinion the sentence belong to. Second column is the text of the sentence. Third column is referred to the aspect categories discussed in the sentence (separated by '/'). Fourth column is the sentiment polarity of the sentence. Fifth column is referred to the star rating of, in this case, the review 0.





## Citation
López, M., Martínez-Cámara, E., Luzón, M. V., & Herrera, F. (2021). ADOPS: Aspect Discovery OPinion Summarisation Methodology based on deep learning and subgroup discovery for generating explainable opinion summaries. Knowledge-Based Systems, 107455. 
Please use the following citation:

```
@article{LOPEZ2021107455,
title = {ADOPS: Aspect Discovery OPinion Summarisation Methodology based on deep learning and subgroup discovery for generating explainable opinion summaries},
journal = {Knowledge-Based Systems},
volume = {231},
pages = {107455},
year = {2021},
issn = {0950-7051},
doi = {https://doi.org/10.1016/j.knosys.2021.107455},
url = {https://www.sciencedirect.com/science/article/pii/S0950705121007176},
author = {Miguel López and Eugenio Martínez-Cámara and M. Victoria Luzón and Francisco Herrera},
keywords = {Opinion summarisation, Deep learning, Aspect extraction, Subgroup discovery, Interesting rules},
abstract = {Opinion summarisation is concerned with generating structured summaries of multiple opinions in order to provide insightful knowledge to end users. We present the Aspect Discovery for OPinion Summarisation (ADOPS) methodology, which is aimed at generating explainable and structured opinion summaries. ADOPS is built upon aspect-based sentiment analysis methods based on deep learning and Subgroup Discovery techniques. The resultant opinion summaries are presented as interesting rules, which summarise in explainable terms for humans the state of the opinion about the aspects of a specific entity. We annotate and release a new dataset of opinions about a single entity on the restaurant review domain for assessing the ADOPS methodology, and we call it ORCo. The results show that ADOPS is able to generate interesting rules with high values of support and confidence, which provide explainable and insightful knowledge about the state of the opinion of a certain entity.}
}
```

## Contact
Miguel López Campos - miguellopezcamp@ugr.es / miguel.lopez.campos1995@gmail.com


Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

