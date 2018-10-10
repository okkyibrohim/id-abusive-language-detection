# id-abusive-language-detection

## About this data
Here we provide our dataset for abusive language detection in Indonesian language. These dataset is provided in two types of labeling:
* In **re_dataset_two_labels.csv**, the dataset are coded into two labels, that are `1` (*not abusive language*) and `2` (*abusive language*);
* In **re_dataset_three_labels.csv**, the dataset are conded into three labels, that are  `1` (*not abusive language*), `2` (*abusive but not offensive*), and `3` (*offensive language*).

For text normalization in our experiment, we build small typo and slang words dictionaries named **kamusalay.csv**, that contain two columns (first columns is the typo and slang words, and the second one is the formal words). Here the examples of mapping:
* beud --> banget
* jgn --> jangan
* loe --> kamu

## More detail
If you want to know how these dataset was build (include the explanation of crawling and annotation technique) and how we did our experiment in abusive language detection in Indonesian language using these dataset, you can read here: https://www.sciencedirect.com/science/article/pii/S1877050918314583.

## How to cite us
This dataset can be used for free, but if you want to publish paper/publication using these dataset, please cite this publication:

**Ibrohim, M.O., Budi, I.. A Dataset and Preliminaries Study for Abusive Language Detection in Indonesian Social Media. Procedia Computer Science 2018;135:222-229.** (Every paper template may have different citation writting. For LaTex user, you can see **citation.bib**).
