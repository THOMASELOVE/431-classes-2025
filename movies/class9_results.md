# Results of "Favorite Movies" Breakout on 2025-09-30

## Variables of Interest

- `imdb_stars` (weighted average star rating: 1-10)
- `imdb_ratings` (# of users who gave the movie a star rating)
- `imdb_genres` (up to 8 genre categories per movie)
- `length` (length of movie)
- `mpa` (MPA rating of movie)
- `year` (year movie was released)

## Your Research Questions and My Efforts to Clean Them Up

- Dr. Love's suggested versions of your questions are **shown in bold**.
- Questions *in italics* are taken verbatim from your submissions.
    - Major problems with genres (`imdb_genres`) are that movies can have more than one genre (and as many as 8), and there are 20 different genres in our sample.
    - MPA ratings (`mpa`), like genres, include multiple categories (really everything other than PG, PG-13 and R) with very few observations.

1. TEL: **How well can we predict a movie's average IMDB rating using its length?** (`imdb_stars`, `length`)
    - *Do longer length movies have a better star rating?* (What would your cutoff for "longer" movies be?)
    - *Are longer movies more highly rated?* (What would your cutoff for "longer" movies be?)
    - *Is there a relationship between the length of the film and the imdb_stars (audience rating) of the film?* (Well, there is always "a relationship" between two variables, so you need to ask something like "how strong is it" or "is it well fit by a linear model")
2. TEL suggests: **How strong is the association between how often a movie is rated on IMDB and its number of stars?** (`imdb_stars`, `imdb_ratings`)
    - *Do films with more ratings have higher review scores?* (What would be your cutoff for "more" ratings?)
    - *Does the number of ratings a movie has correlate with the average star rating?* (Every set of quantities is correlated with every other set of quantities with the same number of observations, even if that correlation turns out to be zero.)
3. TEL suggests: **How strong is the association of a movie's MPA rating with its average IMDB rating?** (`imdb_stars`, `mpa`)
    - *Is increase in mpa rating correlate to increase in IMDB star rating?* (Avoid "correlate" - all variables correlate with each other, some have strong correlations, others have weak, but they are still correlated)
    - *Do different MPA ratings have different mean star ratings?* (Which ratings would you choose to look at? All MPA options, or just PG, PG-13 and R?)
4. TEL: **Do more recent films have higher average IMDB ratings?** (`year`, `length`)
    - *Are films that were released prior to 2005 longer on average than films released after 2005?* (OK, this could work as a cutoff)
    - *Does the creation year impact movie length?* (Well, there will always be some association, perhaps a weak one.)
    - *Are newer movies longer than older movies?* (Cutoff for "newer" movies? Same issue with my revision, I guess.)
    - *Is there a relationship between the year the film was released and the length of the film?* (The answer is always yes, there is *a* relationship, perhaps a weak one.)
    - *What is the relationship between the year a movie was released and its length?* (You really need to describe what sort of relationship you're looking to choose between.)
5. TEL: **Do older movies have more IMDB ratings?** (`year`, `imdb_ratings`)
    - *Do older films have more ratings?* (OK)
    - *Does the movie's year of release have an impact on number of star ratings at IMDB?* (Well, it will have *some* impact, or more technically correctly, *some* association. Impact implies some causation here, I think.)
6. TEL: **Which movie genres have the highest weighted average star ratings on IMDB?** (`imdb_stars`, `imdb_genres`) (Of course, we would still need to deal with overlap in the genres.)
    - *What is the relationship between genre and average IMDB rating?* (What sort of relationship is a possibility?)
    - *Does movie star rating vary between thriller, comedy, and family films?* (There are films that fall into several of these categories, and others that fall into only one. What to do?)
7. TEL: **Do older movies have higher weighted average star ratings on IMDB?** (`imdb_stars`, `year`)
    - *Do older movies have higher star ratings?* (group accidentally chose `imdb_ratings` and `year`) 
8. TEL: **Which MPA ratings have higher average IMDB ratings?**
    - (`imdb_ratings`, `mpa`) *Do PG13 rated movies have more IMDP ratings compared to other MPA groups?* (It's IMDB, not IMDP. Are you just looking at PG-13 vs. all others collapsed together?)
9. TEL: **Does the association of year and length vary by movie genre?** 
    - (`imdb_genres`, `imdb_ratings`, `length`) *Respective to genre, do longer movies have higher star ratings?* (I've tried to guess at what you mean by "Respective to genre" in my revision, but there's still the problem of overlapping genres to stop me from doing much.)

## Some Tougher Cases

- (`year`, `imdb_genres`) *Do certain year have more specific type of genre?*
    - Many years in the data have fewer than 4 movies. What to do about them? What is the question you actually want to answer here?
- (`imdb_stars`, `imdb_ratings`, `length`) *Does the length of the movie impact the ratings of the movie, imdb_ratings and Imbd_stars,(positively and negatively) ?*
    - This might work if you specified, for example, is the relationship between ratings and stars (it's IMDB, not IMBD) different for long movies vs. short ones, while specifying what you mean by "long" and "short", I suppose.
- (`imdb_stars`, `year`, `length`) *Longer and older movies have higher average IMDB ratings (imdb_stars) compared to more recent and shorter movies?*
    - In addition to the grammatical problems, you'd have to describe what "longer and older" means relative to "shorter and younger" in categories, I think.     

## First Movie all of you have seen from [Our List](movie_1ist.md)

Group | Members | First Movie on [Our List](movie_1ist.md) <br /> They've All Seen
:----------------: | :---: | :------------------------:
Go Guardians! | 4 | M-012 Avatar
LRSC | 4 | M-012 Avatar
(Han) Solo | 1 | M-001 3 Idiots
Buc-ees with the good hair | 5 | M-052 Despicable Me
The 300ers | 4 | M-005 300
Average Five | 5 | M-012 Avatar
M.R.B. (Movie Review Board) | 4 | M-012 Avatar
Just Keep Swimming | 5 | M-068 Finding Nemo
Anti P-values | 4 | M-063 Everything, Everywhere, All At Once
Bonferrani | 5 | M-240 Titanic
Rotten Tomatoes  | 5 | M-012 Avatar
