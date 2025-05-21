---
layout: page
title: Text as Data (Modules 2, 6)
---

Monday, June 16; Tuesday, June 17
{: #module-date}

**Monday, June 16; Tuesday, June 17**

**Fiona Shen-Bayh (University of Maryland)**

What does “text as data” mean? How do scholars transform texts into data that can be read and analyzed quantitatively? How are these data and methods used in service of political science research questions? This unit explores these questions by examining a variety of computational approaches to analyzing texts in innovative ways. Drawing on insights from research in political science, economics, sociology, and the humanities, the aim of this course is to provide students with a toolkit that can be used in service of applied text as data research.

***Participants who did not attend the module sequence from the beginning may not join later in the sequence.***

## Quantifying texts (M2, June 16) 
{: .module-sub }

### 8:45am - 10:15am – Transforming text into data

What does it mean to transform text into data? This is a task of translation: translating human language (i.e. natural language) into computer language. This module digs into the mechanics of translating qualitative information into machine readable data. We will also examine various ways of reading texts into Python.

**Required readings:**

  - Grimmer, J., & Stewart, B. (2013). Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts. Political Analysis, 21(3), 267-297. doi:10.1093/pan/mps028

  - Joel Spolsky, “[The Absolute Minimum Every Software Developer Absolutely, Positivitely Must Know About Unicode and Character Sets (No Excuses\!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

Suggested readings:

  - David C. Zentgraf, [What every programmer absolutely, positively needs to know about encodings and character sets to work with text](http://kunststube.net/encoding/) (a more technical explainer of the Spolsky piece)

  - David Mimno, “[From bits to characters](https://nbviewer.org/url/mimno.infosci.cornell.edu/info3350/notebooks/bits_to_chars.ipynb)”

  - Lucas, C., Nielsen, R. A., Roberts, M. E., Stewart, B. M., Storer, A., & Tingley, D. (2015). Computer-Assisted Text Analysis for Comparative Politics. Political Analysis, 23(2), 254–277.

### 1:30pm - 3:00pm – Building a corpus


The first step in any text-as-data project is understanding how to build a corpus. In this module, we will cover common approaches to text selection and representation for computational analysis, including the bag of words assumption, tokenization, and document-term matrices. By the end of the session, you will know how to collate a body of texts for a variety of modeling techniques.

**Required readings:**

  - Denny, M. J., & Spirling, A. (2018). Text preprocessing for unsupervised learning: Why it matters, when it misleads, and what to do about it. Political analysis, 26(2), 168-189

Suggested readings:

  - de Vries, E., Schoonvelde, M., & Schumacher, G. (2018). No Longer Lost in Translation: Evidence that Google Translate Works for Comparative Bag-of-Words Text Applications. Political Analysis, 26(4), 417–430.

### 3:30pm - 5:00pm – Counting 


When we transform texts into data, we create opportunities to summarize qualitative information in quantitative terms. The most intuitive way of doing so is through counting. While simple in theory, counting can reveal important trends both within documents and across a corpus – which terms are distinctive to particular documents, the prevalence of key terms across the corpus as a whole, and other lexical patterns that may be relevant for your research question. This session will explore basic principles of counting as well as their more complex applications, including the analysis of lexicons and sentiments using dictionaries.

**Required readings:**

  - Tausczik, Y. R., & Pennebaker, J. W. (2010). The Psychological Meaning of Words: LIWC and Computerized Text Analysis Methods. Journal of Language and Social Psychology, 29(1), 24-54.

  - Ethan Fast, Binbin Chen, Michael Bernstein, “[Empath: Understanding Topic Signals in Large-Scale Text](https://arxiv.org/abs/1602.06979)”

  - Milo Beckman, “[These are the Phrases Each GOP Candidate Uses Most](https://fivethirtyeight.com/features/these-are-the-phrases-each-gop-candidate-repeats-most/)”

Suggested readings:

  - Leites, N., Bernaut, E., & Garthoff, R. L. (1951). Politburo Images of Stalin. World Politics, 3(3), 317–339. [https://doi.org/10.2307/2009118](https://doi.org/10.2307/2009118)

  - Peter Dodds and Christopher Danforth. 2009. “Measuring the Happiness of Large-Scale Written Expression: Songs, Blogs, and President." Journal of Happiness Studies 11(4):441-456.

## Modeling and measuring texts (M6, June 17) 
{: .module-sub }

### 8:45am - 10:15am – Vectorizing 

When we transform texts into machine readable data, we store our text data as vectors. Vectorizing texts opens up a world of analytical possibilities in vector space. Using properties of geometry, we can compute differences and similarities between text vectors in order to analyze differences and similarities between the original texts. This session will cover the “geometry of text” and illustrate how to use Euclidean distance and cosine similarity to draw meaningful comparisons between texts in vector space.

**Required readings:**

  - Daniel Jurafsky & James H. Martin, ["Vector Semantics & Embeddings"](https://web.stanford.edu/~jurafsky/slp3/6.pdf) (Read Sections 6.1–6.5, pages 1-13)

  - Matt Daniels, “[The Language of Hip Hop](https://pudding.cool/2017/09/hip-hop-words/)”

### 1:30pm - 3:00pm – Embedding

You can infer the meaning of a word by the company it keeps – this is the intuition behind embedding, a type of vector space model wherein every word (or text) in a corpus is represented by a vector. Building upon the previous session, in this module we will explore a more advanced approach to word vectorizing using the popular Word2Vec algorithm. We will generate our own embeddings in order to analyze the semantic similarity (and dissimilarity) of words in a particular corpus.

**Required readings:**

  - Daniel Jurafsky & James H. Martin, ["Vector Semantics & Embeddings"](https://web.stanford.edu/~jurafsky/slp3/6.pdf), read Sections 6.8–6.11, pages 17–27).

  - Rodman, E. (2020). A Timely Intervention: Tracking the Changing Meanings of Political Concepts with Word Vectors. *Political Analysis*, *28*(1), 87–111.

Suggested readings:

  - Maria Antoniak, David Mimno; Evaluating the Stability of Embedding-based Word Similarities. *Transactions of the Association for Computational Linguistics* 2018; 6 107–119.

  - Rodriguez, P. L., & Spirling, A. (2022). Word embeddings: What works, what doesn’t, and how to tell the difference for applied research. *The Journal of Politics*, *84*(1), 101-115.

### 3:30pm - 5:00pm – Measuring 

From counting to embedding and beyond, text-as-data approaches have introduced novel ways of measuring complex concepts. But are these measures valid or reliable? How should we evaluate the quantification of qualitative information? This session will be a critical discussion of measurement strategies and best-practices in social science research.


**Required readings:**

  - TAD, Chapter 15: Principles of measurement

  - Lee, M. M., Zhang, N., & Herchenröder, T. (2024). From Pluribus to Unum? The Civil War and Imagined Sovereignty in Nineteenth-Century America. American Political Science Review, 118(1), 127–143. *Read intro and research design.*

  - Antoniak, M., Mimno, D., & Levy, K. (2019). Narrative paths and negotiation of power in birth stories. Proceedings of the ACM on Human-Computer Interaction, 3(CSCW), 1-27.


Suggested readings:

  - Stelios Michalopoulos, Melanie Meng Xue, Folklore, The Quarterly Journal of Economics, Volume 136, Issue 4, November 2021, Pages 1993–2046.

  - Kozlowski, A. C., Taddy, M., & Evans, J. A. (2019). The Geometry of Culture: Analyzing the Meanings of Class through Word Embeddings. American Sociological Review, 84(5), 905-949