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

Oct 23

: MEGA (Guest Lecture by Xuezehe Ma)
  : [Mega Paper](https://arxiv.org/abs/2209.10655); [Annotated S4](https://srush.github.io/annotated-s4/)
    : Tianyi Y. - [Active Example Selection for In-Context Learning ](https://aclanthology.org/2022.emnlp-main.622)
    : Questions by: Xinyue
    : Daniel Y. - [mPLUG: Effective and Efficient Vision-Language Learning by Cross-modal Skip-connections](https://aclanthology.org/2022.emnlp-main.488)
    : Questions by: Duygu
: [**HW3 out (due 11/17)**]({{site.baseurl}}assets/files/hw3.pdf){: .label}   
    <!-- : [Life is a Circus and We are the Clowns: Automatically Finding Analogies between Situations and Processes]() -->

Oct 25
: [machine translation]({{site.baseurl}}assets/files/mt_1.pptx): statistical,  [neural]({{site.baseurl}}assets/files/mt_2.pptx)
  : E 18, JM 10, 13
    : Abid - [Calibration Meets Explanation: A Simple and Effective Approach for Model Confidence Estimates](https://aclanthology.org/2022.emnlp-main.178) 
    : Questions by: Sean
    : Eray - [Zero-Shot Text Classification with Self-Training](https://aclanthology.org/2022.emnlp-main.73)
    : Questions by: Ian
