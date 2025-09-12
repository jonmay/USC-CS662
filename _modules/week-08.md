---
title: Week 8
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

10/13 mt
10/15 multilingual
10/17 HW 2 due
-->

Oct 13
: [Agents]({{site.baseurl}}assets/files/tenghao_agents.pptx)  (Guest Lecture by Tenghao Huang)
  : [WebArena](https://arxiv.org/abs/2307.13854), [ToolLLM](https://arxiv.org/pdf/2307.16789), [Narrative Discourse](https://arxiv.org/pdf/2407.13248), [ReAct](https://arxiv.org/abs/2210.03629) 
  : Kiarash Vaziri Goodarzi - [TokenFormer: Rethinking Transformer Scaling with Tokenized Model Parameters](https://arxiv.org/abs/2410.23168)
  : Questions by: Matthew Finlayson
  : Naga Vamsi Ramana Dinavahi - [Sliding Windows Are Not the End: Exploring Full Ranking with Long-Context Large Language Models](https://aclanthology.org/2025.acl-long.8/)
  : Questions by: Danny Deng


Oct 15
: Ethics (Guest Lecture by Katy Felkner)
  : [The Social Impact of Natural Language Processing](https://aclanthology.org/P16-2096.pdf), [Energy and Policy Considerations for Deep Learning in NLP](https://aclanthology.org/P19-1355/), [Model Cards for Model Reporting](https://arxiv.org/abs/1810.03993)
  : Kaicheng Wang - [MAIN-RAG: Multi-Agent Filtering Retrieval-Augmented Generation](https://aclanthology.org/2025.acl-long.131/)
  : Questions by: Ardysatrio Haroen
  : Zhiyuan Gao - [OS Agents: A Survey on MLLM-based Agents for Computer, Phone and Browser Use](https://aclanthology.org/2025.acl-long.369/)
  : Questions by: Naga Vamsi Ramana Dinavahi

Oct 17
: **HW 2 due**{: .label .label-red }
