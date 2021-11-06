# WInteR
WInteR: Widley Intelligent Reader
Winter is an NLP-powered artificial intelligence

Ethical Concerns:
An ethical dilemma arises in the definition of what is useful information and what is disinformation, as several different scenarios may arise.

Pragmatics:
Essentially will be broken down into a classification task either useful or not. However, we will not simply classify, rather attempt to also find the useful information within the disinformation. Subsequently, a passage will be given to Winter, and then it will divide the text in a binary search approach to classify each segement with a given misinformation index, and once the binary search reaches a unigram size it will then begin to omit the unigrams with the highest misinformation index. Once finished with a given passage Winter will return an average misinformation score of the original passage, and a summarization of the original useful information, as to offset the interuptions in natural language presented by the classification algorithm.

Misinformation Detection Task:

Misinformation Omission Task:

Information Summarize Task:

Evaluation Method:
  - Independent Detection
  - Independent Omission
  - Independent Summarization
  - Dependent System Evaluation

New FEVER dataset created in paper Towards Debiasing Fact Verification Models

