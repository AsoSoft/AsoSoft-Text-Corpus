# AsoSoft Kurdish Text Corpus Ver 1.0
AsoSoft Text Corpus is the first large scale text corpus for the Kurdish language. This text corpus is compiled and processed by AsoSoft R&D Group (http://asosoft.com/en/). 

This repository includes the following files:
1. AsoSoft Text Corpus Large Version: This file contains 75 million tokens.
2. AsoSoft Text Corpus Small Version:: This file contains 5 million tokens.
3. AsoSoft topic annotated dataset.

# Normalization
A lot of normalization is done on this text corpus, including:
 <ul style="list-style-type:circle">
  <li>Non-unicode characters are converted.</li>
  <li>Multi-code Unicode Characters are unified and converted to Kurdish characters.</li>
  <li> Everywhere ("h"+ "ZWNJ") is used, it is replaced Kurdish "ە". </li>
  <li> If conjuctive "و"  is joined to its previous word, it is separated using a novel suggested algorithm.</li>
  <li> Everywhere "ر" or "وو" is used as the first letter of words, it is replaced with "ڕ" or "وو"  correspondingly.</li>
 <li>...</li>
</ul> 
More detail about normalization which is done is presented in our paper.

# Applications
Asosoft text corpus is applicable for following research areas:

•	Linguistics

•	Lexicography

•	NLP and Speech Processing

  o	Extracting language models
  
  o	Word vector representation

  o Topic Identification
  
  o Extracting computational lexicons

# How to Use
Some common editors for work with large text files are: EmEdior, TlCorpus, TextPad and so forth.

# License
This text corpus in for non-commercial use and researchers all over the world can use it for research projects.

<b>NOTE</b>: If you are using our text corpus cite us.

Hadi Veisi, Mohammad MohammadAmini, Hawre Hosseini; Toward Kurdish language processing: Experiments in collecting and processing the AsoSoft text corpus, Digital Scholarship in the Humanities, , fqy074, https://doi.org/10.1093/llc/fqy074
