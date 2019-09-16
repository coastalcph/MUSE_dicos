# Annotated MUSE Dictionaries
The MUSE dictionaries for ten language pairs (English to and from Bulgarian, German, Danish, Arabic, and Hindi) were annotated according to the following categories: 
 - noun (n)
 - proper noun (pn)
 - verb (v)
 - adjective/adverb (a)
 - other (o)
 - invalid (nw)

The first five categories concern the part of speech of valid word pairs. The last category covers word pairs where either the
source word was judged to be a non-word in the source language or the listed target word was deemed an invalid translation of
the given source word. Annotations for proper nouns in the English to and from Spanish dictionaries are available as well 
(with all remaining pairs are bulked under the 'other' category). 

We suggest that these splits be used for part-of-speech analysis of the performance of bilingual dictionary induction systems.
We also recommend that overall performance be measure on the subset of noun, verb, adjective/adverb and other pairs, i.e.
excluding both invalid word pairs and proper nouns. 

If you use these splits, please cite

Yova Kementchedjhieva, Mareike Hartmann, Anders Søgaard. <b><a href="https://arxiv.org/abs/1909.05708">
Lost in Evaluation: Misleading Benchmarks for Bilingual Dictionary Induction.</a></b> 
In Proceedings of EMNLP 2019 , Hong Kong.
