# **O**ne-**R**estaurant-**Co**rpus (ORCo)
Opinion Summarisation concerns to obtain a structured summary which extracts knowledge from a set of opinions with regard  to  an  entity. Hence, in order to get a significant summary, the task of summarisation must be performed over an opinion set about an unique entity. As far as we know, there are not annotated datasets which are clustered by entity, making thus the workflow of opinion summarisation as an ABSA task not to be evaluable. 

We present **O**ne **R**estaurant **Co**rpus (ORCo), a new set of opinions referred to a single entity in the restaurant domain obtained from Tripadvisor. It contains 50 opinions divided into 277 sentences, being 25 opinions rated as 1  star and 25 as 5 stars in Tripadvisor. 

Each sentence of ORCo has at least an aspect cagetory annotated (Food, Desserts ,Ambience, Staff, Location, General, Price, Drinks, Desserts and None) and a sentiment polarity (-1,0,1) according to three annotators. We evaluate inter-annotator agreement by means of Krippendorff’s Alpha with an Alpha value of 0.7311 for aspect category annotation and multi-k annotator coefficient with a value of 0.9041 for polarity annotation.

The file consists on 4 columns: Review_id in order to group sentences by the review they belong to, Phrase which contains the text of the sentence, AspectCategory which contains the aspects categories of each sentence (separated by ‘/’ if there are various aspect categories in a sentence), Polarity which indicates the sentiment polarity of each sentence and TripadvisorReviewStarRating which contains the number of stars given by the opinion holder in Tripadvisor.


## Citation
Please use the following citation:

```
Publication under review
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
