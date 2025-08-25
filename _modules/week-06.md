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
  : JM 11.4 [T5](https://arxiv.org/pdf/1910.10683) [LoRA](https://arxiv.org/abs/2106.09685) [Prefix Tuning](https://aclanthology.org/2021.acl-long.353/) [T0](https://arxiv.org/abs/2110.08207)
: [**HW2 out (due 10/18)**]({{site.baseurl}}assets/files/hw2.pdf){: .label}

Oct 1
: [Reinforcement Learning with Human Feedback: Proximal Policy Optimization (PPO) and Direct Preference Optimization (DPO)]({{site.baseurl}}assets/files/rlhf.pptx)
  : [Ziegler RLHF Paper]({{site.baseurl}}assets/files/ziegler.pdf), [DPO Paper]({{site.baseurl}}assets/files/dpo.pdf)


<!--
//  : Chumeng Liang - [Selective Reflection-Tuning: Student-Selected Data Recycling for LLM Instruction-Tuning](https://arxiv.org/abs/2402.10110)
  : Questions by: Mia Sultan
  : Anirudh Ravi Kumar - [Teaching Language Models to Self-Improve through Interactive Demonstrations](https://aclanthology.org/2024.naacl-long.287.pdf)
  : Questions by: Debaditya Pal
-->
