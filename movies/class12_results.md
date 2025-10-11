## Categorical Variables

Here are the categorical variables you suggested, along with *lightly edited* versions of the exploratory questions you created for them...

Group | Categorical Variable | Exploratory Question
:----------: | :-----------------: | :-----------------------------------------------------------------------------------
MLRAS | [Bechdel-Wallace Test](https://bechdeltest.com/)  | Do movies that pass the Bechdel-Wallace test[^1] have a higher number of stars on IMDB?
The Stats Cubs | [Bechdel-Wallace Test](https://bechdeltest.com/) | Are films with more female-identifying stars (of the first 3 listed stars) more likely to pass the Bechdel-Wallace test[^1]?
Blanked-out | [CinemaScore](https://www.cinemascore.com/) | How strong is the association between the movie budget and CinemaScore rating[^2]?
Go CAVS! | [Does the dog die?](https://www.doesthedogdie.com/) | Given that there is a dog in the movie[^3] how does the average IMDB star rating vary on the basis of whether the dog lives or dies?
Movie Raters | [Does the dog die?](https://www.doesthedogdie.com/) | Is there a meaningful difference in numbers of dog deaths in more recent movies?
Fresh Tomatoes | Jump scares, from [Does the dog die?](https://www.doesthedogdie.com/) | Do movies with at least one jump scare have a higher worldwide gross revenue?
Owala Koalas | Addiction, from [Does the dog die?](https://www.doesthedogdie.com/) | Do action movies showcase addictions more than other genres?
100% Fresh | Fresh or Rotten rating, from [Rotten Tomatoes](https://www.rottentomatoes.com/) | How does the movie's budget vary by the Fresh or Rotten rating?
Clueless | Production Method, from [The Numbers](https://www.the-numbers.com/) | Are the number of mentions by 431 students strongly associated with production method[^4]?

## Quantitative Variables

Here are the quantitative variables you suggested, along with *lightly edited* versions of the exploratory questions you created for them...

Group | Quantitative Variable | Exploratory Question
:----------: | :-----------------: | :-----------------------------------------------------------------------------------
The Stats Cubs | [Letterboxd] users | Are films that are mentioned more frequently by 431 students over the past 5 years reported as being seen more often on Letterboxd? 
Owala Koalas | [List of Deaths Wiki](https://listofdeaths.fandom.com/wiki/List_of_Deaths_Wiki) | Do movies released before 2005 have more deaths than movies released after 2005?
MLRAS | Popcornmeter from [Rotten Tomatoes](https://www.rottentomatoes.com/) | Do movies with a higher Rotten Tomatoes Popcornmeter score also have a higher Metascore, from IMDB?
Go CAVS! | Popcornmeter from [Rotten Tomatoes](https://www.rottentomatoes.com/) | For horror movies, is the popcornmeter score higher than the Metascore, from IMDB?
Movie Raters | Popcornmeter from [Rotten Tomatoes](https://www.rottentomatoes.com/) | How strongly is the popcornmeter score associated with the number of IMDB ratings? 
100% Fresh | Audience Rating at [Rotten Tomatoes](https://www.rottentomatoes.com/) | How strong is the association between the Rotten Tomatoes audience score and gross worldwide revenue?
Blanked-out | Number of critic reviews at [Rotten Tomatoes](https://www.rottentomatoes.com/) | How strong is the association between the number of critic reviews on Rotten Tomatoes and IMDB (Metacritic)?
Fresh Tomatoes | First day revenues from [The Numbers](https://www.the-numbers.com/) | Do movies with higher budgets gross higher on the first day released? 
Clueless | Bankability from [The Numbers](https://www.the-numbers.com/) | Does the country of origin impact the worth of the actor?

### Notes

[^1]: Here is a [video explaining the Bechdel-Wallace test](https://feministfrequency.com/video/the-bechdel-test-for-women-in-movies/). Bechdel-Wallace scores range from 0 to 3, and are a count of how many of these standards are met by the movie: 1. It has to have at least two named women in it. 2. Who talk to each other 3. About something besides a man. A passing score is 3, anything less doesn't pass the test.

[^2]: We plan to exclude TV shows, and movies where the question "Does the dog die?" have no values. If the question has more Yes than No then we consider it as a Yes, and if there are more No answer than Yes, we will consider No as the answer to the question. If there are No dogs then we will exclude the movie.

[^3]: A movie’s overall CinemaScore can range from A+ to F, but we plan to collapse + and - into one letter category to reduce the number of levels.

[^4]: The "Production Method" falls into one of the following seven categories, it seems: Live Action, Animation/Live Action, Digital Animation, Hand Animation, Stop-Motion Animation, Multiple Production Methods, Rotoscoping.
