## Welcome to ACML19 Weakly-supervised Learning Workshop

# Topic Summary

UC terminates subscriptions with world’s largest scientific publisher in push for open access to publicly funded research, since “Knowledge should not be accessible only to those who can pay,” said Robert May, chair of UC’s faculty Academic Senate. Similarly, machine learning should not be accessible only to those who can pay. Specifically, modern machine learning is migrating to the era of complex models (e.g., deep neural networks), which require a plethora of well-annotated data. Giant companies have enough money to collect well-annotated data. However, for startups or non-profit organizations, such data is barely acquirable due to the cost of labeling data or the intrinsic scarcity in the given domain. These practical issues motivate us to research and pay attention to **weakly-supervised learning (WSL)**, since WSL does not require such a huge amount of annotated data. We define WSL as the collection of machine learning problem settings and algorithms that share the same goals as supervised learning but can only access to **less supervised information** than supervised learning. In this workshop, we discuss both theoretical and applied aspects of WSL. Meanwhile, we co-organize **AutoWSL challenge** with 4Paradigm, ChaLearn and Microsoft. Winners in the competition and recived papers in WSL (related with AutoML) will be invite to **TPAMI special issue**. WSL workshop includes but not limited to the following topics:


# Topics of Interest

- Theory and applications of **incomplete supervision**, e.g., semi-supervised learning, active learning and positive-unlabeled learning;

- Theory and applications of **inexact supervision**, e.g., multi-instance learning and complementary learning;

- Theory and applications of **inaccurate supervision**, e.g., crowdsourcing and learning with noisy labels;

- Theory and applications of **cross-domain supervision**, e.g., zero-/one-/few-shot learning, domain adaptation and multi-task leaning;

- Theory and applications of **imperfect demonstration**, e.g., inverse reinforcement learning and imitation learning with non-expert demonstrations;

- Broad applications of weakly-supervised learning, such as weakly-supervised **object detection**, weakly-supervised **sequence modeling**, weakly-supervised **cross-media retrieval**, and weakly-supervised **medical image segmentation**.


# Topic Description

The focus of this workshop is three classical types of weak supervision: incomplete supervision, inexact supervision and inaccurate supervision. Specifically, incomplete supervision considers a subset of training data given with ground-truth labels while the other data remain unlabeled, such as semi-supervised learning and positive-unlabeled learning. Inexact supervision considers the situation where some supervision information is given but not as exacted as desired, i.e., only coarse-grained labels are available. For example, if we are considering to classify every pixel of an image, rather than the image itself, then ImageNet becomes a benchmark with inexact supervision. Besides, multi-instance learning belongs to inexact supervision, where we do not exactly know which instance in the bag corresponds to the given ground-truth label. Inaccurate supervision considers the situation where the supervision information is not always the ground-truth, such as learning with noisy labels. 

Moreover, this workshop covers two emerging types of weak supervision: cross-domain supervision and imperfect demonstration.
Cross-domain supervision considers the situation where the supervision information is scarce or even non-existent in the current domain but can be possibly derived from other domains. Examples of cross-domain supervision appear in zero-/one-/few-shot learning, where external knowledge from other domains is usually used to overcome the problem of too few or even no supervision in the original domain. Imperfect demonstration considers the situation for inverse reinforcement learning and imitation learning, where the agent learns with imperfect or non-expert demonstrations. For example, AlphaGo learns a policy from a sequence of states and actions (expert demonstration). Even if an expert player (human or agent) wins a game, it is not guaranteed that every action in the sequence is optimal.

This workshop will discuss the fundamental theory of weakly-supervised learning. Although theories of statistical weakly-supervised learning already exist, extending these results for deep weakly-supervised learning is still a challenge. Besides, this workshop also discusses on broad applications of weakly-supervised learning, such as weakly-supervised object detection (computer vision),
weakly-supervised sequence modeling (natural language processing), weakly-supervised cross-media retrieval (information retrieval),
and weakly-supervised medical image segmentation (healthcare). 

# Submission Guidelines

Workshop submissions and camera ready versions will be handled by Gmail. Please E-mail your paper to wsl.workshop@gmail.com with subject line ACML19-WSL-{paper name}.

Papers should be formatted according to the ACML19 formatting instructions for the Conference Track. The submissions with 2 pages will be considered for the poster, while the submissions with at least 4 pages will be considered for the oral presentation. 

ACML19-WSL is a non-archival venue and there will be no published proceedings. The papers will be posted on the workshop website. It will be possible to submit to other conferences and journals both in parallel to and after ACML19-WSL. Besides, we also welcome submissions to ACML19-WSL that are under review at other conferences and workshops. 

At least one author from each accepted paper must register for the workshop. Please see the ACML 2019 Website for information about accommodation and registration. 


# Preliminary list of invited speakers


The ACML-WSL workshop will feature on a **3 hours** event. We plan to invite **3 keynote speakers** who are leading experts in weakly-supervised learning area. A list of keynote speakers (alphabetic ordering) includes:


Prof. **[James T. Kwok](http://www.cse.ust.hk/~jamesk/)**, Hong Kong University of Science and Technology (confirmed)

Prof. **[Hsuan-Tien Lin](https://www.csie.ntu.edu.tw/~htlin/)**, National Taiwan University (confirmed)

Prof. **[Yu-Feng Li](http://lamda.nju.edu.cn/liyf/)**, Nanjing University (confirmed)


# Tentative Schedule

**Date**: date Nov 17, 2019

**Venue**: Room 1103 (11th floor) at WINC AICHI venue

| Time          | Event             |
| ------------- | -------------     |
| 13:30-13:35   | **Opening Ceremony**  |
| 13:35-14:05   | **Keynote Talk 1**  |  
|               | **Title**: TBD        |
|               | **Speaker**: James T. Kwok, (Hong Kong University of Science and Technology)|
| 14:05-14:15   | **Contributed Talk 1**    |
|               | **Title**: TBD       |
|               | **Authors**: TBD |
| 14:15-14:45   | **Keynote Talk 2**  |  
|               | **Title**:  TBD       |
|               | **Speaker**: Yu-Feng Li, (Nanjing University) |
| 14:45-14:55   | **Contributed Talk 2**    |
|               | **Title**: TBD        |
|               | **Authors**: TBD |
| 14:55-15:25   | **Keynote Talk 3**  |  
|               | **Title**: TBD        |
|               | **Speaker**:  Hsuan-Tien Lin, (National Taiwan University) |
| 15:25-15:35   | **Contributed Talk 3**    |
|               | **Title**: TBD        |
|               | **Authors**: TBD |
| 15:35-16:05   | **AutoWSL Challenge Talk**  |  
|               | **Title**: TBD        |
|               | **Speaker**: TBD |
| 16:05-16:30   | **Panel Discussion & Concluding Remark**    |
|               | **Host**: Bo Han        |
|               | **Guests**: Hsuan-Tien Lin, Yu-Feng Li, James T. Kwok|




# Important Dates

Submission Deadline: 05:00 PM (Pacific Time), Oct 1st, 2019

Acceptance Notifications: Oct 5th, 2019

Camera-ready: Oct 10th, 2019


# Organizers

[Bo Han](https://bhanml.github.io/), RIKEN-AIP, Japan.

[Gang Niu](https://niug1984.github.io/), RIKEN-AIP, Japan.

[Quanming Yao](http://www.cse.ust.hk/~qyaoaa/), 4Paradigm Inc., Hong Kong.

[Giorgio Patrini](https://giorgiop.github.io/), DeepTrace Inc., Netherlands.

[Aditya Krishna Menon](https://akmenon.github.io/), Google AI, USA.

[Clayton Scott](http://web.eecs.umich.edu/~cscott/), University of Michigan, USA.

[Masashi Sugiyama](http://www.ms.k.u-tokyo.ac.jp/sugi/), RIKEN / University of Tokyo, Japan.


# Sponsors

Several awards are kindly sponsored by RIKEN-AIP and 4Paradigm. We hope to receive more sponsorships to support young students. Please contact to bo.han@riken.jp for sponsorships.
