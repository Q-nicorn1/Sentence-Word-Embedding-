# Word-Sentence-Embedding

## Introduction
The beginning technique of embedding can only process single words, which uses for example one-hot-encoding to represent words in a sentence. This could be inefficient when we need to deal with large text data; and sometimes, a word can has multiple meaning(e.g. "class" can mean a course or a hierarchy). Thus, word and sentence embedding can help solve the issues. Word-embedding can translate the semantics and syntaxes of the word and build a vector representation for that. Sentence embedding enlarges the input processing from single words to single sentence, and also allows machine to understand text with more information when at sentence-level compared to word-level.      

## Project Topic
Investigating on different tensorflow pre-trained models on the topic of Sentence Embedding, comparing and analyzing how well these model to interpret groups of
input sentences with different nuances of words like star (movie/rock star, planet/sun, or
shape) or glasses (a glass of water, glasses to wear, a mirror, sheets of the material, or
even a person’s last name, etc.).

### Approach
We will start by looking up different feasible pre-trained models on tensorflow. We will
also look into many previous studies or examples to get familiar with the concept and
ways to interpret the query results by using the pre-trained models. One big challenge in
this project is to understand the output results from those pre-trained models and
language bias in the pretrained model dataset. There is also a need to come up with a
metric or standard rules to interpret the meaning and to evaluate the list of numbers after
applying the pretrain models. There are some models that we have conducted researches
on and here they are following:

### Models
We decide to use pre-trained models because those models usually contain rare words that bring more sparity and large parameter than not pre-trained models. The three models selected to test are Universal Sentence Encoder, SentenceBert, and Infersent. Both SentenceBert and Infersent are similar, so we will just demo 2 models of evaluation results.  

### ● Universal Sentence Encoder
This model is mainly used for sentence embedding but can also multitask for things like
sentiment analysis, text classification, sentence similarity, etc,. The encoder has two
models, one is Transformer and the other is Deep Averaging Network(DAN). In order to
determine the inferential relationship between the same words in different sentences,
DAN would be a better choice.
### SentenceBert
 
### Infersent GloVe

## Conclusion
