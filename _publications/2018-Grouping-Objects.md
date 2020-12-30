---
title: "Grouping Objects to Homogeneous Classes Satisfying Requisite Mass"
collection: publications
permalink: /publication/2018-Grouping-Objects
excerpt: 'Grouping datasets plays an important role in many scientific researches. Depending on data features and applications, different constrains are imposed on groups, while having groups with similar members is always a main criterion.'
date: 2018-1-1
venue: 'Journal of Artificial Intelligence & Data Mining (JAIDM)'
paperurl: 'http://jad.shahroodut.ac.ir/article_988_c658adc85a5905c687f13853dcb213e1.pdf'

---
Abstract
======
  Grouping datasets plays an important role in many scientific researches. Depending on data features and applications, different constrains are imposed on groups, while having groups with similar members is always a main criterion. In this paper, we propose an algorithm for grouping the objects with random labels, nominal features having too many nominal attributes. In addition, the size constraint on groups is necessary. These conditions lead to a mixed integer optimization problem which is not convex nor linear. It is an NP-hard problem and exact solution methods are computationally costly. Our motivation to solve such a problem comes along with grouping insurance data which is essential for fair pricing. The proposed algorithm includes two phases. First, we rank random labels using fuzzy numbers. Afterwards, an adjusted K-means algorithm is used to produce homogenous groups satisfying a cluster size constraint. Fuzzy numbers are used to compare random labels, in both observed values and their chance of occurrence. Moreover, an index is defined to find the similarity of multi-valued attributes without perfect information with those accompanied with perfect information. Since all ranks are scaled into the interval [0,1], the result of ranking random labels does not need rescaling techniques. In the adjusted K-means algorithm, the optimum number of clusters is found using coefficient of variation instead of Euclidean distance. Experiments demonstrate that our proposed algorithm produces fairly homogenous and significantly different groups having requisite mass.

