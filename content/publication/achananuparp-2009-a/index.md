---
title: "Using Negative Voting to Diversify Answers in Non-factoid Question Answering"
date: 2009-11-02
publishDate: 2019-10-09T06:50:14.337601Z
authors: ["Palakorn Achananuparp", "Christopher C. Yang", "Xin Chen"]
publication_types: ["1"]
abstract: "We propose a ranking model to diversify answers of non-factoid questions based on an inverse notion of graph connectivity. By representing a collection of candidate answers as a graph, we posit that novelty, a measure of diversity, is inversely proportional to answer vertices' connectivity. Hence, unlike the typical graph ranking models, which score vertices based on the degree of connectedness, our method assigns a penalty score for a candidate answer if it is strongly connected to other answers. That is, any redundant answers, indicated by a higher inter-sentence similarity, will be ranked lower than those with lower inter-sentence similarity. At the end of the ranking iterations, many redundant answers will be moved toward the bottom on the ranked list. The experimental results show that our method helps diversify answer coverage of non-factoid questions according to F-scores from nugget pyramid evaluation."
featured: false
publication: "*Proceedings of the 18th ACM international conference on Information and knowledge management - CIKM '09*"
tags: ["Answer ranking", "Negative voting", "Non-factoid question answering"]
doi: "10.1145/1645953.1646203"
---

