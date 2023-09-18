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

-->

Oct 23
: machine translation: history, evaluation, data
  : [“Oh, yes, everything’s right on schedule, Fred”](https://www.cs.jhu.edu/~post/bitext/)
    : Daniel Y. - [mPLUG: Effective and Efficient Vision-Language Learning by Cross-modal Skip-connections](https://aclanthology.org/2022.emnlp-main.488)
: **HW3 out (due 11/17)**{: .label}   
    <!-- : [Life is a Circus and We are the Clowns: Automatically Finding Analogies between Situations and Processes]() -->

Oct 25
: machine translation: statistical, recurrent, [transformer]({{site.baseurl}}assets/files/transmt.pdf), transfer learning,  unsupervised, nonautoregressive
  : E 18, JM 10, 13
    : Abid - [Calibration Meets Explanation: A Simple and Effective Approach for Model Confidence Estimates](https://aclanthology.org/2022.emnlp-main.178) 
    : Eray - [Zero-Shot Text Classification with Self-Training](https://aclanthology.org/2022.emnlp-main.73)
