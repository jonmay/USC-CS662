---
title: Week 1
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

Aug 21
: [intro]({{site.baseurl}}assets/files/intro_2022.pdf), applications
  : E 1
: [**project assignment out (due 9/18)**]({{site.baseurl}}assets/files/CSCI_662_Fall_2022_Project_Assignment.pdf){: .label}

Aug 23
: [data processing. data resources, evaluation, annotation]({{site.baseurl}}assets/files/data.pdf)
  : E 4.5, JM 2, 4.9, [Nathan Schneider's unix notes](https://github.com/nschneid/unix-text-commands), 
  [Unix for poets](https://www.cs.upc.edu/~padro/Unixforpoets.pdf), 
  [sculpting text](http://matt.might.net/articles/sculpting-text/)

