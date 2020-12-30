---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Network data envelopment analysis in uncertain environment
======
* Abstract
  In the Network data envelopment analysis, in addition to external inputs and outputs of a decision-making unit, interactions between internal subprocesses are also respected. These interactions could be an essential part of an efficiency assessment of decision-making units, while in many circumstances, they are represented as undetermined quantitative values by the experts of the domain. Uncertainty theory, initiated in 2007 and then completed in 2009, is an axiomatic mathematical framework for formalizing human reasoning. Here, we consider the network DEA at which both external and internal data are provided by an expert and design a novel procedure in the efficiency evaluation process of decision-making units using the uncertainty theory. We consider the basic model for a typical small instance, and a crisp counterpart is provided. The presented numerical example could be evidence of the applicability of the methodology in practice.
* Collaboration with: Waichon Liob
* Publication date: 2020/10/1
* Journal: Computers & Industrial Engineering
* Volume: 148
* Pages: 106657
* https://www.sciencedirect.com/science/article/pii/S0360835220303910

Advances in induced optimal partition invariancy analysis in uni-parametric linear optimization
======
* Abstract
  In this study, we consider a family of uni-parametric linear optimization problems that the objective function, the right, and the left hand side of constraints are linearly perturbed with an identical parameter. We are interested in studying the effect of this variation on a given optimal solution and the behavior of the optimal value function on its domain.  This problem has several applications, such as in linear time dynamical systems.  A  prototype example is provided in dynamical systems as a justification for the practicality of the study results. Based on the concept of induced optimal partition, we identify the intervals for the parameter value where optimal induced partitions are invariant.  We show that the optimal value function is piecewise fractional continuous in the interior of its domain, while it is not necessarily to be continuous at the endpoints. Some concrete examples depict the results of the analysis.
* Collaboration with: N. Mehanfar
* Publication date: 2020/9/7
* Journal: Journal of Mathematical Modeling
* Pages: 10.22124/JMM.2020.16732.1448
* https://jmm.guilan.ac.ir/article_4259.html

Induced optimal partition invariancy in linear optimization: constraints perturbation
======
* Abstract
  In this paper, we study uni-parametric linear optimization problems, in which simultaneously the right-hand-side and the left-hand-side of constraints are linearly perturbed with identical parameter. In addition to the concept of change point, the induced optimal partition is introduced, and its relation to the well-known optimal partition is investigated. Further, the concept of free variables in each invariancy intervals is described. A modified generalized computational method is provided with the capability of identifying the intervals for the parameter value where induced optimal partitions are invariant. The behavior of the optimal value function is described in its domain. Some concrete examples depict the results. We further implement the methodology on some test problems to observe its behavior on large scale problems.
* Collaboration with: N. Mehanfar
* Publication date: 2020/8/5
* Journal: arXiv preprint arXiv:2008.02305
* https://arxiv.org/pdf/2008.02305

Identification of minimum set of master regulatory genes in gene regulatory networks
======
* Abstract
  Identification of master regulatory genes is one of the primary challenges in systems biology. The minimum dominating set problem is a powerful paradigm in analyzing such complex networks. In these models, genes stand as nodes and their interactions are assumed as edges. Here, members of a minimal dominating set could be regarded as master genes. As finitely many minimum dominating sets may exist in a network, it is difficult to identify which one represents the most appropriate set of master genes. In this paper, we develop a weighted gene regulatory network problem with two objectives as a version of the dominating set problem. Collective influence of each gene is considered as its weight. The first objective aims to find a master regulatory genes set with minimum cardinality, and the second objective identifies the one with maximum weight. The model is converted to a single objective using a parameter varying between zero and one. The model is implemented on three human networks, and the results are reported and compared with the existing model of weighted network. Parametric programming in linear optimization and logistic regression are also implemented on the arisen relaxed problem to provide a deeper understanding of the results. Learned from computational results in parametric analysis, for some ranges of priorities in objectives, the identified master regulatory genes are invariant, while some of them are identified for all priorities. This would be an indication that such genes have higher degree of being master regulatory ones, specially on the noisy networks.
* Collaboration with: Somayeh Bakhteh, Nader Chaparzadeh
* Publication date: 12 October 2018
* Journal:  IEEE/ACM Transactions on Computational Biology and Bioinformatics 
* Volume: 17, Issue: 3, May-June 1 2020
* Pages: 999 - 1009
* https://ieeexplore.ieee.org/abstract/document/8490740

Roman domination problem with uncertain positioning and deployment costs
======
* Abstract 
 In a connected simple graph, the weighted Roman domination problem is considered at which the cost of positioning at each vertex is imposed in addition to the costs of potential deployments from a vertex to some of its neighboring vertices. Proper decision in practice is prone to a high degree of indeterminacy, mostly raised by unpredictable events that do not obey the rules and prerequisites of the probability theory. In this study, we model this problem with such assumptions in the context of the uncertainty theory initiated by Liu (Uncertainty theory. Studies in fuzziness and soft computing, Springer, Berlin, 2007). Two different optimization models are presented, and a concrete example is provided for illustrative purposes. Weaknesses of the probability theory and fuzzy theory in dealing with this problem are also mentioned in detail.
* Publication date: 2020/2
* Journal:  Soft Computing 
* Volume: 24, Issue: 4
* Pages: 2637-2645
* https://link.springer.com/article/10.1007/s00500-019-03811-z

Application of Dempster-Shafer theory in combining the experts’ opinions in DEA
======
* Abstract
 In data envelopment analysis models, values of inputs, outputs and their slack weights are usually based on the domain experts’ opinions. While they play a key role in efficiency evaluation of decision-making units in practice, when there are more than one expert, the manager encounters with the problem of effective specification of final values. The problem may be worsen when the belief degree on the opinions is not complete and differs from one expert to the other, which consequently leads to different and sometimes conflicting analytic results. Belief function defined in Dempster–Shafer theory is a powerful tool to derive a possible solution in these circumstances. We adapt this theory to address such situations in data envelopment analysis. A linear optimisation model is devised as a new combination rule of experts’ opinions, which covers the drawbacks of some existing combination rules in the belief function theory. The methodology is visualised with simple examples. Moreover, the well-known Monte Carlo experimentation is used to test the performance of the proposed method.
* Collaboration with: Omid Yaghubi Agreh 
* Publication date: 2019/6/3
* Journal: Journal of the Operational Research Society
* Volume: 70 , Issue: 6
* Pages: 915-925
https://orsociety.tandfonline.com/doi/abs/10.1080/01605682.2018.1468858

Uncertain Network Interdiction Problem
======
* Abstract 
 Indeterminacy is an intrinsic characteristic of a decision making process. Sometimes there are no samples, and historical data are not enough for estimating an appropriate probability distribution for an indeterminate variable. In these situations, an option could be referring to an expert on the subject, and uncertainty theory is a potentially powerful framework to manage this sort of indeterminacy. In this theory, an undetermined input parameter is referred to as an uncertain variable and its distribution is constructed based on the opinion of an expert. This is the case in many practical problems such as in the smuggling networks and drug-trafficking networks. This paper considers the network interdiction problem that aims to minimize the maximum flow through a capacitated network from a source to a sink where the arc capacities are uncertain variables. It is proved that there exists an equivalent deterministic model to the uncertain network interdiction problem. The proposed method is applied on a test problem, and the results are compared with the associated deterministic counterpart.
* Collaboration with: Maryam Soleimani-Alyar 
* Publication date: 2018/5
* Journal: Journal of Uncertain Systems
* Volume: 12 , Issue: 2
* Pages: 141-150
http://www.worldacademicunion.com/journal/jus/jusVol12No2paper05.pdf


