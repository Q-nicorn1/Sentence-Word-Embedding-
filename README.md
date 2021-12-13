# Word-Sentence-Embedding

## Introduction
The beginning technique of embedding can only process single words, which uses for example one-hot-encoding to represent words in a sentence. This could be inefficient when we need to deal with large text data; sometimes a word can has multiple meaning(e.g. "class" can mean a course or a hierarchy). Thus, word and sentence embedding can help solve the issues. Word-embedding can translate the semantics and syntaxes of the word and build a vector representation for that. Sentence embedding enlarges the input processing from single words to single sentence, and allows machine to understand text with more information when at sentence-level compared to character/word-level. Pre-trained word embedding is a form of transfer learning, which involves trnasfer the learning(embedding) from one task to another. 

## Project Topic
Investigating on different tensorflow pre-trained models in the topic of Sentence Embedding. Specifically, comparing and analyzing how well these models to interpret groups of input sentences with different nuances of words that has multiple meanings like star (movie/rock star, planet/sun, or
shape) or glasses (a glass of water, glasses to wear, a mirror, sheets of the material, or
even a person’s last name, etc.).

## Approach
We will start by looking up different feasible pre-trained models on keras and tensorflow. We decide to use pre-trained models because those models usually contain rare words that bring more sparity and large parameter than not pre-trained models. We will
look into the similarity score between words to determine the word meaning. One big challenge in
this project is to understand the output results from those pre-trained models and
language bias in the pretrained model dataset as well as keep update with current advanced models. There is also a need to come up with a
metric or standard rules to interpret the meaning and to evaluate the list of numbers after
applying the pretrain models. The following are the models that we have conducted researches
on.

## Models 
### ● Universal Sentence Encoder
This model is mainly used for sentence embedding but can also multitask for things like
sentiment analysis, text classification, sentence similarity, etc,. The encoder has two
models, one is Transformer and the other is Deep Averaging Network(DAN). In order to
determine the inferential relationship between the same words in different sentences,
DAN would be a better choice.
 
### ● Infersent GloVe
Stanford's Glove is a supervised sentence embedding that pretrained by <a href="https://nlp.stanford.edu/projects/snli/">The Stanford Natural Language Inference</a> 
It indentifies relationship between words, which using co-occurence matrix to caluculate the probability of the word.   

## Conclusion
There is no single one model that is the best for sentence embedding, because each model has its best performing text tasks, so better to choose model based on the task(e.g. semantic relatedness or sentiment analysis).

