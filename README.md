## Welcome to ACML19 Weakly-supervised Learning Workshop

# Topic Summary

UC terminates subscriptions with world’s largest scientific publisher in push for open access to publicly funded research, since “Knowledge should not be accessible only to those who can pay,” said Robert May, chair of UC’s faculty Academic Senate. Similarly, machine learning should not be accessible only to those who can pay. Specifically, modern machine learning is migrating to the era of complex models (e.g., deep neural networks), which require a plethora of well-annotated data. Giant companies have enough money to collect well-annotated data. However, for startups or non-profit organizations, such data is barely acquirable due to the cost of labeling data or the intrinsic scarcity in the given domain. These practical issues motivate us to research and pay attention to weakly-supervised learning (WSL), since WSL does not require such a huge amount of annotated data. We define WSL as the collection of machine learning problem settings and algorithms that share the same goals as supervised learning but can only access to **less supervised information** than supervised learning.

In this workshop, we discuss both theoretical and applied aspects of WSL, which includes but not limited to the following topics:

# Topics of Interest

Interested topics include, but are not limited to:

- Theory and applications of **incomplete supervision**, e.g., semi-supervised learning, active learning and positive-unlabeled learning;

- Theory and applications of **inexact supervision**, e.g., multi-instance learning and complementary learning;

- Theory and applications of **inaccurate supervision**, e.g., crowdsourcing and learning with noisy labels;

- Theory and applications of **cross-domain supervision**, e.g., zero-/one-/few-shot learning, domain adaptation and multi-task leaning;

- Theory and applications of **imperfect demonstration**, e.g., inverse reinforcement learning and imitation learning with non-expert demonstrations.

# Topic Description

The focus of this workshop is three classical types of weak supervision: incomplete supervision, inexact supervision and inaccurate supervision. Specifically, incomplete supervision considers a subset of training data given with ground-truth labels while the other data remain unlabeled, such as semi-supervised learning and positive-unlabeled learning. Inexact supervision considers the situation where some supervision information is given but not as exacted as desired, i.e., only coarse-grained labels are available. For example, if we are considering to classify every pixel of an image, rather than the image itself, then ImageNet becomes a benchmark with inexact supervision. Besides, multi-instance learning belongs to inexact supervision, where we do not exactly know which instance in the bag corresponds to the given ground-truth label. Inaccurate supervision considers the situation where the supervision information is not always the ground-truth, such as learning with noisy labels. 

Moreover, this workshop covers two emerging types of weak supervision: cross-domain supervision and imperfect demonstration.
Cross-domain supervision considers the situation where the supervision information is scarce or even non-existent in the current domain but can be possibly derived from other domains. Examples of cross-domain supervision appear in zero-/one-/few-shot learning, where external knowledge from other domains is usually used to overcome the problem of too few or even no supervision in the original domain. Imperfect demonstration considers the situation for inverse reinforcement learning and imitation learning, where the agent learns with imperfect or non-expert demonstrations. For example, AlphaGo learns a policy from a sequence of states and actions (expert demonstration). Even if an expert player (human or agent) wins a game, it is not guaranteed that every action in the sequence is optimal.

This workshop will discuss the fundamental theory of weakly-supervised learning. Although theories of statistical weakly-supervised learning already exist, extending these results for deep weakly-supervised learning is still a challenge. Besides, this workshop also discusses on broad applications of weakly-supervised learning, such as weakly-supervised object detection (computer vision),
weakly-supervised sequence modeling (natural language processing), weakly-supervised cross-media retrieval (information retrieval),
and weakly-supervised medical image segmentation (healthcare analysis). 

# Submission Guidelines

Workshop submissions and camera ready versions will be handled by Microsoft CMT. Click [https://cmt3.research.microsoft.com/IJCAIMOL2019](https://cmt3.research.microsoft.com/IJCAIMOL2019) for submission. 

Papers should be formatted according to the ACML formatting instructions for the Conference Track. The submissions with 2 pages will be considered for the poster, while the submissions with at least 4 pages will be considered for the oral presentation. 

ACML-WSL is a non-archival venue and there will be no published proceedings. The papers will be posted on the workshop website. It will be possible to submit to other conferences and journals both in parallel to and after ACML-WSL'19. Besides, we also welcome submissions to ACML-WSL that are under review at other conferences and workshops. 

At least one author from each accepted paper must register for the workshop. Please see the ACML 2019 Website for information about accommodation and registration. 


<!-- To be announced
-->

<!--

Workshop submissions and camera ready versions will be handled by Microsoft CMT. Click [https://cmt3.research.microsoft.com/ACMLMoL2018](https://cmt3.research.microsoft.com/ACMLMoL2018) for submission.

Papers should be formatted according to the ACML formatting instructions for the Conference Track. The submissions with 2 pages will be considered for the poster, while submissions with at least 6 pages will be considered for the oral presentation. The selective oral papers will be invited for IEEE TNNLS Special Issue on "Structured Multi-output Learning: Modelling, Algorithm, Theory and Applications" ([https://cis.ieee.org/images/files/Documents/Transactions/TNNLS/TNNLS_SMLMATA-CFP.pdf](https://cis.ieee.org/images/files/Documents/Transactions/TNNLS/TNNLS_SMLMATA-CFP.pdf)).

ACML-MoL is a non-archival venue and there will be no published proceedings. The papers will be posted on the workshop website. It will be possible to submit to other conferences and journals both in parallel to and after ACML-MoL'18. Besides, we also welcome submissions to ACML-MoL that are under review at other conferences and workshops.

At least one author from each accepted paper must register for the workshop. Please see the ACML 2019 Website for information about accommodation and registration.

-->



# Preliminary list of invited speakers


The MoL workshop will feature on a **2.5 hours** event. We plan to invite **4 keynote speakers** who are leading experts from both academia and industry. A list of keynote speakers includes:

Prof. **Hsuan-Tien Lin**, National Taiwan University

Prof. **Ivor W. Tsang**, University of Technology Sydney

Prof. **Jun Zhu**, Tsinghua University

Prof. **Zhi-Hua Zhou**, Nanjing University



# Tentative Schedule

**Date**: date Nov 17, 2019

**Venue**: Room 1103 (11th floor) at WINC AICHI venue

| Time          | Event             |
| ------------- | -------------     |
| 08:30-08:45   | **Opening Ceremony**  |
| 08:45-09:20   | **Keynote Talk 1**  |  
|               | **Title**: TBD        |
|               | **Speaker**: Hsuan-Tien Lin (National Taiwan University) |
| 09:20-09:40   | **Paper Talk 1**    |
|               | **Title**: TBD       |
|               | **Authors**: TBD |
| 09:40-10:15   | **Keynote Talk 2**  |  
|               | **Title**:  TBD       |
|               | **Speaker**: Zhi-Hua Zhou, (Nanjing University) |
| 10:15-10:35   | Coffee Break      |
| 10:35-10:55   | **Paper Talk 2**    |
|               | **Title**: TBD        |
|               | **Authors**: TBD |
| 10:55-11:30   | **Keynote Talk 3**  |  
|               | **Title**: TBD        |
|               | **Speaker**: Ivor W. Tsang  (University of Technology Sydney) |
| 11:30-11:50   | **Paper Talk 3**    |
|               | **Title**: TBD        |
|               | **Authors**: TBD |
| 10:55-11:30   | **Keynote Talk 4**  |  
|               | **Title**: TBD        |
|               | **Speaker**: Jun Zhu (University of Technology Sydney) |
| 11:50-12:30   | **Panel Discussion & Concluding Remark**    |
|               | **Host**: Bo Han        |
|               | **Guests**: Hsuan-Tien Lin, Zhi-Hua Zhou, Ivor W. Tsang |


<!--
To be announced
-->

<!--

8:50 - 9:00 Introduction

9:00 - 10:00 Invited Keynote Talk

===10:00-10:30 Morning tea===

10:30 - 10:55 Paper presentation

10:55 - 11:20 Paper presentation

11:20 - 11:35 Paper presentation

===11:35 - 11:50 Panel discussion===

11:50 - 12:05 Paper presentation

12:05 - 12:20 Paper presentation

12:20 - 12:35 Paper presentation

===12:35 - 12:50 Panel discussion===

-->

# Important Dates

Submission Deadline: 05:00 PM (Pacific Time), Oct 1st, 2019

Acceptance Notifications: Oct 5th, 2019

Camera-ready: Oct 10th, 2019



# Organizers

Bo Han, RIKEN-AIP, Japan.

Gang Niu, RIKEN-AIP, Japan.

Quanming Yao, 4Paradigm Inc., Hong Kong.

Giorgio Patrini, DeepTrace Inc., Netherlands.

Aditya Krishna Menon, Google AI, USA.

Clayton Scott, University of Michigan, USA.

Masashi Sugiyama, RIKEN / University of Tokyo, Japan.
