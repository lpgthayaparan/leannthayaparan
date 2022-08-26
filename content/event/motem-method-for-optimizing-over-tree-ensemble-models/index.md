---
title: "RMP, 2021: MOTEM: Method for Optimizing Over Tree Ensemble Models"
abstract: >-
  Significant growth in data availability in revenue management, has made the
  useof machine learning tools core to forecasting and planning. In the case of
  e-commerce and retail, sophisticated machine learning models are key to
  accurate demand forecasting. This is often an essential input into decisions
  around pricing, promotions and inventory. However, the most sophisticated
  machine learning models are not easily optimized over. Specifically, when
  tree-based models, such as Random Forest or XGBoost, are used for demand
  forecasting they then require an exponential number of binary decision
  variables when they are used in optimization formulations. Optimization
  problems of this type do not scale well and result in intractable
  formulations. In this work, we propose a scalable approximation of the revenue
  optimization formulation that can optimize over ensemble tree models in linear
  time. We propose MOTEM (Method for Optimizing over Tree Ensemble Models), an
  algorithm for optimizing an objective function that is determined by an
  ensemble tree model. The algorithm uses the process of building an ensemble
  tree model to store information of the best payoff that could be achieved on
  either side of a tree’s branch. This information is calculated and stored
  without having to go down the entirety of the tree and can be used during the
  optimization phase to narrow the region of decision variables to an
  approximate region of optimality. This method works well with a variety of
  ensemble tree models, including Random Forest and XGBoost with either parallel
  or hyperplane splits. We demonstrate that our algorithm can capture over 90%
  of optimality on a variety of datasets. The algorithm is able to accomplish
  this while scaling only linearly in runtime, quickly outpacing the exponential
  growth of the alternative mixed-integer optimization. Finally, our work is in
  collaboration with Oracle to help improve their product offerings to retail
  and e-commerce clients. The work will be used to help Oracle inform clients on
  optimal pricing strategies and inventory decisions when demand is determined
  by an ensemble tree

  method.
location: Revenue Management and Pricing Section Conference 2021
date: 2021-06-28T20:30:05.202Z
date_end: 2021-06-28T21:30:00.000Z
all_day: false
event: Revenue Management and Pricing Section Conference 2021
event_url: https://sites.google.com/site/ozgesahin/informs-revenue-management-and-pricing-section-conference
publishDate: 2022-08-23T20:01:05.223Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
