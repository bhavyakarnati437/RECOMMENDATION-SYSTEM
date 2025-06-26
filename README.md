# RECOMMENDATION-SYSTEM
COMPANY : CODTECH IT SOLUTIONS

NAME : KARNATI BHAVYA

INTERN ID : CT2MTDM438

DOMAIN : Machine Learning

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH
# DESCRIPTION

This project presents a Movie Recommendation System built using collaborative filtering techniques, specifically leveraging Singular Value Decomposition (SVD) for matrix factorization. The primary goal of this system is to recommend movies to users based on their past preferences, by analyzing patterns in the ratings of similar users or items. The system is developed using the Surprise library, which is a powerful Python scikit specifically built for building and analyzing recommender systems.

We utilize the MovieLens 100k dataset, a popular benchmark dataset in the recommender systems domain. This dataset contains 100,000 ratings from 943 users on 1,682 movies. Each user has rated at least 20 movies. The dataset also includes metadata such as movie titles and genres, which is used to make the output more meaningful and interpretable.

The core recommendation engine is based on matrix factorization using SVD (Singular Value Decomposition). Matrix factorization is a widely adopted technique in collaborative filtering, where the goal is to factorize the user-item interaction matrix into two lower-dimensional matrices that capture latent features of users and items. These features help predict how a user might rate an unseen item.

Once the model is trained, it is evaluated using Root Mean Squared Error (RMSE) — a standard metric to measure the prediction accuracy of recommender systems. A lower RMSE indicates that the predicted ratings are closer to the actual ratings, thus indicating a more reliable model.

A key enhancement in this project is the use of the tabulate library to present the recommendation results in a well-formatted tabular layout. While the default print statements only show raw item IDs and ratings, using tabulate improves the readability and presentation of results significantly. The recommendation output now includes movie titles, predicted ratings, and genres, making the system much more user-friendly and suitable for presentation or end-user reports.

To provide genre and title information for each movie, the project reads the u.item file from the MovieLens 100k dataset. This file contains metadata such as the movie's name, release year, and genre flags. The genre information is originally stored as one-hot encoded columns. A function is used to convert these columns into a single string containing all genres for each movie, which is then merged with the recommendation results.
# The final output 
shows the top 5 recommended movies for a subset of users. For each user, a table is generated using tabulate, which neatly presents:
The movie title
The estimated rating the user would give
The genres the movie belongs to

This structured output is not only helpful in evaluating the system’s suggestions but also makes it easier for non-technical stakeholders (e.g., managers, external reviewers, or internship evaluators) to understand the effectiveness of the system.

# Technologies & Libraries:
Python
scikit-surprise
pandas
tabulate

# Conclusion:
This project effectively demonstrates how collaborative filtering techniques, particularly matrix factorization using SVD, can be applied to build intelligent recommendation systems. The integration of metadata and formatted output with tabulate makes the results more meaningful and professional, ideal for real-world applications, academic demos, or internship project evaluations.

# OUTPUT

![Image](https://github.com/user-attachments/assets/c5baf92b-f3ec-4ba8-9bfd-6c7744655b08)
