## Content-Based Recommender

### Case-Based Recommendation

Strucutre a DB of "cases" around a set of relevant "attributes"
Query based on them

### Knowledge-Based

### TFIDF 

Ex: search engine

Weight = Term Frequency(TF) * Inverse Document Frequenty(IDF)

TF = number of occurrences of a term in the document

IDF = log(#documents/#documents with term) how rare the term exists in the document(s)

Weight will be high if the work appeared frequently in the doc and didn't appear in many document(s)

vector space model

![Alt text](/images/vector.png "Vector space")

We have a vector for user and a vector for item
Lets predict using those vectors. It is the cosine of the angle between the two vectors

Cons:
Can't handle interdependencies
Ex: I like action and romance, it will recommend to me movies with action and romance however, i may not like movie has both action and romance
