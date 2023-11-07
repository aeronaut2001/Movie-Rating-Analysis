# Movie-Rating-Analysis
Movie Rating Analysis using Apache Spark (pyspark)

**Problem Statement :**


1. Setup hadoop cluster with yarn, hive and spark in cloud gcp
2. three files movies.csv, ratings.csv and tags.csv
3. Load all three files in HDFS location
4. Write spark job to solve below mentioned problem statements <br>
a) Show the aggregated number of ratings per year. <br>
b) Show the average monthly number of ratings. <br>
c) Show the rating levels distribution. <br>
d) Show the 18 movies that are tagged but not rated. <br>
e) Show the movies that have rating but no tag.  <br>
f) Focusing on the rated untagged movies with more than 30 user ratings, <br>
show the top 10 movies in terms of average rating and number of ratings. <br>
g) What is the average number of tags per movie in tagsDF? And the average number of tags per user? <br>
 How does it compare with the average number of tags a user assigns to a movie? <br>
h) Identify the users that tagged movies without rating them. <br>
i) What is the average number of ratings per user in ratings DF? And the average number of ratings per movie? <br>
j) What is the predominant (frequency based) genre per rating level? <br>
k) What is the predominant tag per genre and the most tagged genres? <br>
l) What are the most predominant (popularity based) movies? <br>
m) Top 10 movies in terms of average rating (provided more than 30 users reviewed them) <br>
6. store the output of each problem statement in single csv with header in output HDFS path 
