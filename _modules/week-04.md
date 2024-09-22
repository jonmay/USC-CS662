---
title: Week 4
---


{% assign filedir = site.baseurl | append: page.subpath %} 
{% assign notes_path = filedir | append: "notes/" %} 
{% assign project = filedir | append: "project_proposal.pdf" %}

<!--  
Instructions:

INDENTATION COUNTS

Each day should be formatted exactly as follows

Date
: Lessons Covered
  : Reading List
    : In Class Presentations
: **Assignment/Announcement**{: .label}


To add a hyperlink for readings, do it as follows
  : [Example Paper](http://linktopaper.edu)

To make the hyperlink open in a new tab by default
  : [Example Paper](http://linktopaper.edu){:target=_"blank"}

The announcement can be made red for due dates as follows
: **Assignment Due**{: .label .label-red }
9/16 Word rep
9/18 ngram/ff/rnn
9/20 hw1 due
-->


Sep 16
: [Distributional Feature Representations: PPMI, LSA, word2vec]({{site.baseurl}}assets/files/distrib.pdf)
  : E 14.3, 14.5--6. JM 6, [LSA via SVD](https://matpalm.com/lsa_via_svd/index.html), [Linguistic regularities in continuous space word representations](https://aclanthology.org/N13-1090/), [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781), [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/abs/1310.4546)
    : 

<!-- Sep 8 -->
<!-- :  Drop deadline (for refund, without W) -->


Sep 18
: [N-Gram Language Models]({{site.baseurl}}assets/files/ngram.pdf), [Feed Forward and Recurrent Language Models (RNNs)]({{site.baseurl}}assets/files/ffrnn.pdf)
  : E 6.1--2, 6.4. 7.5, 7.7. JM 3 [Exploring the limits of language modeling](https://arxiv.org/abs/1602.02410) [LM notebook]({{site.baseurl}}assets/files/LMs.ipynb)


Sep 20
: **HW1 due**{: .label .label-red}
