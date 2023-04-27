# Movie-Lens

DESCRIPTION

Background of Problem Statement :

The GroupLens Research Project is a research group in the Department of Computer Science and Engineering at the University of Minnesota. Members of the GroupLens Research Project are involved in many research projects related to the fields of information filtering, collaborative filtering, and recommender systems. The project is led by professors John Riedl and Joseph Konstan. The project began to explore automated collaborative filtering in 1992 but is most well known for its worldwide trial of an automated collaborative filtering system for Usenet news in 1996. Since then the project has expanded its scope to research overall information by filtering solutions, integrating into content-based methods, as well as, improving current collaborative filtering technology.

Problem Objective :

Here, we ask you to perform the analysis using the Exploratory Data Analysis technique. You need to find features affecting the ratings of any particular movie and build a model to predict the movie ratings.

Analysis Tasks to be performed:

1. Import the three datasets
2. Create a new dataset [Master_Data] with the following columns MovieID Title UserID Age Gender Occupation Rating. (Hint: (i) Merge two tables at a time. (ii) Merge the tables using two primary keys MovieID & UserId)
3. Explore the datasets using visual representations (graphs or tables), also include your comments on the following:
4. User Age Distribution
5. User rating of the movie “Toy Story”
6. Top 25 movies by viewership rating
7. Find the ratings for all the movies reviewed by for a particular user of user id = 2696
8. Feature Engineering:
            Use column genres:

  8.1 Find out all the unique genres (Hint: split the data in column genre making a list and then process the data to find out only the unique categories of genres)
  8.2 Create a separate column for each genre category with a one-hot encoding ( 1 and 0) whether or not the movie belongs to that genre. 
  8.3 Determine the features affecting the ratings of any particular movie.
  8.4 Develop an appropriate model to predict the movie ratings
