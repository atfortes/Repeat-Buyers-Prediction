# Repeat Buyers Prediction - Challenge the Baseline

Tianchi Competition top 0.7% solution :trophy: ([51st](https://tianchi.aliyun.com/competition/entrance/231576/rankingList) out of 6803 teams at the time of submission)

Big Data Intelligence course project @ Tsinghua University

## Authors
[Armando Fortes](https://github.com/atfortes) & [David Pissarra](https://github.com/davidpissarra) & [Gabriele Oliaro](https://github.com/gabrieleoliaro)

## Overview

Merchants sometimes run big promotions on particular dates (e.g., "Black Friday" or "Double 11"), in order to attract a large number of new buyers. Unfortunately, there are many one-time deal hunters, and these promotions may have little long lasting impact on sales. To alleviate this problem, it is important for merchants to identify who can be converted into repeated buyers and focus on targeting on those potential loyal customers.

Accordingly, [Tmall.com](https://www.tmall.com/) - a platform for local Chinese and international businesses to sell brand-name goods to consumers in Greater China, owned by [Alibaba Group](https://www.alibabagroup.com/en/global/home) - made their accumulated long term user behaviour logs available and hosted a related [Tianchi competition](https://tianchi.aliyun.com/competition/entrance/23157), in order to solve this problem.

Follows the architecture of our best performing solution for the competition:

![arch](/docs/figs/arch_readme.png)

Further details on our solution can be found in the [report](https://github.com/atfortes/Repeat-Buyers-Prediction/blob/main/docs/report.pdf).

## Built With

- [XGBoost](https://xgboost.readthedocs.io/en/stable/)
- [CatBoost](https://catboost.ai/)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/)
