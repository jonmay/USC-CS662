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

10/27: IE; HW3 out (due 11/21)
10/29: Syntax
-->

Oct 27

: [Information Extraction]({{site.baseurl}}assets/files/ie.pdf)
: [**HW3 out (due 11/21)**]({{site.baseurl}}assets/files/hw3.pdf){: .label}
  : JM17.3, 20
    : Siniukov, Maksim - [An Iterative Associative Memory Model for Empathetic Response Generation](https://arxiv.org/pdf/2402.17959)
    : Questions by: Cheng-Han Wu
    : Pal, Debaditya - [Answer is All You Need: Instruction-following Text Embedding via Answering the Question](https://aclanthology.org/2024.acl-long.27/)
    : Questions by: Xinyan Yu

Oct 29
: [Agents]({{site.baseurl}}assets/files/tenghao_agents.pptx)  (Guest Lecture by Tenghao Huang)
  : [WebArena](https://arxiv.org/abs/2307.13854), [ToolLLM](https://arxiv.org/pdf/2307.16789), [Narrative Discourse](https://arxiv.org/pdf/2407.13248), [ReAct](https://arxiv.org/abs/2210.03629)
//    : Lee, Ryan - [MQuAKE: Assessing Knowledge Editing in Language Models via Multi-Hop Questions](https://aclanthology.org/2023.emnlp-main.971.pdf)
//    : Questions by: Ayush Goyal
//    : Yu, Xinyan - [Spiral of Silence: How is Large Language Model Killing Information Retrieval? A Case Study on Open Domain Question Answering](https://aclanthology.org/2024.acl-long.798/)
//    : Questions by: Maksim Siniukov
