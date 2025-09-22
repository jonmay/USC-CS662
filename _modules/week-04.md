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
9/15 Word rep
9/17 ngram/ff/rnn
9/19 hw1 due
-->


Sep 15
: [N-Gram Language Models]({{site.baseurl}}assets/files/ngram.pdf), [Feed Forward and Recurrent Language Models (RNNs)]({{site.baseurl}}assets/files/ffrnn.pdf)
  : E 6.1--2, 6.4. 7.5, 7.7. JM 3, 13 [Exploring the limits of language modeling](https://arxiv.org/abs/1602.02410), [LM notebook]({{site.baseurl}}assets/files/LMs.ipynb), [Fast and Robust Neural Network Joint Models for Statistical Machine Translation](https://aclanthology.org/P14-1129/)



Sep 17
: [Slides]({{site.baseurl}}assets/files/Transformer.key), [Transformer Language Models]({{site.baseurl}}assets/files/transformer.pdf)
  : E 6.3, JM 8. [Attention is all you need](https://arxiv.org/abs/1706.03762), [Neural Machine Translation of Rare Words with Subword Units](https://arxiv.org/abs/1508.07909) 


Sep 19
: **HW1 due**{: .label .label-red}
