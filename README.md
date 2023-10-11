# User_Based_Film_Recommendation_System
This Python script leverages **TensorFlow** to calculate user skill **similarity based on a user's skills and a desired set of skills**. It reads user data from a JSON file, processes the data to construct a skill similarity model, and identifies the **top-K users who are most similar to a given set of skills**.

## Key Features:
1. Loads user data from a JSON file and extracts user URLs and skills.
2. Creates a skill vocabulary for all unique skills in the dataset.
3. Builds embeddings for users and skills.
4. Defines a user similarity model to compute skill-based similarities.
5. Allows users to specify a set of desired skills.
6. Finds and displays the top-K users with the highest similarity scores for the desired skill set.
7. This script provides a foundation for implementing user recommendation systems based on skill profiles, making it valuable for various applications, including job matching and skill-based social networks.

## Usage:
1. Prepare user data in a JSON file with appropriate structure.
2. Run the script and specify the desired set of skills.
3. The script will calculate and display the most similar users and their similarity scores.
4. Enjoy exploring user skill similarities with TensorFlow!
