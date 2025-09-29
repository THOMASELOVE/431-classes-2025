# Favorite Movies: Breakout Activity for Class 09

To be completed on 2025-09-30 (Class 09).

## The Six Variables We're Focusing On Today

We will use the `movies_2025-09-30` data in the **Favorite Movies** directory in our Shared Drive Folder, which describes 260 films mentioned as "favorites" by students in 431 for 2020-2025. 

There are six variables (`year`, `length`, `imdb_categories`, `imdb_ratings`, `imdb_stars` and `mpa`) that we will focus on today...

Variable | Sample Value | Explanation
:--------: | :------------: | ------------------------------------------------------------------------
**`year`** | 1968 | year movie was released
**`length`** | 149 | length of movie (in minutes)
**`imdb_genres`** | Adventure, Sci-Fi | Movie Genre Categories specified by IMDB (between 1 and 8 genres are listed, [see below](#about-imdb_genres))
**`imdb_ratings`** | 764,000 | Number of Star Ratings (IMDB)
**`imdb_stars`** | 8.3 | Weighted Average Rating (IMDB)
**`mpa`** | G | Rating by the [Motion Picture Association](https://www.motionpictures.org/); [see below](#about-mpa).

The other variables found in `movies_2025-09-30` are...

Variable | Sample Value | Explanation
:--------: | :------------: | ------------------------------------------------------------------------
`mov_id` | M-006 | code (M-001 to M-260): arranges in alphabetical order by title, ignoring starting "The" or "A"
`movie` | 2001: A Space Odyssey | film title according to IMDB
`imdb_synopsis` | - | IMDB Movie Synopsis (max. 250 characters)
`list_25` | 0 | # of students in Fall 2025 who selected this movie
`imdb_link` | - | Web link to IMDB main page for this movie

The **Variable Descriptions** tab in the Google Sheet has additional information on all of these variables.

### About `imdb_genres`

Across the 260 movies, a total of 846 genres are listed in **`imdb_genres`**. Each movie has 1-8 genres listed, and 20 different genres are listed. Here are the counts of individual genres for these movies (remember the mean number of genres was 3.25, median was 3) from most common (Drama, listed for 153/260 (59%)) to least common (Western 2/160 (1%)).

Genre | Count | - | Genre | Count | - | Genre | Count | - | Genre | Count 
---------- | ---: | --- |  ---------- | ---: | --- | ---------- | ---: | --- | ---------- | ---:
Drama | 153 |  | Fantasy | 59 | | Animation | 29 | | Horror | 12
Comedy | 103 | | Sci-Fi | 51 | | Mystery | 26 | | War | 11
Adventure | 87 | | Thriller | 50 | | Biography | 17 | | History | 6
Romance | 62 | | Family | 45 | | Musical | 17 | | Sport | 6
Action | 60 | | Crime | 34 | | Music | 16 | | Western | 2

### About `mpa`

Each of the 260 movies fits in one (and only one) of the 10 **`mpa`** categories listed here:

`mpa` | PG-13 | R | PG | Not Rated | G | Approved | TV-G | TV-14 | TV-MA | TV-PG 
:-----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | 
Count | 84 | 80 | 67 | 14 | 8 | 2 | 2 | 1 | 1 | 1

## Your Task(s) for Today

You'll have about 20 minutes to accomplish the following tasks.

1. Form a group of 4-5 people, ideally including at least person you don't know yet. Come up with a group name that each of you will still remember in a week.
2. One person in your group will report the results of your work using the Google Form found at <https://bit.ly/431-2025-movies-1> (**TO COME**). 
3. As a group, you will identify **two** exploratory questions about films in this sample that could be addressed using the six key variables (`year`, `imdb_categories`, `imdb_ratings`, `imdb_stars`, `length` and `mpa`) listed above.
    - A good question (a) explores relationships involving two or more variables from the data set (b) lets us use data from all (or almost all) of the films and (c) ends with a question mark.
    - As an example that fits at least (a) and (c), we might ask "Do dramas last longer than comedy films?" which could be answered using the `length` and `imdb_categories` variables, although (b) is a problem since some films are not listed as either Drama or Comedy.
    - The current version (dated 2025-09-30) of the movies data is available in our Shared Google Drive folder, or you can [download the Excel version here](**TO COME**).
4. Look at this [list of movies](movies_260.md). Alphabetically, what is the first movie (i.e., lowest `mov_id` value) that **all** of the members of your breakout group have seen? 
    - [The form](https://bit.ly/431-2025-movies-1) (**TO COME**) asks you to type in that movie's `mov_id` value and name. If there isn't a movie on the list that you've all seen, you'll type in "We couldn't find one."
5. Ensure that your group's reporter has completed [the Google Form](https://bit.ly/431-2025-movies-1) (**TO COME**)to report your group's results and has submitted the form successfully (they should receive an email confirmation.)
