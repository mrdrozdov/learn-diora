# Tutorials for understanding parsing and using DIORA

## 1. Background in Constituency Parsing

- Read section 8.4 to review the viterbi algorithm for part-of-speech tagging ([link](https://web.stanford.edu/~jurafsky/slp3/8.pdf)). Although we will be using the inside-outside algorithm for constituency parsing, it is much like the approach used in part-of-speech tagging.
- Read 12.1-12.4 to review constituent grammars ([link](https://web.stanford.edu/~jurafsky/slp3/12.pdf)). This is helpful for analyzing the output of DIORA, but as we will see, the parse trees DIORA predicts are simplified versions of constituent trees that are strictly binary and do not have non-terminal labels.
- Read 13.1-13.4 to review constituency parsing algorithms and evaluation methods ([link](https://web.stanford.edu/~jurafsky/slp3/13.pdf)). This is the most relevant section for DIORA-related research. It covers the CKY algorithm which is used for inference in graph-based constituency models (including DIORA) and also some modern supervised constituency parsing approaches such as Kitaev et al. (2019).

## 2. Background in Deep Inside-Outside Recursive Autoencoders

- Review section 2 in this paper by Lari and Young (1990) ([link](https://www.cs.jhu.edu/~jason/600.665/lari-young.pdf)). Note: This is not the paper that introduces the inside-outside algorithm! That paper is by Baker (1979). Also, consider this reading optional. It is a very good review of the algorithm but is fairly dense and heavy on notation.
- Read Drozdov et al. (2019) that introduces DIORA ([link](https://arxiv.org/abs/1904.02142)).
