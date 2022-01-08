# Awesome NLP Resources for Dutch


A curated list of Resources for Dutch natural language processing (NLP).

# Data
- [OSCAR (**O**pen **S**uper-large **C**rawled **A**LMAnaCH co**R**pus)](https://huggingface.co/datasets/oscar) (~50 GB)  is a huge multilingual corpus obtained by language classification and filtering of the Common Crawl corpus using the goclassy architecture. Data is distributed by language in both original and deduplicated form.
- [Dutch medical NLP](https://github.com/terminalkitten/dutch_medical_nlp) (0.6 GB) is collection of Dutch medical texts  which were used for domain-adaptive pretraining to pretrain Dutch medical language models
- [DpgMedia2019: A Dutch News Dataset for Partisanship Detection](https://github.com/dpgmedia/partisan-news2019) (0.3 GB)  is a dataset consisting of news articles of several Dutch newspapers owned by DPG Media, plus annotations of the perceived partisanship of each of article.
- [DBRD: Dutch Book Reviews Dataset](https://github.com/benjaminvdb/DBRD) (0.2 GB)  contains over 110k book reviews along with associated binary sentiment polarity labels.

# Models

### Pretrained models
- [RobBERT: Dutch RoBERTa-based Language Model.](https://github.com/iPieter/RobBERT) RobBERT is the state-of-the-art Dutch BERT model. It is a large pre-trained general Dutch language model that can be fine-tuned on a given dataset to perform any text classification, regression or token-tagging task.
- [BERTje: A Dutch BERT model.](https://github.com/wietsedv/bertje) BERTje is a Dutch pre-trained BERT model developed at the University of Groningen.
- [GPT-2 Recycled for Italian and Dutch](https://github.com/wietsedv/gpt2-recycle) a multi-stage adaptation method for transfering GPT-2 to Dutch without unnecessary retraining

### Domain specific / finte-tuned models
- [belabBERT 🤧](https://github.com/Joppewouts/belabBERT) a RobBERT model fine-tuned to the classification of psychiatric illnesses
- [Dutch Word2Vec Model](https://github.com/coosto/dutch-word-embeddings) a Word2Vec model trained on a large Dutch corpus, comprised of social media messages and posts from Dutch news, blog and fora.


# Libraries
- [DeepFrog - NLP Suite](https://github.com/proycon/deepfrog) DeepFrog aims to be a (partial) successor of the Dutch-NLP suite Frog. Whereas the various NLP modules in Frog wre built on k-NN classifiers, DeepFrog builds on deep learning techniques and can use a variety of neural transformers.


# Blogs and articles
- [Training a Dutch GPT-2 base model](https://medium.com/deepdesk/training-a-dutch-gpt-2-base-model-5f21dcfa3cd2)
- [Dutch GPT2: Autoregressive Language Modelling on a budget](https://blog.ml6.eu/dutch-gpt2-autoregressive-language-modelling-on-a-budget-cff3942dd020)
- [NLP with R part 5: State of the Art in NLP: Transformers & BERT](https://medium.com/broadhorizon-cmotions/nlp-with-r-part-5-state-of-the-art-in-nlp-transformers-bert-3449e3cd7494)

# Misc
- [Deduce: de-identification method for Dutch medical text](https://github.com/vmenger/deduce), a de-identification method for Dutch medical text

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Bram Zijlstra has waived all copyright and related or neighboring rights to this work.
