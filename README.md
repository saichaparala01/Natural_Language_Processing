# Natural_Language_Processing
**Student Name: Mounika Sai Chowdary Chaparala**
**Student ID: 700778259**

**Homework_1.Project Overview & Functionality**
This assignment covers key NLP concepts across five tasks. You designed several regular expressions to handle ZIP codes, number formats, spelling variants, and punctuation‑sensitive patterns. You then performed manual Byte Pair Encoding (BPE) merges on a toy corpus and implemented a mini‑BPE learner to observe how subword units reduce out‑of‑vocabulary issues. You applied Bayes’ Rule to text classification by interpreting priors, likelihoods, and posteriors, and explained why the denominator can be ignored. You also computed add‑1 smoothed likelihoods for sentiment classification. Finally, you tokenized a paragraph using naïve and manual methods, compared your tokens with an NLP tool, identified multiword expressions, and reflected on tokenization challenges such as punctuation, morphology, and idioms.


**Homework_2.Project Overview & Functionality**
This assignment covers both theoretical NLP calculations and hands on programming. Students analyze core NLP concepts such as Naive Bayes classification, bigram language models, smoothing, backoff, and evaluation metrics, and then implement a working bigram model in Python.
Part I – Written Calculations
Naive Bayes document classification using smoothed likelihoods and priors.
Ethical considerations in NLP, including representational harm, censorship risks, and dialect bias.
Bigram probability computation, sentence likelihood comparison, and handling zero probability with Laplace smoothing.
Backoff modeling for trigram → bigram probability estimation.
Evaluation metrics (precision, recall, macro/micro averaging) using a multi class confusion matrix, plus a short Python snippet to compute them.
Part II – Programming
You implement a full bigram language model, including:
Reading a small training corpus
Computing unigram and bigram counts
Estimating bigram probabilities using MLE
A function to compute the probability of any sentence
Testing the model on two sample sentences
Printing which sentences the model prefers and why
