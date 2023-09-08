# CebuaNER: A New Baseline Cebuano Named Entity Recognition Model
This repository contains the code and data for our paper entitled `CEBUANER: A New Baseline Cebuano Named Entity Recognition Model` accepted for ORAL at PACLIC37. 

Authored by Ma. Beatrice Emanuela N. Pilar, Ellyza Mari J. Papas, Mary Loise Buenaventura, Dane C. Dedoroy, Myron Montefalcon, Jay Rhald Padilla, Lany Maceda, Mideth Abisado, and Joseph Imperial.

## Dependencies
1. [Label Studio](https://labelstud.io/) for the annotation process of NER tags
2. [nlp-notebooks](https://github.com/nlptown/nlp-notebooks/tree/master) for the implementation of Conditional Random Fields and BiLSTM for NER model training.
4. `Scikit-Learn` for Kappa score.

## Data
The dataset contribution of this study is a compilation of Cebuano news articles from two local news stations, Yes the Best Dumaguete and
the Filipinas Bisaya. To further increase the data count, we also incorporated another publicly available dataset from [Sunstar Cebu](https://github.com/rjrequina/Cebuano-POS-Tagger/blob/master/eval/data/scraped/news-raw.txt) pre-collected by independent researcher Arjemariel Requina. The total accumulated and filtered size of the Cebuano dataset is 4258 articles. All the dataset used for this study is purely for non-commercial research purposes and under Fair Use.

| Source                  | Original      | Cleaned |  
| ------------------------| ------------- | ------- |
| Yes the Best Dumaguete  | 1484          | 781     |
| Filipinas Bisaya        | 769           | 377     |
| Sunstar                 | 3100          | 3100    |


## Contact
For questions, you may reach the corresponding author of the study at:

**Joseph Marvin Imperial**\
Faculty Member, Department of Computer Science\
Lab Head, NU Human Language Technology Lab\
jrimperial@national-u.edu.ph
