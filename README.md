# Assessing the Effectiveness of Rating Pattern Transfer Models for Recommender Systems

With the ever-increasing popularity of entertainment streaming services, social media, e-commerce websites, etc., very large and diverse catalogs become usually hard to approach by users. Predicting the single customer's tastes and creating personalized lists of products has become a need for companies.
By aiming at alleviating this problem, recommender systems have recently become major players in the field of machine learning. These systems leverage the data of users and items of the catalog to extract information about each user's taste.

The quality of the results strictly depends on data quality and quantity. In particular, in practical applications, the amount of interactions has an extremely low density compared to the whole dataset. That is, users tend to interact with or review a very small subset of the catalog. This issue is known as the data sparsity problem.\\
Over the years, many different knowledge transfer solutions to this problem have been proposed. The majority of these techniques rely on the overlap of users, items, or both, between two datasets, source and target.

In this thesis, we aim to analyze a particular set of knowledge transfer techniques based on the rating pattern transfer approach without any data overlapping between datasets, called codebook transfer. Since their efficacy in specific tasks is not consistent across past evaluations, we show their formulation and performance in providing recommendations by analyzing their models and by performing experiments on several datasets, by including multiple baselines and an ablation study.\par
The results of the conducted experiments provide theoretical and empirical evidence that codebook transfer is not able to encode and transfer knowledge useful to provide recommendations and its use cannot be generalized to real domains.
