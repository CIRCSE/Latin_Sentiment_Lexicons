# Latin_Sentiment_Lexicons
This repository contains a new set of sentiment lexicons of Latin adjectives and nouns which content is summarized in the table below.
- *cross-lingual-projection.tsv* was generated using a cross-language projection method starting from the English lexicon by [Cho et al. (2014)](https://www.sciencedirect.com/science/article/pii/S0950705114002196 "Cho et al. (2014)").
- *induction-kNN.tsv* was induced from distributed vector representations of words with [a k-NN algorithm implementation](https://github.com/WladimirSidorenko/SentiLex "a k-NN algorithm implementation") [(Sidarenka, 2019)](https://publishup.uni-potsdam.de/frontdoor/index/index/docId/43742 "(Sidarenka, 2019)").
- *gold_3classes.tsv* and *gold_5classes.tsv* were created by two experts of Latin language and culture following a multi-stage process and an extensive reconciliation phase. In the first each entry has 1 out of 3 possible score: positive, negative, neutral. The second has a five-way classification: 1 (fully positive), 0.5 (somewhat positive), 0 (neutral), -0.5 (somewhat negative), -1 (fully negative).
- *silver.tsv* was built by deriving new lexicon entries through synonym, antonym and derivational relations with the entries in the gold standard. Synonyms and antonyms were taken from the [Latin dictionary compiled by Skřivan (1890)](https://github.com/nikita-moor/latin-dictionary/tree/master/Skrivan1890 "Latin dictionary compiled by Skřivan (1890)"). Derivational relations were extracted from the database of [Word Formation Latin](http://wfl.marginalia.it/ "Word Formation Latin"). Graphical variants of lemmas present in the gold standard were added to the silver standard as well.
- *LatinAffectus.tsv* was created by merging the gold standard and the silver standard. It has been linked to the LiLa:Linking Latin Knowledge Base.

## How to cite
### Papers
Sprugnoli, R., Passarotti, M., Corbetta, D., & Peverelli, A. (2020). Creating, Evaluating and Extending Sentiment Lexicons for Latin. In Proceedings of the Twelfth International Conference on Language Resources and Evaluation (pp. 3071-3079). European Language Resources Association (ELRA). ([PDF])(https://www.aclweb.org/anthology/2020.lrec-1.376.pdf)

For *LatinAffectus*, its modeling and linking:
Sprugnoli, R., Mambrini, F., Moretti, G., Passarotti, M. (2020). Towards the Modeling of Polarity in a Latin Knowledge Base. In Proceedings of the 3rd Workshop on Humanities in the Semantic Web (WHiSe III). ([PDF])(http://whise.cc/2020/papers/WHiSe_2020_paper_6.pdf)

### Dataset
Rachele Sprugnoli, Giovanni Moretti, Marco Passarotti, Daniela Corbetta, Andrea Peverelli. (2020). CIRCSE/Latin_Sentiment_Lexicons: First release (Version v1.0.0) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.3865154

## Copyright
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />These resources are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
