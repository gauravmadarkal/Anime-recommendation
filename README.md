# Anime recommendation System
# Team members 
  - Adithiyya Kishoore
  - Bhargav Shandilya
  - Pratik Prasanna Raghavendra
  - Gaurav Madarkal

# Description of the project 
Anime has exploded in the past two years. Especially with the onset of the pandemic, it has reached the mainstream masses due to its presence on Netflix and Amazon Prime.
While a handful of anime are well-known, a lot of the hidden gems are yet to be discovered and enjoyed by the public. Our
main goal with this endeavor is to get a glimpse of obscure but high-quality shows, mostly for ourselves, based on genre
and length. Length is an important factor in anime as we might need anywhere from a few hours to a few years to
watch one. While there are a lot of recommendation systems and
websites already available for this purpose, the recommendations generally misfire on all cylinders, as we are not privy
to the behind-the-scenes stuff on which the system relies. This can be problematic as these anime tend to run really
long, a time-sink that we simply cannot afford to endure. With our recommendation system, we hope to get a closer
look at the metrics and cater the system to our needs. Also, using the existing ratings, we hope to analyze the
trends and get a feel for the parameters that could affect them. While the quality of the show is generally paramount
and takes center stage in how a show is rated, we hope to check whether the “meta-data” also plays a role in the critical
rating of the show by the users

# Summary of the question(s) sought and the answers 
 - Can we predict the average rating based on list of genre (one hot encoded), number of episodes, and type of anime. (Rating (Y) = X0 + X1(num. episodes) + X2 (Comedy-genre) + X3 (Action-genre) + ....)

 - Cluster anime based on rating and popularity and check the distribution of genres within each cluster.

 - If a user A likes an anime 1 (Death Note), and user B likes anime 1 and 2 (Naruto), what is the probability that user A likes anime B?

 - If a user enjoys anime 1 and anime 2, how likely are they to enjoy anime 3? (Recommendation system)

# Application of this knowledge 
With these results in hand, it is now possible for an anime creator to create an anime that might be well suited to get the best rating based on the number of episodes and genre of the anime. As we now know which anime's get the best ratings based on our linear regression model, we could tailor the number of episodes of animes of a particular genre. For example, in our model we predicted that most `shounen' anime benefit from having about 275+ episodes episodes. We see that beyond the 275 episode mark, the rating for these genre of anime, shoot up from a plateau.

Also, we could predict things the other way round. What genre of anime would a studio, say Toei Animation or Studio Ghibli, want to producing a series on a small scale for a great rating? Our model would be well suited to do just that. This would be an interesting application for the anime.

Let us suppose an anime has already been created and set for running. Based on the initial reception of the anime, we could get a good idea of how it would fare in the long run. But, to predict the popularity of the anime, in case we need to create merchandise for it, we would be in a much better position by relying on a robust model. While it might not be the only decider, it would be a great supplement to user surveys that are generally done. Thus, our logistic regression model would be applied here.

# Link to the video demonstration 
https://drive.google.com/file/d/1Os7wvmcHfO8dI97xcZTno-RHJxWN80h_/view?usp=sharing

# Link to your final project paper
https://drive.google.com/file/d/1bCh97rwPtNSgxeosnMf-soXwi6lhQRRF/view?usp=sharing
