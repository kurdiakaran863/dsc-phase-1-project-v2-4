Project Overview

This project recommends the types of movies Microsoft should be making, using exploratory data analysis to generate insights and visualizations.

Business Problem:

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. Microsoft needs recommendations on what types of movies to make.


Data Understanding and Analysis:

1. Source of Data:

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

2. Understanding of the Data:

* The 'zippedData' folder, consists of datasets from the above mentioned sources. The files consists of different extensions .db, .csv(comma-separated- value), .tsv(text-separated-values) etc.
* Looking at the different data sets and exploring the data, in order to solve the business problem my analysis is more focussed on the genre of movies, the profits these genres have been making over the year, budget, the director and distributors. 

3. Analysis:

* By understanding the Business problem and viewing the data, I realized, focussing on the genre of movies would be a better idea to make accurate recommendations to Microsoft on the types of movies it should be making.
* I cleaned the data and created different data fraames, that would now help in exploring the different parameters I could use to make my recommendations.
* I wanted to know which are the generes that are gaining the highest profit. Based on the result, I was able to know the top 5 genres that were having the maximum profitability over the years.
* Based on the top five genres, I wanted to know which are the directors that have made movies which gained maximum profit over these genres.
* Based on the top five generes, I also wanted to know which are the distributors that have made movies which gained maximum profit over these genres.

4. Recommendations:
* For any studio, the genre of movie is important. I would recommend Microsoft to make movies based on the top five genres that I derived through my analysis.
* Directors play a very key role towards a movies success. I would recommend Microsoft to make movies with directors, which have had maximum ROI for the top 5 genres over the years.
* Distributors play a key role in marketing and financing a file.I would recommend Microsoft to make movies with distributors, which have had maximum ROI for the top 5 genres over the years.


Folder Details: 

* zippedData folder consists of the primary data used in this project
* Data Cleaning folder consists of two notebooks, that consists of the code implemented to clean the data
* EDA folder consists of two notebooks, that consists of the code implemented to perform Exploratory Data Analysis. 

Summary:

I was able to use the data from different sources to perform my analysis. Cleaned the data and made it ready for Exporatory data analysis. Based on the analysis, I was able to create recommendations to Microsoft on the types of movies it should be making.