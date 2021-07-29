---
title: "Evaluation of Move Method Refactorings Recommendation Algorithms: Are We Doing It Right?"
authors: '<i>Evgenii Novozhilov, Ivan Veselov, Mikhail Pravilov, and Timofey Bryksin</i>'
collection: publications
permalink: /publication/2019-05-28-move-method-evolution
date: 2019-05-28
venue: "proceedings of <b>IWoR'29</b>"
paperurl: 'https://doi.org/10.1109/IWoR.2019.00012'
tool: 'https://github.com/JetBrains-Research/MoveMethodGenerator'
data: 'https://github.com/ml-in-programming/MoveMethodDataset'
pdf: 'https://www.researchgate.net/profile/Timofey-Bryksin-2/publication/335945222_Evaluation_of_Move_Method_Refactorings_Recommendation_Algorithms_Are_We_Doing_It_Right/links/5dee9cbc4585159aa470f15c/Evaluation-of-Move-Method-Refactorings-Recommendation-Algorithms-Are-We-Doing-It-Right.pdf'
abstract: '<p><b>Abstract</b>. Software refactoring plays an important role in increasing code quality. One of the most popular refactoring types is the Move Method refactoring. It is usually applied when a method depends more on members of other classes than on its own original class. Several approaches have been proposed to recommend Move Method refactoring automatically. Most of them are based on heuristics and have certain limitations (e.g., they depend on the selection of metrics and manually-defined thresholds). In this paper, we propose an approach to recommend Move Method refactoring based on a path-based representation of code called code2vec that is able to capture the syntactic structure and semantic information of a code fragment. We use this code representation to train a machine learning classifier suggesting to move methods to more appropriate classes. We evaluate the approach on two publicly available datasets: a manually compiled dataset of well-known open-source projects and a synthetic dataset with automatically injected code smell instances. The results show that our approach is capable of recommending accurate refactoring opportunities and outperforms JDeodorant and JMove, which are state of the art tools in this field.</p>'
---