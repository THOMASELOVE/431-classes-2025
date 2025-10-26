# List of Variables in `movies_2025-10-28`

Variable | Description | Source | Comment
:-----------: | :---------------------------------------------------------- | :----------: | :---------------------------
mov_id | Code # (Mxxx) - alphabetical with #s first; sequels after originals | Dr. Love | 
movie | Name of Movie | [IMDB](https://www.imdb.com/) | 
year | Year Movie was Released | [IMDB](https://www.imdb.com/) | 
mpa | Motion Picture Association rating | [IMDB](https://www.imdb.com/) | 
length | Length of Movie (minutes) | [IMDB](https://www.imdb.com/) | 
imdb_ratings | # of IMDB public ratings as of 2025-09 | [IMDB](https://www.imdb.com/) | 
imdb_stars | # of stars (1-10) in IMDB public rating as of 2025-09 | [IMDB](https://www.imdb.com/) | 
imdb_pct10 | % of 10-star public ratings in IMDB as of 2025-09 | [IMDB](https://www.imdb.com/) | 
metascore | Metascore (0-100 scale) from critic reviews at Metacritic.com | [IMDB](https://www.imdb.com/) | 
critic_revs | # of critic reviews gathered at IMDB as of 2025-09 | [IMDB](https://www.imdb.com/) | 
oscars | # of Oscar (Academy Award) wins according to IMDB | [IMDB](https://www.imdb.com/) | 
awards | # of awards (wins) according to IMDB as of 2025-09 | [IMDB](https://www.imdb.com/) | 

Variable | Description | Source | Comment
:-----------: | :---------------------------------------------------------- | :----------: | :---------------------------
imdb_genres | Movie's list of Genres (up to 10) as identified by IMDB | [IMDB](https://www.imdb.com/) | There are 20 [different imdb_genres](https://github.com/THOMASELOVE/431-classes-2025/blob/main/movies/class09.md#about-imdb_genres).
genre_count | Number of Genres identified by IMDB | [IMDB](https://www.imdb.com/) | There are 20 [different imdb_genres](https://github.com/THOMASELOVE/431-classes-2025/blob/main/movies/class09.md#about-imdb_genres).
director | Name of director(s) of movie | [IMDB](https://www.imdb.com/) | 
star_1 | Name of first listed actor (star) in movie | [IMDB](https://www.imdb.com/) | 
gen_1 | Gender of star_1 (M or F) in movie | Dr. Love | 
star_2 | Name of second listed actor (star) in movie | [IMDB](https://www.imdb.com/) | 
gen_2 | Gender of star_2 (M or F) in movie | Dr. Love | 
star_3 | Name of third listed actor (star) in movie | [IMDB](https://www.imdb.com/) | 
gen_3 | Gender of star_3 (M or F) in movie | Dr. Love | 
origin | Country (Countries) of Origin | [IMDB](https://www.imdb.com/) | 
lang_1 | Primary language used in the Movie | [IMDB](https://www.imdb.com/) | 
budget | Estimated Budget via IMDB (in $) | [IMDB](https://www.imdb.com/) | 
gross_northA | Gross Revenue in US and Canada ($) | [IMDB](https://www.imdb.com/) | 
gross_world | Gross Revenue Worldwide ($) | [IMDB](https://www.imdb.com/) | 
pct_northA | % of gross_world from US and Canada | [IMDB](https://www.imdb.com/) | 100*gross_northA/gross_world
box_off_m | Box Office Multiple | [IMDB](https://www.imdb.com/) | gross_world / budget
color | Color or Black and White movie | [IMDB](https://www.imdb.com/) | Color, BW and two movies list both Color & BW
imdb_link | Link to IMDB public page for movie | [IMDB](https://www.imdb.com/) | 
imdb_id | IMDB movie ID #  | [IMDB](https://www.imdb.com/) | Useful numeric code for some APIs

Variable | Description | Source | Comment
:-----------: | :---------------------------------------------------------- | :----------: | :---------------------------
dr_love | Has Dr. Love seen this movie? (Yes or No) as of 2025-10 | Dr. Love | Movie I saw most recently: Parasite
mentions | # of times movie mentioned by 431 students in 2020-2025 | Dr. Love | 
list_20 | # of 431 students who mentioned this movie in Fall 2020 | Dr. Love | 
list_21 | # of 431 students who mentioned this movie in Fall 2021 | Dr. Love | 
list_22 | # of 431 students who mentioned this movie in Fall 2022 | Dr. Love | 
list_23 | # of 431 students who mentioned this movie in Fall 2023 | Dr. Love | 
list_24 | # of 431 students who mentioned this movie in Fall 2024 | Dr. Love | 
list_25 | # of 431 students who mentioned this movie in Fall 2025 | Dr. Love | 
stu_Yes | # of 431 students in 2025 who said they had seen this movie | [Small Class Survey](https://github.com/THOMASELOVE/431-classes-2025/blob/main/movies/small_survey.md) | NA for all movies not listed as a favorite by at least one student in 2025
stu_No | # of 431 students in 2025 who said they had not seen this movie | [Small Class Survey](https://github.com/THOMASELOVE/431-classes-2025/blob/main/movies/small_survey.md) | NA for all movies not listed as a favorite by at least one student in 2025
stu_Unsure | # of 431 students in 2025 unsure if they had seen this movie | [Small Class Survey](https://github.com/THOMASELOVE/431-classes-2025/blob/main/movies/small_survey.md) | NA for all movies not listed as a favorite by at least one student in 2025

Variable | Description | Source | Comment
:-----------: | :---------------------------------------------------------- | :----------: | :---------------------------
bw_rating | Bechdel-Wallace Test Criteria Met (0-3) | [bechdeltest.com](http://bechdeltest.com/) | Criteria: (1) two women in movie who (2) talk to each other about (3) something besides a man. Pass = 3, Fail < 3
ebert | Movie Review (from Roger Ebert or other reviewer) rating (1-4 stars) | [RogerEbert.com](http://rogerebert.com/) | 1 = worst, 4 = best
cinemascore | CinemaScore rating | [cinemascore.com](http://cinemascore.com/) | Movies that open in less than 1,500 screens are not polled or reported
rt_critic | Rotten Tomatoes Tomatometer (% Fresh via Critics) as of 2025-09 | [Rotten Tomatoes](https://www.rottentomatoes.com/) | 
rt_audience | Rotten Tomatoes Popcornmeter (% Fresh via Audience) as of 2025-09 | [Rotten Tomatoes](https://www.rottentomatoes.com/) | 
rt_reviews | # of Critic Reviews gathered at Rotten Tomatoes as of 2025-09 | [Rotten Tomatoes](https://www.rottentomatoes.com/) | 
rt_link | Link to movie at Rotten Tomatoes | [Rotten Tomatoes](https://www.rottentomatoes.com/) | 
dogdie | Yes or No, from 2025-10 "Does the dog die" question | [doesthedogdie.com](https://www.doesthedogdie.com/) | Shows whether there were more Yes or No votes (NA if even)
jumpscare | Yes or No, from 2025-10 "There are jump scares" question | [doesthedogdie.com](https://www.doesthedogdie.com/) | Shows whether there were more Yes or No votes (NA if even)
addiction | Yes or No, from 2025-10 "Addiction" category with >=1 Yes | [doesthedogdie.com](https://www.doesthedogdie.com/) | Any of: (1) Someone uses drugs or (2) Alcohol abuse or (3) There's addiction
triggers | # of Potential Triggering Event Categories with Yes in 2025-10 | Here are [the 37 categories](https://www.doesthedogdie.com/categories)
dd_votes | # of votes for "Does the dog die" question in 2025-10 | [doesthedogdie.com](https://www.doesthedogdie.com/) | If dd_votes < 2, then other doesthedogdie results are NA, other than link
dd_link | Does the Dog Die Link | [doesthedogdie.com](https://www.doesthedogdie.com/) |
kim_sn | Kids-In-Mind Sex & Nudity rating (1 - 10, higher = more) | [kids-in-mind.com](https://kids-in-mind.com/) | 1 to 10 rating, with higher ratings = more sex and nudity
kim_vg | Kids-In-Mind Violence & Gore rating (1 - 10, higher = more) | [kids-in-mind.com](https://kids-in-mind.com/) | 1 to 10 rating, with higher ratings = more violence and gore
kim_lang | Kids-In-Mind Language rating (1 - 10, higher = more) | [kids-in-mind.com](https://kids-in-mind.com/) | 1 to 10 rating, with higher ratings = more troubling language

Variable | Description | Source | Comment
:-----------: | :---------------------------------------------------------- | :----------: | :---------------------------
deaths | Human Deaths during the Movie (total) | [List of deaths wiki](https://listofdeaths.fandom.com/wiki/List_of_Deaths_Wiki) | 
lb_rating | Letterboxd Rating as of 2025-10 | [letterboxd.com](http://letterboxd.com/) | Average rating (1 to 5 stars = best)
lb_fans | Letterboxd Fans who have given Ratings as of 2025-10 | [letterboxd.com](http://letterboxd.com/) | 
lb_watched | Letterboxd Members who have watched the movie as of 2025-10 | [letterboxd.com](http://letterboxd.com/) | 
lb_link | Letterboxd Link | [letterboxd.com](http://letterboxd.com/) | 
lb_love | Dr. Love's Letterboxd Rating | [letterboxd.com](http://letterboxd.com/) | 0.5 (worst) to 5 (best) stars
fc_love | Dr. Love's Flickchart Ranking (1 = best, 2 = next best, etc.) | [Flickchart.com](http://flickchart.com/) | 1 = best, 2 = next best, and so forth, as of 2025-09 I'd ranked ~ 900 movies
fc_globalrk | Global ranking on Flickchart as of 2025-09 | [Flickchart.com](http://flickchart.com/) | 1 = best, 2 = next best, and so on
fc_pctwins | % of matchups won on Flickchart as of 2025-09 | [Flickchart.com](http://flickchart.com/) | 
fc_users | Flickchart users who've ranked movie as of 2025-09 | [Flickchart.com](http://flickchart.com/) | 
fc_no1 | Flickchart users who have movie as number 1 on their list as of 2025-09 | [Flickchart.com](http://flickchart.com/) | 
fc_top20 | Flickchart users who have movie in top 20 of their list as of 2025-09 | [Flickchart.com](http://flickchart.com/) | 
fc_link | Link to movie at FlickChart | [Flickchart.com](http://flickchart.com/) | 
imdb_synopsis | Synopsis from IMDB Front Page | [IMDB](https://www.imdb.com/) | 
