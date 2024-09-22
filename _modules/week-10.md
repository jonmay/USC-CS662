---
title: Week 10
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

10/28: IE; HW3 out (due 11/20)
10/30: Syntax
-->

Oct 28

: Information Extraction (IE)
: [**HW3 out (due 11/20)**]({{site.baseurl}}assets/files/hw3.pdf){: .label}   
    <!-- : [Life is a Circus and We are the Clowns: Automatically Finding Analogies between Situations and Processes]() -->
  : Siniukov, Maksim - [An Iterative Associative Memory Model for Empathetic Response Generation](https://arxiv.org/pdf/2402.17959)
  : Questions by: Wu, Cheng-Han
  : Pal, Debaditya - [Answer is All You Need: Instruction-following Text Embedding via Answering the Question](https://aclanthology.org/2024.acl-long.27/)
  : Questions by: Yu, Xinyan

Oct 30
: Syntax
  : Lee, Ryan - [MQuAKE: Assessing Knowledge Editing in Language Models via Multi-Hop Questions](https://aclanthology.org/2023.emnlp-main.971.pdf)
  : Questions by: Goyal, Ayush
  : Yu, Xinyan - [Spiral of Silence: How is Large Language Model Killing Information Retrieval? A Case Study on Open Domain Question Answering](nan)
  : Questions by: Siniukov, Maksim