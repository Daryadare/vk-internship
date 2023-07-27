## 👀 Recommendation system

<div id="header" align="center">
  <img src="https://media.giphy.com/media/N2rLxtwaU9rBC/giphy.gif" width="300"/>
</div>

---

## 🍃 About project

**The point of the project is to recommend new movies based on user ratings of other films.** 

There are 6 related spreadsheets to work with:
1. ratings: has userID, movieID, overall movie rating and timestamp;
2. tags: has userID, movieID, movie tag and timestamp;
3. movies: has movieID, title (including release year), genres;
4. links: has movieID, imdbID, tmdbID;
5. genome_scores: movieId, tagID, relevance;
6. genome_tags: tagID, tag

**Process**
* Firstly the Exploratory Data Analysis was done;
* movies.csv refactoring;
* Create new DataFrame containing most active users by their userID and movies the rated (movieID);
* train/val/test split;
* model architecture;
* work in progress...