# User_Based_Film_Recommendation_System

This Python script demonstrates the creation of a movie recommendation system using **user-based collaborative filtering**. It uses **Pandas** and **NumPy** for data manipulation and analysis and calculates the similarity using **PearsonCoeffficient**

## Main Steps:

1. **Data Preparation:** The script reads two CSV files, 'movielens_movie_titles.csv' and 'movielens_movie_ratings.csv', containing information about movies and user ratings, respectively. It then combines this data into a single table for analysis.

2. **User Selection:** The script selects a target user, in this case, User 1, and extracts their movie ratings. These ratings are used as a basis for finding similar users.

3. **Similar User Identification:** It identifies users who have rated similar movies to the target user by calculating the Pearson correlation coefficient between the target user and all other users. The higher the correlation, the more similar the users.

4. **Top Similar Users:** The script sorts the users by their similarity to the target user and selects the top similar users.

5. **Weighted Recommendations:** Based on these similar users, the script calculates weighted movie recommendations. It multiplies the movie ratings of similar users by their similarity scores and sums these values to make movie recommendations for the target user.

6. **Recommendation Output:** The final output is a list of movie recommendations for the target user, sorted by their weighted average recommendation score.

This code can be further extended to create a fully functional movie recommendation system. It's a starting point for anyone interested in collaborative filtering-based recommendation systems.

