# Word-Sentence-Embedding

## Introduction
The beginning technique of embedding can only process single words, which uses for example one-hot-encoding to represent words in a sentence. This could be inefficient when we need to deal with large text data; and sometimes, a word can has multiple meaning(e.g. "class" can mean a course or a hierarchy). Thus, word and sentence embedding can help solve the issues. Word-embedding can translate the semantics and syntaxes of the word and build a vector representation for that. Sentence embedding enlarges the input processing from single words to single sentence, and also allows machine to understand text with more information when at sentence-level compared to word-level.      

## Pre-trained sentence embedding models
 We decide to use pre-trained models because those models usually contain rare words that bring more sparity and large parameter than not pre-trained models. The three models selected to test are Universal Sentence Encoder, SentenceBert, and Infersent. Both SentenceBert and Infersent are similar, so we will just demo 2 models of results instead of three.  

## Conclusion
