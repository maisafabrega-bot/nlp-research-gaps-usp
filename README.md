# Research Gap Analysis of Natural Language Processing Studies at USP

Research project that analyzes theses and dissertations on Natural Language Processing (NLP) produced at the University of São Paulo (USP). The works were processed with NLP techniques to identify which tasks and methodologies have already been studied and which remain underexplored.

### Data Collection:
- Source: Biblioteca Digital de Teses e Dissertações - USP
- Search: 
- Results: 127 works
- Tool: Octoparse

### Project Steps:
- Preprocessing: text normalization, tokenization and stopword removal
- Lemmatization and part-of-speech tagging with spaCy
- Noun phrase extraction
- Term frequency analysis
- Dictionary-based classification
- Topic modeling with TF-IDF and NMF
- Gap analysis

### Tools:
Octoparse, Python and pandas, spaCy, scikit-learn, Matplotlib, Seaborn, WordCloud, Google Colab.

### Approach:
NLP tasks and methodologies were categorized according to the classical architecture of natural language processing, based on the references below.
- NLP levels of linguistic analysis: phonetic-phonological, morphological-lexical, syntactic, semantic, discourse-pragmatic, and natural language generation.
- Methodologies: rules and lexicons, statistics and machine learning, neural networks and embeddings, transformers and BERT, and LLMs.

### How to Use This Repository:
- Download the dataset `octoparse_thesis_scraping.csv`
- Open the notebook in Google Colab and select the CSV file when required

### Results:
- The semantic level is strongly predominant (50 works) among the classified works, while the phonetic-phonological (3 works) and syntactic (9 works) levels are the least studied.
- The most frequently used methodologies were statistics and machine learning (42 works) and neural networks (37). LLMs (15) appear only in the most recent works.
- The USP schools and institutes with the most NLP research are ICMC, EP and IME.

### Research Gaps:
Within the analyzed sample, no works were found that combine the phonetic-phonological or syntactic levels with neural networks, transformers or LLMs.

### Data and Ethics
- Data was collected exclusively for academic, non-commercial purposes, with intervals between requests to avoid overloading the website.
- Titles and abstracts belong to their authors. Each record includes its DOI, which links to the original source.

### References:
JURAFSKY, D.; MARTIN, J. H. Speech and Language Processing. 2nd ed. Upper Saddle River: Pearson Prentice Hall, 2009.

MANNING, C. D.; SCHÜTZE, H. Foundations of Statistical Natural Language Processing. Cambridge: MIT Press, 1999.

LIU, P.; YUAN, W.; FU, J.; JIANG, Z.; HAYASHI, H.; NEUBIG, G. Pre-train, prompt, and predict: a systematic survey of prompting methods in natural language processing. ACM Computing Surveys, v. 55, n. 9, 2023. DOI: 10.1145/3560815.
