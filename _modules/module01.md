---
title: Schedule of Classes
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


To add a hyperlink for readings, due it as follows
  : [Example Paper](http://linktopaper.edu)

To make the hyperlink open in a new tab by default
  : [Example Paper](http://linktopaper.edu){:target=_"blank"}

The announcement can be made red for due dates as follows
: **Assignment Due**{: .label .label-red }

-->

Aug 22
: intro, applications
  : E 1
: **project assignment out (due 9/19)**{: .label}

Aug 24
: data processing. data resources
  : [Nathan Schneider's unix notes](https://github.com/nschneid/unix-text-commands), 
  [Unix for poets](https://www.cs.upc.edu/~padro/Unixforpoets.pdf), 
  [sculpting text](http://matt.might.net/articles/sculpting-text/)

Aug 29
: linear classifiers 
  : E 2.2, 2.3, 2.4. JM 4, 5, [Goldwater probability tutorial](http://homepages.inf.ed.ac.uk/sgwater/teaching/general/probability.pdf).
: **HW1 out (due 9/14)**{: .label}  

Aug 31
: nonlinear classifiers, backprop, gradient descent
  : E 3. JM 7.2-7.4, 7.6. 
    : <!-- Jon -- [Preregistering NLP research](https://aclanthology.org/2021.naacl-main.51.pdf) -->



Sep 5
: LABOR DAY NO CLASS
  : 

Sep 7
: distributional feature representations Perceptron, Logistic Regression, Nonlinear classifiers
  : E 14.3, 14.5-6. JM 6.
    : <!-- Julie -- [Adversarial Learning for Zero-Shot Stance Detection on Social Media](https://aclanthology.org/2021.naacl-main.379.pdf){:target="_blank"} -->


Sep 12
: ngram language models
  : E 6.1-2, 6.4. 7.5, 7.7. JM 3
    :  <!-- Jiageng -- [A Disentangled Adversarial Neural Topic Model for Separating Opinions from Plots in User Reviews](https://aclanthology.org/2021.naacl-main.228/) -->
: Drop deadline (for refund, without W)

Sep 14
: recurrent and transformer language models, ELMo, BERT
  : E 6.3, JM 9
    : <!-- Preni -- [The Importance of Modeling Social Factors of Language: Theory and Practice](https://aclanthology.org/2021.naacl-main.49/) -->
: **HW1 due**{: .label .label-red}

Sep 19
: data gathering, annotation, evaluation
  : TBD
    : <!-- Anirudh -- [End-to-end ASR to jointly predict transcriptions and linguistic annotations](https://aclanthology.org/2021.naacl-main.149/) -->
: **project proposal due**{: .label .label-red }

Sep 21
: ethics
  : TBD
    : <!-- Taufeq -- [Smoothing and Shrinking the Sparse Seq2Seq Search Space](https://aclanthology.org/2021.naacl-main.210/) -->

Sep 26
: ROSH HASHANAH NO CLASS
  :
    :
: **HW2 out (due 10/12)**{: .label}

Sep 28
: POS tags, HMMs, treebanks
  : E 7.1--7.4, JM 8.1-8.5 (TBD discussion of actual trees!!)
    : <!-- Zhuochen -- [Continual Learning for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.310/) -->


Oct 3
: constituencies, cky, dependencies, shift-reduce
  : E 10.1--10.4, JM TBD
    : <!-- Fei -- [Counterfactual Data Augmentation for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.18/) -->


Oct 5
: YOM KIPPUR NO CLASS
  :

Oct 10
: semantics: logical/compositional, frames and roles, amr, distributional
  : E 12.1, 12.2, 13.1, 13.3, 14.1-3, 14.6-8, JM 15.1-3, 6
    : Presentation TBD

Oct 12
: machine translation: history, evaluation, data
  : TBD
    : Presentation TBD
: **HW2 due**{: .label .label-red}

Oct 17
: machine translation: statistical, recurrent, attention
  : E 18, JM TBD
    : Presentation TBD
  
  
Oct 19
: machine translation: transformer, transfer learning
  : TBD
    : Presentation TBD
    
Oct 24
: dialogue: task-oriented
  : E 19.3, JM 24.3-24.4.4, 24.5.2
    : Presentation TBD
: **HW3 out (due 11/9)**{: .label}    
  
Oct 26
: dialogue: chatbots
  : JM 24-24.2.3. 
    : Presentation TBD

Oct 31
: information extraction: history, entities
  : TBD
    : Presentation TBD
    
Nov 2
: information extraction: relations, events
  : TBD
    : Presentation TBD
: [**Project Report Version 1 due**{: .label .label-red}](({{project}}){:target="_blank"})

Nov 7
: question answering, information retrieval
  : TBD
    : Presentation TBD

Nov 9
: natural language inference and common sense tasks
  : TBD
    : Presentation TBD
: **HW3 due**{: .label .label-red}

Nov 14
: prompts, multi task large language models
  :  TBD
    : Presentation TBD

Nov 16
: adapters, prefix tuning, few-parameter fine-tuning
  : TBD
    : Presentation TBD

Nov 21
: very long sequence models (Guest Lecture [Xuezhe (Max) Ma](https://xuezhemax.github.io/))
  : 
    : Presentation TBD

Nov 23
: THANKSGIVING BREAK; NO CLASS
  

Nov 28
: Project presentations
 

Nov 30
: Project presentations
