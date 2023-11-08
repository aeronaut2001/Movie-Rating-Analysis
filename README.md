# Movie-Rating-Data-Analysis
 <p align="left"> <img src="https://komarev.com/ghpvc/?username=aeronaut2001&label=Profile%20views&color=0e75b6&style=flat" alt="aeronaut2001" /> </p>
 
[![View My Profile](https://img.shields.io/badge/View-My_Profile-green?logo=GitHub)](https://github.com/aeronaut2001) 
 [![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/aeronaut2001?tab=repositories)

---
## Movie Rating Data Analysis using Apache Spark (pyspark)💥🐝

📝 Gain the skills 
---

 <h3 align="left">Languages and Tools:</h3>

<p align="left"> Cloud: </p>

<a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> </p>

<p align="left"> Version Control System: </p>

 <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> </p>

<p align="left"> Programming Language - PYTHON: </p>
    <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 

<p align="left"> BIG DATA TOOL AND SOFTWARES: </p> 
  <a href="https://hadoop.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hadoop/apache_hadoop-icon.svg" alt="hadoop" width="40" height="40"/> </a> 
  <a href="https://hive.apache.org" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Apache_Hive_logo.svg" alt="Apache Hive" width="40" height="40"/> </a>
<a href="https://spark.apache.org" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg" alt="Apache Spark" width="40" height="40"/> </a> 
<a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> </p>
 
 ---

## 📙 Project Structures :

- [x] **Problem Statement:**
- The objective of this project is to analyze movie data using Hadoop, Spark, and Hive. We aim to derive insights from the data, such as ratings, tags, and movie details, to understand user preferences and popular trends in the world of movies.

- [x] **Project Introduction:**
- Welcome to my movie data analysis project. To kick things off, I established a Hadoop cluster with Hadoop YARN, Hive, and Apache Spark. I accomplished this either using Docker for a local setup or on a cloud platform like AWS, GCP, or Azure.

- [x] **Data Loading:**
- First and foremost, I loaded three crucial data files - `movies.csv`, `ratings.csv`, and `tags.csv` - into my Hadoop Distributed File System (HDFS).

- [x] **Spark Data Analysis:**
- The heart of the project! I wrote Spark jobs to tackle specific analytical challenges in the movie data.
- I showed the aggregated number of ratings per year.
- I displayed the average monthly number of ratings.
- I visualized the distribution of rating levels.
- I identified the 18 movies that were tagged but not rated.
- I found movies that had ratings but no tags.
- For rated untagged movies with more than 30 user ratings, I displayed the top 10 movies in terms of average rating and number of ratings.
- I calculated the average number of tags per movie in `tagsDF` and the average number of tags per user, comparing it with the average number of tags a user assigns to a movie.
- I also identified the users that tagged movies without rating them.
- I calculated the average number of ratings per user in the ratings DataFrame and the average number of ratings per movie.
- I determined the predominant (frequency-based) genre per rating level.
- I found the predominant tag per genre and the most tagged genres.
- I identified the most predominant (popularity-based) movies.
- Finally, I listed the top 10 movies in terms of average rating (provided more than 30 users reviewed them).

- [x] **Data Storage:**
- At the end of each problem statement, I ensured that the output was stored neatly in a single CSV file with headers in the output HDFS path.

- [x] **Key Takeaway:**
- This project embodies the essence of utilizing Hadoop, Spark, and Hive to extract valuable insights from movie data. It emphasizes the importance of data organization for further exploration, decision-making, and a better understanding of user preferences and trends in the movie industry.
