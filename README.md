## Welcome to SDM2020 Weakly-supervised and Unsupervised Learning Workshop

# Topic Summary

Modern data mining is migrating to the era of complex models (e.g., deep neural networks), which require a plethora of data to train. However, most existing data mining algorithms rely heavily on supervisory label information. As dataset sizes grow bigger, obtaining labels is becoming more and more laborious and expensive. Giant companies have enough money to collect well-annotated data. However, for startups or non-profit organizations, such data is barely acquirable due to the cost of labeling data or the intrinsic scarcity in the given domain. These practical issues motivate us to research and pay attention to weakly-supervised and unsupervised learning (WSUL), since that it does not require such a huge amount of annotated data and that it is relatively easy to collect a large amount of unannotated data. We therefore propose a workshop for researchers from different fields of data mining that face this problem to discuss this issue and foster further research advances in this direction.


# Topics of Interest

We define WSUL as the collection of learning problem settings and algorithms that share the similar goals as supervised learning but can only access to **less or even no supervised information** than supervised learning.  
In this workshop, we discuss both theoretical and applied aspects of WSUL, which includes but not limited to the following topics:

-   Theories, algorithms, and applications of **no supervision**, e.g., clustering, generative adversarial nets, variational autoencoders;
-   Theories, algorithms, and applications of **incomplete supervision**, e.g., dealing with semi-supervised data or positive-unlabeled data;
-   Theories, algorithms, and applications of **inexact supervision**, e.g., dealing with similarity/dissimilarity data and complementary information;
-   Theories, algorithms, and applications of **inaccurate supervision**, e.g., crowdsourcing and dealing with noisy labels;
-   Theories, algorithms, and applications of **cross-domain supervision**, e.g., domain adaptation and zero-/one-/few-shot learning.


# Topic Description

The focus of this workshop is five types of supervision: no supervision, incomplete supervision, inexact supervision, inaccurate supervision, and cross-domain supervision. Specifically, no supervision considers problems in which no data have ground-truth labels. Incomplete supervision considers a subset of training data given with ground-truth labels while the other data remain unlabeled, such as semi-supervised data and positive-unlabeled data. Inexact supervision considers the situation where some supervision information is given but not as exacted as desired, i.e., only coarse-grained labels are available. For example, if we are considering to classify every pixel of an image, rather than the image itself, then ImageNet becomes a benchmark with inexact supervision. Besides, the multi-instance learning setting belongs to inexact supervision, where we do not exactly know which instance in the bag corresponds to the given ground-truth label. Inaccurate supervision considers the situation where the supervision information is not always the ground-truth, such as learning with noisy labels. Cross-domain supervision considers the situation where the supervision information is scarce or even non-existent in the current domain but can be possibly derived from other domains. Examples of cross-domain supervision appear in zero-/one-/few-shot learning, where external knowledge from other domains is usually used to overcome the problem of too few or even no supervision in the original domain.

This workshop will discuss the fundamental theories of weakly-supervised and unsupervised learning. Although theories of statistical weakly-supervised and unsupervised learning already exist, extending these results for deep weakly-supervised and unsupervised learning is still a challenge. Besides, this workshop also discusses on broad applications of weakly-supervised and unsupervised learning, such as mining text, web & social media, analyzing finance data, genomics & bioinformatics, and recommendation.


# Submission Guidelines

Workshop submissions and camera ready versions will be handled by the CTM system. [Link to be updated]. We welcome extended-abstract submissions to introduce preliminary works and ideas, as well as recently-published research at the top conferences. The workshop accepts both full papers (4 to 8 pages) and extended abstracts (1 to 2 pages) for published or ongoing work.  Papers should be submitted as PDF, using the SIAM conference proceedings style.

# Tentative Schedule

The workshop will be combined with invited talks, accepted presentations, and informal discussions. 

| Time | Event |  
| ------------- | ------------- |  
| 09:00-09:15 | **Opening Ceremony** |  
||Session 1: Incomplete supervision, inexact supervision and inaccurate supervision
| 09:15-10:15 | **Keynote Talk 1** |  
| | **Title**: TBD |  
| | **Speaker**: Lingfei Wu, (IBM T. J. Watson Research Center; confirmed)|  
| 10:15-11:15 | **Keynote Talk 2** |  
| | **Title**: TBD |  
| | **Speaker**: Jiayu Zhou, (Michgan State University; confirmed)|  
| 11:15-11:25 | **Contributed Talk 1** |  
| | **Title**: TBD |  
| | **Authors**: TBD |  
| 11:25-11:35 | **Contributed Talk 2** |  
| | **Title**: TBD |  
| | **Authors**: TBD |  
| 11:35-11:45 | **Contributed Talk 3** |  
| | **Title**: TBD |  
| | **Authors**: TBD |  
| 11:45-12:45 | **Poster session 1 / Coffee break** |  
 | 11:45-12:45 | **12:45-14:30 / Lunch break** | 
||Session 2: No supervision and Cross-domain supervision
| 14:30-15:30 | **Keynote Talk 3** |  
| | **Title**: TBD |  
| | **Speaker**: Kayhan Batmanghelich, (University of Pittsburgh; confirmed)|  
| 15:30-16:30 | **Keynote Talk 4** |  
| | **Title**: TBD |  
| | **Speaker**: Zhangyang Wang, (Texas A&M University; confirmed)|  
| 16:30-16:40 | **Keynote Talk 5** |  
| | **Title**: TBD |  
| | **Authors**: Wei-Lun Chao, (Ohio State University; confirmed)|  
| 16:40-16:50 | **Contributed Talk 4** |  
| | **Title**: TBD |  
| | **Authors**: TBD |  
| 16:50-17:00 | **Contributed Talk 5** |  
| | **Title**: TBD |  
| | **Authors**: TBD |  
  | 17:00-18:00 | **Poster session 2 / Coffee break** | 


# Important Dates

Submission Deadline: March 8, 2020

Acceptance Notifications: March 22, 2020

Final camera-ready papers due: April 1, 2020


# Organizers
[Mingming Gong](https://mingming-gong.github.io/), University of Melbourne, Australia.

[Chunyuan Li](http://chunyuan.li/), Microsoft Research, USA.

[Tongliang Liu](https://tongliang-liu.github.io/), University of Sydney, Australia.

[Bo Han](https://bhanml.github.io/), RIKEN AIP, Japan.

[Quanming Yao](http://www.cse.ust.hk/~qyaoaa/), 4Paradigm Inc., Hong Kong.

[Gang Niu](https://niug1984.github.io/), RIKEN AIP, Japan.

[Kun Zhang](http://www.andrew.cmu.edu/user/kunz1/index.html), Carnegie Mellon University, USA.

[Masashi Sugiyama](http://www.ms.k.u-tokyo.ac.jp/sugi/), RIKEN / University of Tokyo, Japan.
