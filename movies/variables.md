# List of Variables in `movies_2025-10-28`

Variable | Description | Source | Comment
:-----------: | :----------------------------------------------------- | :----------: | :-------------------------------------------------
mov_id | Code # (Mxxx) - alphabetical with #s first; sequels after originals | Dr. Love | New Variables
movie | Name of Movie | IMDB | Old Variables
year | Year Movie was Released | IMDB | 
mpa | Motion Picture Association rating | IMDB | 
length | Length of Movie (minutes) | IMDB | 
imdb_ratings | # of IMDB public ratings as of 2025-09 | IMDB | 
imdb_stars | # of stars (1-10) in IMDB public rating as of 2025-09 | IMDB | 
imdb_pct10 | % of 10-star public ratings in IMDB as of 2025-09 | IMDB | 
metascore | Metascore (0-100 scale) from critic reviews at Metacritic.com | IMDB | 
critic_revs | # of critic reviews gathered at IMDB as of 2025-09 | IMDB | 
oscars | # of Oscar (Academy Award) wins according to IMDB | IMDB | 
awards | # of awards (wins) according to IMDB as of 2025-09 | IMDB | 
imdb_genres | Movie's list of Genres (up to 10) as identified by IMDB | IMDB | There are 20 different imdb_genres. See this link for counts, and list.
genre_count | Number of Genres identified by IMDB | IMDB | There are 20 different imdb_genres. See this link for counts, and list.
director | Name of director(s) of movie | IMDB | 
star_1 | Name of first listed actor (star) in movie | IMDB | 
gen_1 | Gender of star_1 (M or F) in movie | Dr. Love | 
star_2 | Name of second listed actor (star) in movie | IMDB | 
gen_2 | Gender of star_2 (M or F) in movie | Dr. Love | 
star_3 | Name of third listed actor (star) in movie | IMDB | 
gen_3 | Gender of star_3 (M or F) in movie | Dr. Love | 
origin | Country (Countries) of Origin | IMDB | 
lang_1 | Primary language used in the Movie | IMDB | 
budget | Estimated Budget via IMDB (in $) | IMDB | 
gross_northA | Gross Revenue in US and Canada ($) | IMDB | 
gross_world | Gross Revenue Worldwide ($) | IMDB | 
pct_northA | % of gross_world from US and Canada | IMDB | 100*gross_northA/gross_world
box_off_m | Box Office Multiple | IMDB | gross_world / budget
color | Color or Black and White movie | IMDB | Color, BW and two movies list both Color & BW
imdb_link | Link to IMDB public page for movie | IMDB | 
imdb_id | IMDB movie ID #  | IMDB | Useful numeric code for some APIs
dr_love | Has Dr. Love seen this movie? (Yes or No) as of 2025-10 | Dr. Love | Movie on this list that I saw most recently: Parasite
mentions | # of times movie mentioned by 431 students in 2020-2025 | Dr. Love | 
list_20 | # of 431 students who mentioned this movie in Fall 2020 | Dr. Love | 
list_21 | # of 431 students who mentioned this movie in Fall 2021 | Dr. Love | 
list_22 | # of 431 students who mentioned this movie in Fall 2022 | Dr. Love | 
list_23 | # of 431 students who mentioned this movie in Fall 2023 | Dr. Love | 
list_24 | # of 431 students who mentioned this movie in Fall 2024 | Dr. Love | 
list_25 | # of 431 students who mentioned this movie in Fall 2025 | Dr. Love | 
stu_Yes | # of 431 students in 2025 who said they had seen this movie | Small Class Survey | NA for all movies not listed as a favorite by at least one student in 2025
stu_No | # of 431 students in 2025 who said they had not seen this movie | Small Class Survey | NA for all movies not listed as a favorite by at least one student in 2025
stu_Unsure | # of 431 students in 2025 unsure if they had seen this movie | Small Class Survey | NA for all movies not listed as a favorite by at least one student in 2025
bw_rating | Bechdel-Wallace Test Criteria Met (0-3) | bechdeltest.com | Criteria: (1) two women in movie who (2) talk to each other about (3) something besides a man. Pass = 3, Fail < 3
ebert | Movie Review (from Roger Ebert or other reviewer) rating (1-4 stars) | RogerEbert.com | 1 = worst, 4 = best
cinemascore | CinemaScore rating | cinemascore.com | Movies that open in less than 1,500 screens are not polled or reported
rt_critic | Rotten Tomatoes Tomatometer (% Fresh via Critics) as of 2025-09 | Rotten Tomatoes | 
rt_audience | Rotten Tomatoes Popcornmeter (% Fresh via Audience) as of 2025-09 | Rotten Tomatoes | 
rt_reviews | # of Critic Reviews gathered at Rotten Tomatoes as of 2025-09 | Rotten Tomatoes | 
rt_link | Link to movie at Rotten Tomatoes | Rotten Tomatoes | 
dogdie | Yes or No, from 2025-10 "Does the dog die" question | doesthedogdie.com | Shows whether there were more Yes or No votes (NA if even)
jumpscare | Yes or No, from 2025-10 "There are jump scares" question | doesthedogdie.com | Shows whether there were more Yes or No votes (NA if even)
addiction | Yes or No, from 2025-10 "Addiction" category with >=1 Yes | doesthedogdie.com | Any of: (1) Someone uses drugs or (2) Alcohol abuse or (3) There's addiction
triggers | # of Potential Triggering Event Categories with Yes in 2025-10 | doesthedogdie.com | https://www.doesthedogdie.com/categories details the 37 categories
dd_votes | # of votes for "Does the dog die" question in 2025-10 | doesthedogdie.com | If dd_votes < 2, then other doesthedogdie results are NA, other than link
dd_link | Does the Dog Die Link | doesthedogdie.com | https://www.doesthedogdie.com/categories details the 37 categories
kim_sn | Kids-In-Mind Sex & Nudity rating (1 - 10, higher = more) | kids-in-mind.com | 1 to 10 rating, with higher ratings = more sex and nudity
kim_vg | Kids-In-Mind Violence & Gore rating (1 - 10, higher = more) | kids-in-mind.com | 1 to 10 rating, with higher ratings = more violence and gore
kim_lang | Kids-In-Mind Language rating (1 - 10, higher = more) | kids-in-mind.com | 1 to 10 rating, with higher ratings = more troubling language
deaths | Human Deaths during the Movie (total) | List of deaths wiki | 
lb_rating | Letterboxd Rating as of 2025-10 | letterboxd.com | Average rating (1 to 5 stars = best)
lb_fans | Letterboxd Fans who have given Ratings as of 2025-10 | letterboxd.com | 
lb_watched | Letterboxd Members who have watched the movie as of 2025-10 | letterboxd.com | 
lb_link | Letterboxd Link | letterboxd.com | 
lb_love | Dr. Love's Letterboxd Rating | letterboxd.com | 0.5 (worst) to 5 (best) stars
fc_love | Dr. Love's Flickchart Ranking (1 = best, 2 = next best, etc.) | Flickchart.com | 1 = best, 2 = next best, and so forth, as of 2025-09 I'd ranked ~ 900 movies
fc_globalrk | Global ranking on flickchart (at flickchart dot com) as of 2025-09 | Flickchart.com | 1 = best, 2 = next best, and so on
fc_pctwins | % of matchups won on flickchart as of 2025-09 | Flickchart.com | 
fc_users | Flickchart users who've ranked movie as of 2025-09 | Flickchart.com | 
fc_no1 | Flickchart users who have movie as number 1 on their list as of 2025-09 | Flickchart.com | 
fc_top20 | Flickchart users who have movie in top 20 of their list as of 2025-09 | Flickchart.com | 
fc_link | Link to movie at FlickChart | Flickchart.com | 
imdb_synopsis | Synopsis from IMDB Front Page | IMDB | 
