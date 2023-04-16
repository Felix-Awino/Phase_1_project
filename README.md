# Phase_1 Project Submission

Please fill out:
* Student name: Felix Awino
* Student pace: part time 
* Scheduled project review date/time: N/A
* Instructor name: Everlyne Asiko
* Blog post URL:N/A

# PROBLEM STATEMENT

The project requires that we use exploratory data to review a set of movie data from a selected studio and use the findings as an insight into advising the head of Microsoft new moview studio on what films to create. 

## The Project will attempt to answer the Questions below. 

Having reviewed the dataset provided, I decided to work with the IM.DB SQL database which contained a good amount of data for consideration. The following key pointers could be retrived from the data through data cleaning and analysis as shall be demonstarted hereafter. 

The following key issues will be relevant in advising the M/S movie production director appropriately. 

*   Which are the top ten genre of movies in production by volume.
*   Which are the highest rated movies in production. 
*   Is there any correlation between the production volume and the movie ratings. 

## DATA ANALYSIS PROCESS

In order to answer the subject question, we shasll use Data Analysis with Pandas in order to work hthrough the provided dataset. We shall go through the below key steps in our data analysis process. 

1.   Data exploration in Pandas
2.   Data cleaning
1.   Data analysis in Pandas

## Data

The data for this analysis is drawn from different movie studio databases inlcuding im.db sql ratabase and tn.movie_budgets.csv database. The data provides details of the movie names and ratings and goes ahead to provide the grossing amounst made in the movie sales. 

## Methods

This project uses descriptive analysis, including description of the performance of the movies by the genre groupings. We were able to analyse the highest genres in active production, the highest rates genres and the highest grossing genress in terms of profits. This gave us a good overview of the kind of genres the the production studio needs to focus on.

## Results

We were able to pick out the top ten movies in production by volume. This could point to the market share in terms of movie production and consumption numbers. 

![](highestmovieproductionbygenre.png)

## Top Ten Rated Movies

We were also able to single out the top ten rated moviers by their genres. 

![](toptenratedmoviesbygenre.png)

## Top Ten grossing movies. 

Next we analysed the average cost of production vs the gross sales per movie to determine which movies grossed the highesdt amounts to guide the area of production to focus on. 

![](toptengrossingmovies.png)



## SUMMARY AND CONCLUSIONS

From the analysis we were able to pick out the following fsacts around the movies in the given dataset. 


*   The three top genres in production are drama, documentary and comedy. In the event that the movie house intends to reach to the largest audience, these three genres would be a good place to get started. 

*   On the highest rsted movies, the clear outcome from that analysis will be deebunked in the next conclusion that the highest rating movies are not necessaily the ones that rack in the most profits or the highest viewership. 

*   We were also able to pick out the highest grossing movies. The top three being 

1.   Adventure, drama, sport
2.   Fantasy,romance

1.   Family, fantasy, musical

These would be the top three recommendations to the production house were we to realise the highest profit margins. 

## Next Steps
Further analyses could yield additional insights on movie consumptions by demographics, we could also look into the regional distribution of movie consumption by the market share. 

We could also model a predictin for year by year trend on ovies consumed and predict the areas to focus in for future productions. 

## For More Information
See the full analysis in the Jupyter Notebook or review this presentation.

For additional info, contact Felix Awino @felix.awino@student.moringaschool.com

![image.png](data:image/png;base64,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)
