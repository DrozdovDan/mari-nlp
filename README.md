# Mari NLP


<a name="data"></a>
## Datasets

#### Corpora
* [Meadow Mari monoligual corpus](https://huggingface.co/datasets/mari-lab/mari-monolingual-corpus) 1.4M texts, over 20M word occurrences, 19 genres.

* [Meadow Mari corpora (web-corpora.net)](https://meadow-mari.web-corpora.net/index.html) web corpora with 5.53M word occurrences in the main monolingual corpus and 3.59M Mari and 15.11 Russian word occurrences in social media corpus (commentaries in VK).

* [Mari-language Korp (Vienna)](https://mari-language.univie.ac.at) web corpora with 57.38M tokens in Meadow Mari corpus and 6.25M tokens in Hill Mari corpus.

* [Hill Mari Corpus (tilda)](https://hillmari-exp.tilda.ws/corpus) Hill Mari corpus with 63522 word occurences in latin transcription.
 
* [Tatoeba](https://tatoeba.org/en/downloads) corpus of parallel sentences, 3869 pairs for Meadow Mari and Russian, 72 sentences for Hill Mari and Russian.

* [Wiki-dumps](https://commonvoice.mozilla.org/en/datasets) hours of Meadow and Hill Mari audio with transcriptions.

<a name="pretrained-models"></a>
## Pretrained models

* [UralicNLP](https://github.com/mikahama/uralicNLP) pretrained morphological analysators/generators and lemmatisation for uralic languages. Includes Meadow Mari and Hill Mari.

* [TartuNLP “Smugri”](https://huggingface.co/tartuNLP/smugri3_14-finno-ugric-nmt) Multilingual Neural Machine Translation model for low-resource Finno-Ugric languages. Includes Meadow Mari (average to-lang scores: 8.51 bleau, 43.42 chrf, 38.76 chrf++), Hill Mari (average to-lang scores: 7.30 bleau, 40.81 chrf, 36.40 chrf++).

* [Adapters for multilingual BERT/XLM-R] trained adapters on wikipedia corpus for Meadow Mari. [BERT](https://huggingface.co/AdapterHub/bert-base-multilingual-cased-mhr-wiki_houlsby). [XLM-R](https://huggingface.co/AdapterHub/xlm-roberta-base-mhr-wiki_pfeiffer).

#### Word Similarity
* [Fasttext Mari Word Embeddings](https://fasttext.cc/docs/en/crawl-vectors.html). [Meadow Mari](https://huggingface.co/facebook/fasttext-mhr-vectors). [Hill Mari](https://huggingface.co/facebook/fasttext-mrj-vectors).

<a name="software"></a>
## Methods/Software

* [GiellaLT] tools for building morphological analysers, proofing tools and dictionaries. [Meadow Mari repository](https://github.com/giellalt/lang-mhr). [Hill Mari repository](https://github.com/giellalt/lang-mjr).

* [Apertium](https://github.com/apertium/apertium-mrj-mhr) morphological analysis and generation, PoS-tagging.

<a name="misc"></a>
## Miscellaneous
* [Mari-lab](https://mari-lab.ru/index.php/Mari-Lab) community