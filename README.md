# Netflix Prize: Improving Movie Recommendations with Matrix Factorization

## Overview

The **Netflix Prize** was a competition launched by Netflix in 2006, offering a grand prize of **$1 million** to any individual or team that could improve the accuracy of its movie recommendation algorithm by at least **10%**. The goal was to enhance the performance of Netflix’s original recommender system, **CineMatch**.

A team of computer engineers from **AT&T Labs** won the grand prize by reducing the **RMSE (Root Mean Squared Error)** loss from **0.9525** (reported by Netflix's CineMatch algorithm) to **0.8572**.

The Netflix Prize challenge was a significant milestone in the development of modern **machine learning** and **collaborative filtering (CF)** techniques. It paved the way for more sophisticated approaches to product recommendations.

## Key Contributions

As demonstrated by the Netflix Prize competition, **matrix factorization models** proved to be superior to the classic **nearest-neighbor techniques**. Matrix factorization allows for the incorporation of additional information such as:

- **Implicit feedback**: User interactions that aren't explicitly rated, such as views or clicks.
- **Temporal effects**: The evolution of user preferences over time.
- **Confidence levels**: Weighting interactions based on user behavior and context.

These advances made it possible to provide more accurate and personalized recommendations.

## Winning Team’s Contribution

The team from **AT&T Labs** published a paper on their approach, which was featured in the **IEEE Computer Society**. Their machine learning algorithm, based on matrix factorization, is still partially used by Netflix in its production recommender system today.

## Objective of This Project

In this project, we aim to:

1. Study the paper published by the **AT&T Labs winning team** in IEEE Computer Society.
2. Explore the **matrix factorization** techniques and machine learning approaches they employed.
3. Understand how these methods contributed to the 10% improvement in recommendation accuracy.
4. Analyze the impact of the Netflix Prize challenge on modern recommender systems.

## Key Metrics

- **CineMatch RMSE (Netflix’s original algorithm)**: 0.9525
- **AT&T Labs Winning Team RMSE**: 0.8572
- **Improvement**: More than 10% reduction in RMSE

## Technologies

- **Machine Learning**
- **Collaborative Filtering (CF)**
- **Matrix Factorization**

## Conclusion

The Netflix Prize competition has driven significant advances in **recommender system algorithms** and **machine learning techniques**. The work done by the AT&T Labs team remains influential, as portions of their model are still used in Netflix’s production servers.
