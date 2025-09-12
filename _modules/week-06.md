---
title: Week 6
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
9/29 pretraining and fine-tuning; hw2 out (due 10/17)
10/1 prompting, LLMs
-->



Sep 29
: [Prompting and Large Language Models]({{site.baseurl}}assets/files/llm.pdf)
  : JM 7 [T5](https://arxiv.org/pdf/1910.10683) [LoRA](https://arxiv.org/abs/2106.09685) [Prefix Tuning](https://aclanthology.org/2021.acl-long.353/) [T0](https://arxiv.org/abs/2110.08207)
  : Jinyi Ye - [What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A Gradient Perspective](https://aclanthology.org/2025.acl-long.1545/)
  : Questions by: Narges Ghasemi Ghaleh Bahmani
  : Saba Hashemi Safaei - [Byte Latent Transformer: Patches Scale Better Than Tokens](https://aclanthology.org/2025.acl-long.453/)
  : Questions by: Yuxin Yang	
: [**HW2 out (due 10/18)**]({{site.baseurl}}assets/files/hw2.pdf){: .label}



Oct 1
: [Reinforcement Learning with Human Feedback: Proximal Policy Optimization (PPO) and Direct Preference Optimization (DPO)]({{site.baseurl}}assets/files/rlhf.pptx)
  : JM 6, [Ziegler RLHF Paper]({{site.baseurl}}assets/files/ziegler.pdf), [DPO Paper]({{site.baseurl}}assets/files/dpo.pdf) 
  : Sadra Sabouri Halestani - [HUMT DUMT: Measuring and controlling human-like language in LLMs](https://aclanthology.org/2025.acl-long.1261/)
  : Questions by: Nikunj Gupta
  : Feiyu Zhu - [Self-Instructed Derived Prompt Generation Meets In-Context Learning: Unlocking New Potential of Black-Box LLMs](https://aclanthology.org/2025.acl-long.92/)
  : Questions by: Sichang (Stephen) He	