# Job-Recommender

A Job Recommendation system for Nigerian graduates using the KNN algorithm and the Cosine Similarity.

a. Cosine Similarity

The Cosine similarity makes use of cosine of angles between two vectors to check for most similar items to make it'srecommendation. Each record have on the job posting would be checked with a user's resumé transformed to vectors. The values returned by this algorithm ranges from 0 to 1. Values closer to 0 signifies a low similarity between both vectors while values closer to 1 signifies strong similarity between both vectors.

b. K Nearest Neigbour Algorithm

The Nearest neighbors implements the content based technique by applying a distance based algorithm, in this case I used the euclidean distance. The Nearest neighbors calculate distance between two vectors space. Usually the values ranges from 0 to Infinity. So typically, the lesser the magnitude of the distance between the two vectors, the more likely they are similar and therefore recommended by the algorithm. But the higher the magnitude the less likely those vectors are similar and would be recommended.
