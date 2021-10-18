# Crowd Sentiment
An interface to know the crowd's inclination towards a specific topic/idea, with the help of tweets on/towards that topic/idea.

#### Some clarifications? ####
1. Get the tweets (from twitter API services) on a specific topic.
2. Preprocess to extract the tweet and other meta data from it.
3. Add an ad-hoc weightage algo to check if that tweet is really for our use.
4. As more tweets get added, do we need to run the algo for sentiments on all the data again or do we need to run on the new ones and aggregate from the previous
5. Where will we store the tweets? what will happen when we use up all the space? (need to delete tweets on regular basis too?) 
6. the calculation matrix once calculated, when new info comes up, how do we update the matrix/stats about our topic?
7. What will we show to the user? (how can I forward this as a message service to my phone?) to get regular update that some sentiment towards something is getting changed?

