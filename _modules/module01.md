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
  

Oct 12
: machine translation: history, evaluation, data
  : 
    :
: **HW2 due**{: .label .label-red}

Oct 17
: machine translation: statistical, recurrent, attention
  : 
  
  
Oct 19
: machine translation: transformer, transfer learning
  :  
    
Oct 24
: dialogue: task-oriented
  : Eisenstein 19.3
: Information Extraction: Entity/Relation, CRF
  : Eisenstein 17.1, 17.2
    : Souvik -- [Model Extraction and Adversarial Transferability, Your BERT is Vulnerable!](https://aclanthology.org/2021.naacl-main.161/)
: **HW2 due**{: .label .label-red}

Oct 26
: Information Extraction: Events, Zero-shot
  : Eisenstein 17.3
    : Zhaoxu -- [Better Feature Integration for Named Entity Recognition](https://aclanthology.org/2021.naacl-main.271/)
: **HW3 out (due 11/16)**{: .label}

Oct 31
: Question Answering and Asking
  : Eisenstein 17.5
    : Jincheng -- [Abstract Meaning Representation Guided Graph Encoding and Decoding for Joint Information Extraction](https://aclanthology.org/2021.naacl-main.4/)


Nov 2
: Dialogue
  : Eisenstein 19.3
    : Hassan -- [A Frustratingly Easy Approach for Entity and Relation Extraction](https://aclanthology.org/2021.naacl-main.5)
: [**Project Report Version 1 due**{: .label .label-red}](({{project}}){:target="_blank"})

Nov 7
: Power and Ethics
  : 
    : Pithayuth -- [Action-Based Conversations Dataset: A Corpus for Building More In-Depth Task-Oriented Dialogue Systems](https://aclanthology.org/2021.naacl-main.239)

Nov 9
: Knowledge Graphs (Guest Lecture Elan Markowitz)
  : 
    : Liqiu -- [Structure-Aware Abstractive Conversation Summarization via Discourse and Action Graphs](https://aclanthology.org/2021.naacl-main.109)

Nov 14
: Text Games and Reinforcement Learning (Guest Lecture [Jesse Thomason](https://jessethomason.com/))
  :  
    : Aleksei -- [How to Motivate Your Dragon: Teaching Goal-Driven Agents to Speak and Act in Fantasy Worlds](https://aclanthology.org/2021.naacl-main.64/)

Nov 16
: How to write a paper
  : Neubig slides on Piazza
    : Haoming -- [Revisiting the Weaknesses of Reinforcement Learning for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.133/)
: **HW3 due**{: .label .label-red}

Nov 21
: Generalization and Robustness (Guest Lecture [Robin Jia](https://robinjia.github.io/))
  : 
    : Yi -- [Generating An Optimal Interview Question Plan Using A Knowledge Graph And Integer Linear Programming](https://aclanthology.org/2021.naacl-main.160/)

Nov 23
: THANKSGIVING BREAK; NO CLASS
  : 

Nov 28
: Project presentations
  : 
    : James -- [QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering](https://aclanthology.org/2021.naacl-main.45/)

Nov 30
: Project presentations
  : 
    : Abhinav -- [Robust Question Answering Through Sub-part Alignment](https://aclanthology.org/2021.naacl-main.98)
