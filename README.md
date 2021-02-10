# Turkish-NLP-Preprocessing-module
Preprocessing tool for Turkish NLP that contains tokenizer, normalizer, stop-word eliminator and stemmer.
Developed by Melikşah Türker and Büşra Oğuzoğlu for CMPE561 NLP class project.

https://github.com/meliksahturker

https://github.com/busraoguzoglu

Sentence Splitter and Tokenizer modules have 2 versions, rule-based and machine learning based. Machine Learning part contains Naive Bayes Classifier and Logistic Regression Classifier. We developed the Naive Bayes algorithm from scratch, but used sklearn implementation for Logistic Regression.

Stop-Word eliminator has 2 versions, static and dynamic. Static one requires pre-defined stopwords, while dynamic one detects the stop-words choosing a threshold according to word frequency distribution, using second derivative(elbow rule) automatically.

Normalizer works using predefined normalization lexicon and Levenshtein distance calculating both whole word and consonant letters only, facilitating the both.

Stemmer works in a rule based fashion by checking many of the suffixes that exist in Turkish language in an ordered fashion following the extra rules containing irregularities. It can also tell if the given word is a noun or verb based on their suffixes.

Data folder contains lots of lexicons for multi-word-expressions, normalization, prefixes, abbreviations(non-breaking prefixes), stop-words, etc.
