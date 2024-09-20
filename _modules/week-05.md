---
title: Week 5
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
9/23 transformers; proj selection due
9/25 elmo+bert+sent sim -- https://aclanthology.org/N18-1202/ (elmo paper), https://aclanthology.org/N19-1423/ (bert paper)
-->


Sep 23
: [Attention]({{site.baseurl}}assets/files/attention.pdf) [Transformer Language Models]({{site.baseurl}}assets/files/transformer.pdf)
  : E 6.3, JM 9, 10. [Attention is all you need](https://arxiv.org/abs/1706.03762) [LM notebook]({{site.baseurl}}assets/files/LMs.ipynb)
    : <!-- Preni -- [The Importance of Modeling Social Factors of Language: Theory and Practice](https://aclanthology.org/2021.naacl-main.49/) -->
: **project proposal due**{: .label .label-red }

Sep 25
: [Pretrained language models (Elmo, BERT, and sentence similarity)]({{site.baseurl}}assets/files/pretrained.pdf)
  : JM 11.1--11.3 
