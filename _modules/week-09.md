---
title: Week 9
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
10/20: IR and QA
10/22: Dialogue
-->

Oct 20
: [Efficient Inference]({{site.baseurl}}assets/files/efficient_inference.pdf)
  : [LM-Infinite](https://arxiv.org/abs/2308.16137)
  : [Speculative Decoding](https://arxiv.org/abs/2203.16487)
  : [Keep the Cost Down: A Review on Methods to Optimize LLM’s KV Cache Consumption](https://arxiv.org/pdf/2407.18003), [Unlocking Efficiency in Large Language Model Inference: A Comprehensive Survey of Speculative Decoding](https://aclanthology.org/2024.findings-acl.456/)
  : Faith Baca - [Large Language Models Are Biased Because They Are Large Language Models](https://arxiv.org/abs/2406.13138)
  : Questions by: Sajjad Shahabi
  : Ruth-Ann Armstrong - [Lexical Recall or Logical Reasoning: Probing the Limits of Reasoning Abilities in Large Language Models](https://aclanthology.org/2025.acl-long.664/)
  : Questions by: Saba Hashemi Safaei
  	 						
Oct 22
: [Information Retrieval (IR) and Question Answering (QA)]({{site.baseurl}}assets/files/irqa.pdf)
  : JM 11
  : Tianwen Fu - [Improving Factuality with Explicit Working Memory](https://aclanthology.org/2025.acl-long.548/)
  : Questions by: Kaicheng Wang
  : Nikunj Gupta - [Reinforced IR: A Self-Boosting Framework For Domain-Adapted Information Retrieval](https://aclanthology.org/2025.acl-long.1071/)
  : Questions by: Faith Baca
