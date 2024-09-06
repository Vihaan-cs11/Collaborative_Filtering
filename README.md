
Preface
In an era where information is abundant and easily accessible, the sheer volume of available literature can be overwhelming for readers seeking quality recommendations. Finding movies that align with a user's preferences often becomes a time-consuming task, especially with the limitations of current recommendation systems.

The Problem
Most current movie recommender systems rely on content-based filtering, which requires the manual engineering of features for each movie. These features are often vague, non-specific, and hard to define. Moreover, data on such features is typically limited and inaccurate. As a result, content-based systems tend to recommend extremely niche or novelty movies, which might not cater to a user's desire to explore popular films from a variety of genres or broaden their tastes.

The Solution
Collaborative Filtering (CF) solves these problems by not depending on manual feature engineering. Instead, it leverages patterns in user behavior and ratings to find latent features through matrix factorization techniques. CF allows similar users to recommend content to each other, helping users explore movies across genres and discover films they might not have encountered otherwise.

This project aims to implement three different approaches for movie recommendations:

User-to-User Collaborative Filtering (CF) – recommends movies based on the preferences of users with similar tastes.
Item-to-Item Collaborative Filtering (CF) – recommends movies similar to ones the user has already rated highly.
Matrix Factorization – uses techniques like Singular Value Decomposition (SVD) to uncover hidden factors influencing user ratings and make predictions.
Key Features:
Input: The name of a user.
Output: 5 personalized movie recommendations for the user.
How It Works
User-to-User CF: Identifies similar users by comparing their movie ratings and suggests movies that other similar users have liked but the current user hasn’t seen yet.

Item-to-Item CF: Finds movies that are similar to the ones the user has already rated or watched and recommends them accordingly.

Matrix Factorization: Uses a technique like SVD to decompose the user-movie rating matrix into latent features, enabling more accurate predictions of movie ratings based on past behaviors.
