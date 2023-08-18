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

-->


Sep 18
: [recurrent and transformer language models, ELMo, BERT]({{site.baseurl}}assets/files/ffrnn.pdf)
  : E 6.3, JM 9. [Attention is all you need](https://arxiv.org/abs/1706.03762)
    : <!-- Preni -- [The Importance of Modeling Social Factors of Language: Theory and Practice](https://aclanthology.org/2021.naacl-main.49/) -->
: **project proposal due**{: .label .label-red }

Sep 20
: [Transformers, actually]({{site.baseurl}}assets/files/transformer.pdf)
