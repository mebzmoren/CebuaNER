# CebuaNER: A New Baseline Cebuano Named Entity Recognition Model
This repository contains the code and data used in our submission for PACLIC37 

## Dependencies
1. Apify
2. Label Studio
3. Named Entity Recognition with Conditional Random Fields (https://github.com/nlptown/nlp-notebooks/blob/master/Named%20Entity%20Recognition%20with%20Conditional%20Random%20Fields.ipynb?fbclid=IwAR2xhumBtLNsYj9LCz-yGUTvqz72Qo5cr9J1KkhoVif25U3w6f-SaXZdn1Q)
4. Sequence Labelling with a BiLSTM in PyTorch (https://github.com/nlptown/nlp-notebooks/blob/master/Sequence%20Labelling%20with%20a%20BiLSTM%20in%20PyTorch.ipynb)
5. scikit-learn package for Kappa score computing

## Data
The dataset contribution of this study is a compilation of two Cebuano news articles,  [Yes the Best Dumaguete](https://www.facebook.com/search/top?q=yes%20the%20best%20dumaguete) and
the [Filipinas Bisaya](https://www.facebook.com/filipinasbisaya). To further increase the data count, we also incorporated another publicly available dataset from [Sunstar Cebu](https://github.com/rjrequina/Cebuano-POS-Tagger/blob/master/eval/data/scraped/news-raw.txt) pre-collected by independent researcher Arjemariel Requina. The total accumulated and filtered size of the Cebuano dataset is 4258 articles

| Source                  | Original      | Cleaned |  
| ------------------------| ------------- | ------- |
| Yes the Best Dumaguete  | 1484          | 781     |
| Filipinas Bisaya        | 769           | 377     |
| Sunstar                 | 3100          | 3100    |

## Code


## References


## Contact
