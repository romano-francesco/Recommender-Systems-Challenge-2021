# Recommender-Systems-Challenge-2021
[Kaggle competition](https://www.kaggle.com/c/recommender-system-2021-challenge-polimi) for the course Recommender Systems from Politecnico di Milano (A.Y. 2021-2022. Our implementarions intensively use the library of the Recommender Systems course repository which can be found [here](https://github.com/MaurizioFD/RecSys_Course_AT_PoliMi).
## The task
The task was to create the best possible recommender of TV programs, exploiting informations of users, items and user-item interactions present in the [dataset](https://github.com/romano-francesco/Recommender-Systems-Challenge-2021/tree/main/Dataset).
## Our work
We explore the world of recommender algorithms by testing different aglorithms both with a Collaborative and Content Based approach, with particular attention over Collaborative algorithms. To increase the evaluation metric MAP (Mean Average Precision) we have built our final model which is an hybrid one composed by the algorithms: SLIM ElasticNet, SLIM BPR, MF IALS. In particular SLIM ElasticNet dimonstrates to be very effective over this dataset, so we tune it a lot by hyperparameter optimization.

In the folder [Challenge notebooks](https://github.com/romano-francesco/Recommender-Systems-Challenge-2021/tree/main/Challenge%20notebooks) you can find our experiments over single algorithms, our tuning and validation process and finally our best performing model. Our final MAP obtained was 0.48161 over the private dataset, and we placed 24/72 in the competition.
