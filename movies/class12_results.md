## Categorical Variables

Here are the categorical variables you suggested, along with *lightly edited* versions of the exploratory questions you created for them...

Group | Categorical Variable | Exploratory Question
:----------: | :-----------------: | :-----------------------------------------------------------------------------------
MLRAS | [Bechdel-Wallace Test](https://bechdeltest.com/)  | Do movies that pass the Bechdel-Wallace test[^1] have a higher number of stars on IMDB?
The Stats Cubs | [Bechdel-Wallace Test](https://bechdeltest.com/) | Are films with more female-identifying stars (of the first 3 listed stars) more likely to pass the Bechdel-Wallace test[^1]?
Blanked-out | [CinemaScore](https://www.cinemascore.com/) (collapsing + and -) | How strong is the association between the movie budget and CinemaScore rating?
Go CAVS! | [Does the dog die?](https://www.doesthedogdie.com/) | Given that there is a dog in the movie[^2] how does the average IMDB star rating vary on the basis of whether the dog lives or dies?



## Quantitative Variables

Group | Quantitative Variable | Exploratory Question
:----------: | :-----------------: | :-----------------------------------------------------------------------------------
Five Guys (We're Hungry) | Box Office Gross Earnings | Do movies with a female lead (gen_1) have higher worldwide gross box office earnings (in USD)?
Tukey | Box Office Gross Earnings | Is there an association between Oscar nominations and amount of money in box office ticket sales?
Something unique again  | Box Office Gross Earnings | Does the length of the movie impact the total gross box office collection
Sweater Weather | Movie Budget | What is the association between a movie's budget and its star rating on IMDB? 
The Undecisive Statisticians  | Potentially Triggering Events | Using a linear model, can the total number of emotional trigger events in a movie predict the movie picture association rating?
FortySixPeople | Violence and Gore Rating | How strong is the association between the Violence and Gore Rating from the "Kids In Mind" report and the MPA rating?
Movie HunteRs | "Critic's Consensus" Score | Does the gender of star 1 in each movie effect the critic consensus percentage on Rotten Tomatoes?



[^1] Here is a [video explaining the Bechdel-Wallace test](https://feministfrequency.com/video/the-bechdel-test-for-women-in-movies/). Bechdel-Wallace scores range from 0 to 3, and are a count of how many of these standards are met by the movie: 1. It has to have at least two named women in it. 2. Who talk to each other 3. About something besides a man. A passing score is 3, anything less doesn't pass the test.

[^2]: We plan to exclude TV shows, and movies where the question ""Does the dog die?"" have zero values. If the question has more Yes than No then we consider it as a Yes, and if there are more No answer than Yes, we will consider No as the answer to the question. If there are No dogs then we will exclude the movie.
