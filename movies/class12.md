# Favorite Movies: Breakout Activity for Class 12

I anticipate this task will be introduced during Class 11 (2025-10-07) and then actually happen in Class 12 (2025-10-09).

## Your Task(s)

You'll have 20-25 minutes to accomplish the following tasks.

1. Form a group of 4-5 people. Come up with a name for your group that each of you will remember at our next class. If your group has fewer than 4 or more than 5 people, raise your hand, and we'll change the groups around.
2. One person in your group will report the results of your work using **this Google Form**. Try to have someone who hasn't done this for prior work do this, so I can spread around the credit.
3. As a group, you will identify **two new variables** (one **categorical** and one **quantitative**) available on the internet (at least one of which should not come from IMDB) that could be added to the data to expand on what could be studied here in an interesting way. For each variable, we're hoping you will (a) identify a URL on the internet where those data seem to be available and (b) identify a **meaningful exploratory question** that incorporates that variable, along with at least one of the variables we have available in the existing data base. 
    - A current list of variables is found at the bottom of this page, and is also in the "Variable Descriptions" tab of the **movies_2025-10-07** Google Sheet in the Favorite Movies subfolder of our Shared Google Drive folder.
    - Again, at least one of the two new variables you select should come from a source other than [IMDB](https://www.imdb.com/). Two from non-IMDB sources is much better.
        - Some potential sources students have used in the past include: [Rotten Tomatoes](https://www.rottentomatoes.com/), [Flickchart](https://www.flickchart.com/), [Metacritic](https://www.metacritic.com/), [Bechdel Test Movie List](https://bechdeltest.com/), [The-Numbers](https://www.the-numbers.com/), [RogerEbert](https://www.rogerebert.com/), [Movielens](https://movielens.org/), [Filmcrave](https://www.filmcrave.com/), [Letterboxd](https://letterboxd.com/welcome/), [Oracle of Bacon](https://oracleofbacon.org/) and [Open Movie Database](https://omdbapi.com/), but please don't feel obliged to stick to these options.
    - Your first variable should be **categorical** (with 2-10 mutually exclusive and collectively exhaustive levels, and without a lot of missing data.) 
        - An example (that you shouldn't use, since I have it already) would be the Motion Picture Association's Rating (G, PG, PG13, R, NC17 or Not Rated) which is also available on IMDB's page for the film.
        - Another example you shouldn't use is anything to do with the genre of the movie. We'll go with what we have from IMDB.
        - The categories in your suggested variable can be either ordinal or nominal.
    - The other variable you suggest should be **quantitative**, so that it takes values across a range of numerical results, and has units of measurement. 
        - An example (that you shouldn't use, since I have it already) would be the percentage of raters on IMDB that rated the film at the maximum level (10 stars) which is a percentage ranging from 0% to 100%. This is available by clicking on the number of people who rated the film on the main IMDB page.
        - In this work, we'll require a quantitative variable to be any quantity that has at minimum 11 different observed values in our set of films. Eleven is too small a count, really, to declare something "quantitative" in practice, but we'll make the best of it.
4. Ensure that your group's reporter has completed **[the Google Form]** to report your group's response and has submitted the form successfully (they should receive an email confirmation.)

## Variables Included In `movies_2025-10-06`

The current codebook for the data set called **movies_2025-10-06**, is listed below. Additional information is in the *Variable Descriptions and Sources* tab in the **movies_2025-10-06** sheet available in our Shared Drive.

Variable | Description
:------------ | :-----------------------------------------------------------------------------------------------------
mov_id | Code # (Mxxx) - alphabetical with #s first; sequels after originals
movie | Name of Movie
year | Year Movie was Released
mpa | Motion Picture Association rating
length | Length of Movie (minutes)
imdb_ratings | # of IMDB public ratings as of September 2025
imdb_stars | # of stars (1-10) in IMDB public rating as of September 2025
imdb_pct10 | % of 10-star public ratings in IMDB as of September 2025
metascore | Metascore (0-100 scale) from critic reviews at Metacritic.com
critic_revs | # of critic reviews gathered at IMDB as of September 2025
oscars | # of Oscar (Academy Award) wins according to IMDB
awards | # of awards (wins) according to IMDB as of September 2025
imdb_genres | Movie's list of Genres (up to 10) as identified by IMDB
genre_count | Number of Genres identified by IMDB
director | Name of director(s) of film
star_1 | Name of first listed actor (star) in film
gen_1 | Gender of star_1 (M or F)
star_2 | Name of second listed actor (star) in film
gen_2 | Gender of star_2 (M or F)
star_3 | Name of third listed actor (star) in film
gen_3 | Gender of star_3 (M or F)
origin | Country (Countries) of Origin
lang_1 | Primary language used in the Movie
budget | Estimated Budget via IMDB (in $)
gross_northa | Gross Revenue in US and Canada ($)
gross_world | Gross Revenue Worldwide ($)
pct_na | % of gross_world from US and Canada
imdb_synopsis | Synopsis from IMDB Front Page
color | Color or Black and White movie (a few list both)
imdb_link | Link to IMDB public page for movie
imdb_id | IMDB Film ID # (just a useful and numeric code)
dr_love | Has Dr. Love seen this movie? (Yes or No) as of September 2025
mentions | # of times movie mentioned by 431 students in 2020-2025
list_20 | # of 431 students who mentioned this movie in Fall 2020
list_21 | # of 431 students who mentioned this movie in Fall 2021
list_22 | # of 431 students who mentioned this movie in Fall 2022
list_23 | # of 431 students who mentioned this movie in Fall 2023
list_24 | # of 431 students who mentioned this movie in Fall 2024
list_25 | # of 431 students who mentioned this movie in Fall 2025

