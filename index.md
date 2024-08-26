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
{% assign num_instructors = instructors | size %}

{% if num_instructors != 0 %}
{% if num_instructors == 1 %}
#### Instructor
{% else %}
#### Instructors
{% endif %}


{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% if num_teaching_assistants == 1 %}
#### Teaching Assistant
{% else %}
#### Teaching Assistants
{% endif %}


{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

### Lectures 
- Monday and Wednesday 10:00–11:50 am, DMC 261
- See schedule for select days where class is canceled

### Textbook
- Optional: [Natural Language Processing - Eisenstein](https://mitpress.mit.edu/books/introduction-natural-language-processing) ('E' in schedule)
-- or [free version](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)


- Optional: [Speech and Language Processing 3rd edition - Jurafsky, Martin](https://web.stanford.edu/~jurafsky/slp3/) ('JM' in schedule)
-- [February 2024 pdf](https://web.stanford.edu/~jurafsky/slp3/ed3bookfeb3_2024.pdf)

- Required: Selected papers from NLP literature, see (evolving) schedule

### Grading

| Percentage | Assessment Component                                              |
|------------|-------------------------------------------------------------------|
| 10%        | In class participation                                            |
| 10%        | Posted questions before each in-class selected paper presentation and possible quizzes |
| 10%        | In-class selected paper presentation                              |
| 30%        | Three Homeworks (10% each)                                        |
| 40%        | Project, done in small groups, comprising:                        |
|            | - Proposal (5%)                                                   |
|            | - First version of report (5%)                                    |
|            | - In-class presentation (10%)                                     |
|            | - Final report (20%).                                             |

- Written homeworks and project components except for final project report must be submitted on the date listed in the schedule, by 23:59:59 [AoE](https://www.timeanddate.com/worldclock/converter.html). 
- Final project report is due Monday, December 16, 2024, 10:00 AM PST 
- A deduction of 1/5 of the total possible score will be assessed for each late day. After four late days (i.e. on the fifth), you get a 0 on the assignment (and you should come talk to us because your grade will likely suffer!) 
- You have four extension days, to be applied as you wish, throughout the entire class, for homeworks and project proposal / first report (NOT final report). No deduction will be assessed if an extension day is used. As an example, if an assignment is due November 10, you have two extension days remaining, you submit the assignment on November 12, and your score is 90/100. In this case you lose the extension days but your grade is not reduced; it remains 90/100. If you have one extension day, you lose it, and your grade is 70/100. If you have no extension days, your grade is 50/100.

### Contact us

On Slack, or in class/office hours. Please do not email (unless notified otherwise).

### Topics 
(subject to change per instructor/class whim) (will not necessarily be presented in this order):

  : Fundamentals
    : Linguistic Stack (graphemes/phones - words - syntax - semantics - pragmatics - discourse
    : Corpora, Corpus statistics, Data cleaning, munging, and annotation
    : Evaluation
    : Linear and Nonlinear Models
    : Dense Representations and neural architectures (feed-forward, RNN, Transformer)
    : Language Models
    : Pre-training, Fine-tuning, Prompting, Reward Alignment
    : Ethics
    : Effective written and oral communication
  : Applications
    : Multilingualism and Translation
    : Syntax
    : Information Retrieval/Question Answering
    : Dialogue
    : Information Extraction
    : Multimodality
    : Speech Recognition and Generation
    : Agent Interaction
    : Discourse


{% for module in site.modules %}
{{ module }}
{% endfor %}
