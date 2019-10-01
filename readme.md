# [Fictometer](fictometer.com) Training Data
### Corpus
Brown corpus has been used for this work [(Francis and Kucera, 1989)](https://books.google.co.in/books?id=JG_3nQEACAAJ).
### Files
- *Stanford_Master_dataset.dat* contains features extracted from Brown corpus tagged using Stanford POS Tagger [(Toutanova et al., 2003)](https://nlp.stanford.edu/software/tagger.shtml).
- *Gold_Master_dataset.dat* contains features extracted from Brown corpus with Gold standard POS tagset.
## Labels
- label : 0 (Non-fiction) & 1 (Fiction)
- genre : category of the texts
- type : sub category of the text
## Tagset 1 : High level ratio features 
- adv_adj : Adjective by Adverb ratio
- adv_noun : Adjective by Noun ratio
- adv_prn : Adjective by Verb ratio
- adj_verb : Adjective by Pronoun ratio
- adj_prn : Noun by Verb ratio
- noun_verb : Noun by Verb ratio
- noun_prn : Noun by Pronoun ratio
- verb_prn : Verb by Pronoun ratio

## Tagset 2 : Low level features
- avg_sentlen : Average sentence length
- sd_sentlen : Standard deviation of sentence length
- avg_word_typetoken : Average of token (words) by type ratio
- sd_word_typetoken : Standard deviation of token (words) by type ratio
- avg_wordlen : Average word length
- sd_wordlen : Standard deviation of average word length
- avg_punct_typetoken : Average of token (punctuations) by type ratio
- sd_punct_typetoken : Standard deviation of token (punctuations) by type ratio

## Tagset 3 : Low level ratio features
- hyphen.quote.ratio : No. of hyphen by No. of quote ratio
- hyphen.exclamation.ratio : No. of hyphen by No. of exclamation ratio
- quote.question.ratio : No. of quote by No. of question ratio




