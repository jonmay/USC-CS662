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
: [ngram language models](assets/files/ngram.pdf)
  : E 6.1--2, 6.4. 7.5, 7.7. JM 3 [Exploring the limits of language modeling](https://arxiv.org/abs/1602.02410)   

Sep 14
: [recurrent and transformer language models, ELMo, BERT](assets/files/ffrnn.pdf)
  : E 6.3, JM 9. [Attention is all you need](https://arxiv.org/abs/1706.03762)
    : <!-- Preni -- [The Importance of Modeling Social Factors of Language: Theory and Practice](https://aclanthology.org/2021.naacl-main.49/) -->
: **HW1 due**{: .label .label-red}

Sep 19
: [Transformers, actually](assets/files/transformer.pdf)
  : 
    : 
: **project proposal due**{: .label .label-red }

Sep 21
: ethics
  : [The Social Impact of Natural Language Processing](https://aclanthology.org/P16-2096.pdf), [Energy and Policy Considerations for Deep Learning in NLP](https://aclanthology.org/P19-1355/), [Model Cards for Model Reporting](https://arxiv.org/abs/1810.03993)
    : <!-- Taufeq -- [Smoothing and Shrinking the Sparse Seq2Seq Search Space](https://aclanthology.org/2021.naacl-main.210/) -->

Sep 26
: ROSH HASHANAH NO CLASS
  :
    :
: **HW2 out (due 10/12)**{: .label}

Sep 28
: [POS tags, HMMs](assets/files/poshmm.pdf), treebanks
  : E 7.1--7.4, JM 8.1--8.5, 12 (through 12.4.2)
    : <!-- Zhuochen -- [Continual Learning for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.310/) -->


Oct 3
: [constituencies, cky](assets/files/constit.pdf), dependencies, shift-reduce
  : E 10.1--10.4, JM 13.1--13.4, 14--14.4.4
    : <!-- Fei -- [Counterfactual Data Augmentation for Neural Machine Translation](https://aclanthology.org/2021.naacl-main.18/) -->


Oct 5
: YOM KIPPUR NO CLASS
  :

Oct 10
: [dependencies](assets/file/depend.pdf)
: 
: Omey - [TweetSpin - Propaganda detection in Social Media using Multi-View Representations](https://aclanthology.org/2022.naacl-main.251/)
    : Alireza - [Hate Speech and Counter Speech Detection: Conversational Context Does Matter](https://aclanthology.org/2022.naacl-main.433/)


Oct 12
: shift-reduce
:
: Smit - [Aligning to Social Norms and Values in Interactive Narratives](https://aclanthology.org/2022.naacl-main.439/)
    : Syeda - [How Gender Debiasing Affects Internal Model Representations, and Why It Matters](https://aclanthology.org/2022.naacl-main.188/)
: **HW2 due**{: .label .label-red}

Oct 17
: machine translation: history, evaluation, data
  : [“Oh, yes, everything’s right on schedule, Fred”](https://www.cs.jhu.edu/~post/bitext/)
    : Mahak - [Time Waits for No One! Analysis and Challenges of Temporal Misalignment](https://aclanthology.org/2022.naacl-main.435/)
    : Amin - [Lifelong Pretraining: Continually Adapting Language Models to Emerging Corpora](https://aclanthology.org/2022.naacl-main.351/)
  
  
Oct 19
: machine translation: statistical, recurrent, transformer, transfer learning,  unsupervised, nonautoregressive
  : E 18, JM 10
    : Zhuoyu - [Annotators with Attitudes: How Annotator Beliefs And Identities Bias Toxic Language Detection](https://aclanthology.org/2022.naacl-main.431/)
    : Hirona - [Recognition of They/Them as Singular Personal Pronouns in Coreference Resolution](https://aclanthology.org/2022.naacl-main.250/)
    
Oct 24
: MEGA (Guest Lecture by Xuezehe Ma)
: [Mega Paper](https://arxiv.org/abs/2209.10655); [Annotated S4](https://srush.github.io/annotated-s4/)
    : Robert - [Non-Autoregressive Machine Translation: It’s Not as Fast as it Seem](https://aclanthology.org/2022.naacl-main.129/)
    : Yixiang - [Ask Me Anything in Your Native Language](https://aclanthology.org/2022.naacl-main.30/)
: **HW3 out (due 11/9)**{: .label}    



Oct 26
: semantics: logical/compositional, frames and roles, amr, distributional
  : E 12.1, 12.2, 13.1, 13.3, 14.1-3, 14.6-8, JM 15.1-3, 6
    : Charles - [Theory-Grounded Measurement of U.S. Social Stereotypes in English Language Models](https://aclanthology.org/2022.naacl-main.92/)
    : Mina - [How Conservative are Language Models? Adapting to the Introduction of Gender-Neutral Pronouns](https://aclanthology.org/2022.naacl-main.265/)

Oct 31
: Vision-and-language Models (Guest lecture: Xuezhe Ma)
: [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239), [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456), [Variational Diffusion Models](https://arxiv.org/abs/2107.00630), [Understanding Diffusion Models: A Unified Perspective](https://arxiv.org/abs/2208.11970)
: Basem - [Explaining Dialogue Evaluation Metrics using Adversarial Behavioral Analysis](https://aclanthology.org/2022.naacl-main.430/)
: Leticia - [Learning Dialogue Representations from Consecutive Utterances](https://aclanthology.org/2022.naacl-main.55/)


Nov 2
: dialogue: task-oriented and chatbots
: E 19.3, JM 24 [The original ELIZA](https://sites.google.com/view/elizagen-org/the-original-eliza)
    : Zhivar - [Semantic Diversity in Dialogue with Natural Language Inference](https://aclanthology.org/2022.naacl-main.6/)
  : Fazle - [On the Origin of Hallucinations in Conversational Models: Is it the Datasets or the Models?](https://aclanthology.org/2022.naacl-main.387/)
: [**Project Report Version 1 due**{: .label .label-red}](({{project}}){:target="_blank"})


Nov 7
: question answering, information retrieval
  : JM 23
    : James - [Learning as Conversation: Dialogue Systems Reinforced for Information Acquisition](https://aclanthology.org/2022.naacl-main.352/)
    : Yanze - [Meet Your Favorite Character: Open-domain Chatbot Mimicking Fictional Characters with only a Few Utterances](https://aclanthology.org/2022.naacl-main.377/)

Nov 9
: natural language inference and common sense tasks
  : [Modeling Semantic Containment and Exclusion in Natural Language Inference](https://aclanthology.org/C08-1066/), [Commonsense Reasoning and Commonsense Knowledge in Artificial Intelligence](https://cs.nyu.edu/~davise/papers/CommonsenseFinal.pdf)
    : Sophie - [Knowledge-Grounded Dialogue Generation with a Unified Knowledge Representation](https://aclanthology.org/2022.naacl-main.15/)
    : Jiarui - [JointLK: Joint Reasoning with Language Models and Knowledge Graphs for Commonsense Question Answering](https://aclanthology.org/2022.naacl-main.372/)
: **HW3 due**{: .label .label-red}

Nov 14
: prompts, multi task large language models
  :  [InstructGPT paper (pp1--20)](https://arxiv.org/abs/2203.02155), [Large Language Models are Human-Level Prompt Engineers](https://openreview.net/forum?id=92gvk82DE-)
    : Darpan - [Robust Conversational Agents against Imperceptible Toxicity Triggers](https://aclanthology.org/2022.naacl-main.204/)

Nov 16
: adapters, prefix tuning, few-parameter fine-tuning
  : TBD
    : Sahana - [Learning to Transfer Prompts for Text Generation](https://aclanthology.org/2022.naacl-main.257/)

Nov 21
: information extraction
  : JM 17, E 17, [25 years of IE](https://www.cambridge.org/core/journals/natural-language-engineering/article/twentyfive-years-of-information-extraction/0E5BB0D6AE906BB3C25037E2D74CA8F3/share/5ce1ad8430e190e282cc234c79c320c49906a7e2)

Nov 23
: THANKSGIVING BREAK; NO CLASS
  

Nov 28
: Project presentations
 

Nov 30
: Project presentations
