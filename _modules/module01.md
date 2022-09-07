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
: [intro](assets/files/intro_2022.pdf), applications
  : E 1
: [**project assignment out (due 9/19)**](assets/files/CSCI_662_Fall_2022_Project_Assignment.pdf){: .label}

Aug 24
: [data processing. data resources, evaluation, annotation](assets/files/data.pdf)
  : E 4.5, JM 2, 4.9, [Nathan Schneider's unix notes](https://github.com/nschneid/unix-text-commands), 
  [Unix for poets](https://www.cs.upc.edu/~padro/Unixforpoets.pdf), 
  [sculpting text](http://matt.might.net/articles/sculpting-text/)

Aug 29
: [linear classifiers](assets/files/linearmodels.pdf) 
  : E 2.2, 2.3, 2.4. JM 4, 5, [Thumbs up? Sentiment Classification using Machine Learning Techniques](https://aclanthology.org/W02-1011/),  [Goldwater probability tutorial](http://homepages.inf.ed.ac.uk/sgwater/teaching/general/probability.pdf). [The Perceptron (Rosenblatt 1958)](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.335.3398&rep=rep1&type=pdf) (optional)
: [**HW1 out (due 9/14)**](assets/files/hw1.pdf){: .label}  

Aug 31
: [nonlinear classifiers, backprop, gradient descent](assets/files/nonlinear.pdf)
  : E 3. JM 7.2--7.4, 7.6. 
    : 


Sep 5
: LABOR DAY NO CLASS
  : 

Sep 7
: [distributional feature representations: PPMI, LSA, word2vec, bilingual dictionary induction](assets/files/distrib.pdf)
  : E 14.3, 14.5--6. JM 6.
    : 
: (Sep 9):  Drop deadline (for refund, without W))

Sep 12
: ngram language models
  : E 6.1--2, 6.4. 7.5, 7.7. JM 3    

Sep 14
: recurrent and transformer language models, ELMo, BERT
  : E 6.3, JM 9. [Attention is all you need](https://arxiv.org/abs/1706.03762)
    : <!-- Preni -- [The Importance of Modeling Social Factors of Language: Theory and Practice](https://aclanthology.org/2021.naacl-main.49/) -->
: **HW1 due**{: .label .label-red}

Sep 19
: slack class (either we will be behind and this class will let us catch up or we'll be ahead and I'll move the next lecture up
  : 
    : 
: **project proposal due**{: .label .label-red }

Sep 21
: ethics
  : [The Social Impact of Natural Language Processing](https://aclanthology.org/P16-2096.pdf), [Energy and Policy Considerations for Deep Learning in NLP](https://aclanthology.org/P19-1355/)
    : <!-- Taufeq -- [Smoothing and Shrinking the Sparse Seq2Seq Search Space](https://aclanthology.org/2021.naacl-main.210/) -->

Sep 26
: ROSH HASHANAH NO CLASS
  :
    :
: **HW2 out (due 10/12)**{: .label}

Sep 28
: POS tags, HMMs, treebanks
  : E 7.1--7.4, JM 8.1--8.5, 12 (through 12.4.2)
    : <!-- Zhuochen -- [Continual Learning for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.310/) -->


Oct 3
: constituencies, cky, dependencies, shift-reduce
  : E 10.1--10.4, JM 13.1--13.4, 14--14.4.4
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
  : [“Oh, yes, everything’s right on schedule, Fred”](https://www.cs.jhu.edu/~post/bitext/)
    : Presentation TBD
: **HW2 due**{: .label .label-red}

Oct 17
: machine translation: statistical, recurrent, attention
  : E 18, JM TBD
    : Presentation TBD
  
  
Oct 19
: machine translation: transformer, transfer learning, unsupervised, nonautoregressive
  : TBD
    : Presentation TBD
    
Oct 24
: dialogue: task-oriented
  : E 19.3, JM 24.3-24.4.4, 24.5.2
    : Presentation TBD
: **HW3 out (due 11/9)**{: .label}    
  
Oct 26
: dialogue: chatbots
  : JM 24-24.2.3. [The original ELIZA](https://sites.google.com/view/elizagen-org/the-original-eliza)
    : Presentation TBD

Oct 31
: information extraction: history, entities
  : [25 years of IE](https://www.cambridge.org/core/journals/natural-language-engineering/article/twentyfive-years-of-information-extraction/0E5BB0D6AE906BB3C25037E2D74CA8F3/share/5ce1ad8430e190e282cc234c79c320c49906a7e2)
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
  :  [InstructGPT paper (pp1--20)](https://arxiv.org/abs/2203.02155)
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
