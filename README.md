# Book_Data_Analysis
Instructions :
Read in the CSV using Pandas

Remove unnecessary columns from the DataFrame so that only the following columns remain: isbn, original_publication_year, original_title, authors, ratings_1, ratings_2, ratings_3, ratings_4, and ratings_5

Rename the columns to the following: ISBN, Publication Year, Original Title, Authors, One Star Reviews, Two Star Reviews, Three Star Reviews, Four Star Reviews, and Five Star Reviews

Create new column named "Total Reviews" which has the total number of reviews for each book

Create new column named "Average rating" and calculate the average rating for each book

Note: The average rating is a weighted average where each star rating is multiplied by the number of reviews for that rating, summed up, and then divided by the total number of reviews.

Use the apply function to create a new column that classifies books based on their average rating

We'll classify the books into categories:

'Excellent' for average ratings of 4.5 and above 'Good' for average ratings between 3.5 and 4.5 'Average' for average ratings between 2.5 and 3.5 'Poor' for average ratings below 2.5

Write the updated DataFrame into a new CSV file

Using the modified DataFrame that was created earlier, create a summary table for the dataset that includes the following pieces of information...

The count of unique authors within the DataFrame

The year of the latest published book in the DataFrame

Find the book with the highest average rating

Find the book with the most total reviews

Top 3 authors with the highest average ratings

Top 3 books with the highest total reviews

Calculate the percentage of books with more one-star reviews than five-star reviews

Calculate the percentage of books with an average rating above a certain threshold

Example,
Threshold: 4.0
Visualize the below questions for different types of plots of your choice.
Distribution of Average Ratings
Top 10 Books by Total Reviews
Distribution of Book Classifications
Top Authors by Average Rating (Top 10)
