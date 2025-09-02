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


Sep 22
: [Pretrained language models (ELMo, BERT, and sentence similarity)]({{site.baseurl}}assets/files/pretrained.pdf)
  : JM 10 [ELMo paper](https://aclanthology.org/N18-1202/) [BERT paper](https://aclanthology.org/N19-1423/) [Zoph Fine-Tuning paper](https://aclanthology.org/D16-1163/) [Fine-Tuning demo]({{site.baseurl}}assets/files/fine_tuning_demo.ipynb)

: **project proposal due**{: .label .label-red }

Sep 24
: NO CLASS
