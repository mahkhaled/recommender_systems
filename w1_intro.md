## Used Software

* Java
* Apache Maven (similar to Ant)
* LensKit
* IntelliJ IDE


## Examples of recommender systems



## Recommendation Algorithms

### Summary Stats

Ex: tripAdvisor

* No need for attributes 
* Only the rating table will used
* Average of all ratings

![Alt text](/images/non_personalized.png "Summary Stats")


### Content-Based Filtering

Ex: Personalized news feeds, personalized movies recommender
I like action moviews

* Knowledge base from item attributes

![Alt text](/images/content_based.png "Content Based")


### Collaborative Filtering

Ex: Social network recommenders
My friends like that so I may like it

* Opinions of other people to predict/estimate
* Sparse matrix
* User-user, select neighbors of similar taste and user their opinions
* Item-item, 
* Dimensionality reduction

![Alt text](/images/collaborative.png "Collaborative Filtering")