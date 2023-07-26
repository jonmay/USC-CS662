---
layout: home
title: CSCI 662
nav_exclude: true
seo:
  type: Course
  name: Advanced Natural Language Processing
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

### Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} 
{% for staffer in instructors %} 
{{ staffer }}
{% endfor %}

{% assign TAs = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in TAs %}
{{ staffer }}
{% endfor %}

### Lectures 
Monday and Wednesday 10:00–11:50 am, SOS B2

### Textbook
Required: [Natural Language Processing - Eisenstein](https://mitpress.mit.edu/books/introduction-natural-language-processing) ('E' in schedule)
-- or [free version](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)


Required: [Speech and Language Processing 3rd edition - Jurafsky, Martin](https://web.stanford.edu/~jurafsky/slp3/) ('JM' in schedule)
-- [January 2023 pdf](https://web.stanford.edu/~jurafsky/slp3/ed3book_jan72023.pdf)

Required: Selected papers from NLP literature, see (evolving) schedule

### Grading

10% - In class participation \
10% - Posted questions before each in-class selected paper presentation and possible quizzes \
10% - In-class selected paper presentation \
30% - Three Homeworks (10% each) \
40% - Project, comprising proposal (5%), first version of report (5%), in-class presentation (10%), and final report (20%). Done in small groups. \
Written homeworks and project components except for final project report must be submitted on the date listed in the schedule, by 23:59:59 [AoE](https://www.timeanddate.com/worldclock/converter.html). \
Final project report is due Monday, December 11, 2022, 10:00 AM PST \
A deduction of 1/5 of the total possible score will be assessed for each late day. After five late days, you get a 0 on the assignment (and you should come talk to us because your grade will likely suffer!) \
You have four late days, to be applied as you wish, throughout the entire class, for homeworks and project proposal / first report (NOT final report). No deduction will be assessed if a late day is used.

### Contact us

On Piazza, Slack, or in class/office hours. Please do not email (unless notified otherwise).

### Topics 
(subject to change per instructor/class whim) (will not necessarily be presented in this order):

  : Linguistic Stack (graphemes/phones - words - syntax - semantics - pragmatics - discourse)
  : Tools\:
    : Corpora, Corpus statistics, Data cleaning and munging
    : Annotation and crowdwork
    : Evaluation
    : Models/approaches: rule-based, automata/grammars, perceptron, logistic regression, neural network models
    : Effective written and oral communication
    : Components/Tasks/Subtasks:
    : Language Models
  : Syntax: POS tags, constituency tree, dependency tree, parsing
    : Semantics: lexical, formal, inference tasks
    : Information Extraction: Named Entities, Relations, Events
    : Generation: Machine Translation, Summarization, Dialogue, Creative Generation


{% for module in site.modules %}
{{ module }}
{% endfor %}
