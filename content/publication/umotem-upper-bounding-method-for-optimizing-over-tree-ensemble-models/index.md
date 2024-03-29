---
title: "UMOTEM: Upper Bounding Method for Optimizing over Tree Ensemble Models"
publication_types:
  - "2"
authors:
  - Georgia Perakis (MIT)
  - Leann Thayaparan (MIT)
  - Setareh Boroujeni (Oracle Retail Business Unit)
  - Kiran Panchamgam (Oracle Retail Business Unit)
  - and Rebecca Schubertruegmer (Oracle Retail Business Unit)
publication: submitted to Management Science
abstract: Machine learning has become core to forecasting and planning. However, when decision makers are provided with trained and more complex machine learning models, often these models are difficult to then optimize over. When tree-based ensemble models, such as Random Forest or XGBoost, are used in optimization formulations, they require an exponential number of binary decision variables. Optimization problems of this type do not scale well. We propose UMOTEM (Upper Bounding Method for Optimizing over Tree Ensemble Models), an algorithm for solving a constrained optimization problem where the objective function is determined by a tree ensemble model. The algorithm narrows the region of decision variables to an approximate region of optimality by iteratively optimizing using upper bounds as it moves down the trees in the ensemble, at each step only using information available at that depth of the tree. This significantly improves the problem's complexity, with the number of binary variables scaling only linearly, quickly outpacing the exponential growth of the alternative formulations. We show how this method can be used to jointly predict and optimize to save time building sub-optimal branches of the decision trees. We prove an expected optimality gap bound for Random Forest in terms of the forest's in-sample error and leaf separation and show when it is tight. We demonstrate computationally that our algorithm can capture at least 90\% of optimality on a variety of datasets. Finally, we show through work with Oracle Retail, for one of their fashion retailer client, how UMOTEM can increase revenue by 12-13\%.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-08-12T17:15:00.000Z
---
*2022 - Finalist, Revenue Management and Pricing Jeff McGill Student Paper Award

