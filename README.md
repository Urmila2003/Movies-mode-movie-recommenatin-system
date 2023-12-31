# Movies-mode-movie-recommenatin-system

This task evaluates the ability of language models to propose relevant movie recommendations with collaborative filtering data.

# What is the task trying to measure?

This task is trying to measure the ability of language models to propose relevant movie predictions to a user, based on an input prompt sentence enumerating 10 liked movies.

# Abstract

Automatic recommendations (prediction of relevant items) is a widespread application of artificial intelligence. Content-based filtering in recommender systems leverages machine learning algorithms to predict and recommend new but similar items to the user. Recommending products based on their characteristics is only possible if there is a clear set of features for the product and a list of the user’s choices. 
![image](https://github.com/Urmila2003/Moviesmode-movie-recommenatin-system/assets/109129599/edbf66ae-27da-4426-9896-d3436567317a)
The model automatically suggests the third movie rather than the fourth, since it is more similar to the first two. This similarity can be calculated based on a number of features like the actors and actresses in the movie, the director, the genre, the duration of the film, etc.

# Introduction

As the World Wide Web is expanding in an exponential rate, the size andthe complexity of the information are increasing along with it. The Web nowcontains a massive amount of information, most of it does not interest theuser, either as unwanted information (advertisements, spam etc.) or ascontent irrelevant to his interests. However, every user has unique andpeculiar interests, which might correlate with a small percentage of the Web'scontent.  Therefore, it has become even more difficult and time consuming forthe users to find information that they are interested it. To help users findthe information that is in accordance with their interests the Web can bepersonalized, using recommender systems.
Recommendation systems are a special type of information filteringsystems. They are software applications that aim to support users in theirdecision making while interacting with a vast amount of information. Theyrecommend items of interest to the users based on preferences they haveexpressed, either explicitly or implicitly. The continuously expanding volumeand increasing complexity of information on the Web has therefore made suchsystems essential tools for users in a variety of applications , usuallyincluding information seeking or e-commerce activities. Recommendationsystems help users overcome the information overload problem by exposingthem to the most interesting items, and by offering novelty, insight, andrelevance. Recommendation technology is hence an important part of theinformation seeking problem that has emerged along with the World WideWeb. Major e-commerce sites such as Amazon is using recommendationtechnology in a number of different ways. Many adopters are on their way andenterprises are competing with each other in order to find the right andefficient way to use this technology, thus providing a more efficient service to their customers.

# Importance of Recommendation Systems

Netflix: According to a recent study by McKinsey, Netflix uses personalized recommendations, and it is responsible for 80 percent of the content streamed. This has allowed Netflix to earn 1 billion dollars in a single year. Netflix doesn’t spend much on marketing but on recommendations to improve customer retention.

# Cosine similarity

 Cosine  similarity among  two  objects measures  the  angle of cosine between  the two objects.  It compares two  documents on  a  normalized  scale.  It  can  be  done  by  finding  the  dot product between the two identities.
 
![image](https://github.com/Urmila2003/Movies-mode-movie-recommenatin-system/assets/109129599/dc813520-a97b-4e19-bd98-a31b8cf1a58d)


 As the above diagram shows, the angle between v1 and v2 is. Lesser  the angle  between the  two vectors  more is the similarity.  It  means  if the  angle  between  two  vectors  is small,  they  are  almost alike  each  other  and  if  the angle between the two vectors is large then the vectors are very different from each other

# Data source

top10K-TMDB-movies.csv is used as dataset for this project as it contains upto 10k movies. It contains the language ,overview and vote count of different movies.

# Result and Discussion

In the deep learning framework recommendation system, we have used  Cosine Similarity  and Content-based filtering  to predict  our result  and recommend  a  movie  to  the user  by running  the  code  in  python  using  NumPy  and  panda libraries.
In the deep learning framework recommendation system, we have used  Cosine Similarity  and Content-based filtering  to predict  our result  and recommend  a  movie  to  the user  by running  the  code  in  python  using  NumPy  and  panda libraries.

A. Experiment Result 

The  formula used  to measure  how  similar the  movies are based  on  their  similarities  of  different  properties. Mathematically,  it  shows  the  cosine  of  the  angle  of  two vectors  projected  in a  multidimensional space.  The cosine similarity is very beneficial since it helps in finding similar objects.

![image](https://github.com/Urmila2003/Movies-mode-movie-recommenatin-system/assets/109129599/2b1812b3-a285-41ff-b595-ae5172c5fd3d)

# Fig: This is the Cosine similarity formula which is used for the recommendation of movies 

![image](https://github.com/Urmila2003/Movies-mode-movie-recommenatin-system/assets/109129599/25ccac4b-ad31-4260-8534-c1bb0d9c7648)

# Fig: Cosine similarity

The angle theta between the two movies will determine the similarity between the two movies. The theta ranges from 0-1. If the value of the  theta is near 1 then it is most similar and if it's near to 0 then it is least similar. The movie will be recommended if it is close to 1 otherwise there would be no similarity between them. It will recommend the best movies to  the  user  according  to  the  Cosine  similarity.  After  the cosine similarity, we have used  a  normalised popular score through which  we get our  function of computing distance. Then  by using  the KNN  functionality, we  have found the nearest neighbour which will be recommended to the use

# Conclusion

We  have  illustrated  the  modelling  of  a  movie recommendation system by making the use of content-based filtering  in the  movie recommendation  system. The  KNN algorithm  is  implemented  in  this  model  along  with  the principle of cosine similarity as it gives more accuracy than the  other  distance  metrics  and  the  complexity  is comparatively low too. 
Recommendations systems have  become the most  essential fount of a relevant and reliable source of information in the world  of  internet.  Simple  ones  consider  one  or  a  few parameters while the more complex ones make use of more parameters  to  filter  the  results  and  make  it  more  user friendly. With the inclusion  of advanced deep learning  and other  filtering  techniques  like  collaborative  filtering  and hybrid filtering a strong movie recommendation system can be  built.  This  can  be  a  major  step  towards  the  further development of this model as it will not only become more efficient  to  use  but also  increase  the  business  value even further.

# References
[1] https://www.datacamp.com/community/tutorials/recommender-systems-python — tutorial for the basics involving data cleaning and using Count Vectorizers and Cosine Similarity for recommending movies (our chatbot builds on these ideas)

[2] https://youtu.be/DBn1GsryWCo- I used this tutorial to implement this recommendation model.

[3]https://r.search.yahoo.com/_ylt=AwrgLEeLS7lkPiUJoSFXNyoA;_ylu=Y29sbwNncTEEcG9zAzEEdnRpZANDQVEyNTUyM0NPXzEEc2VjA3Ny/RV=2/RE=1689893899/RO=10/RU=https%3a%2f%2fwww.geeksforgeeks.org%2fpython-implementation-of-movie-recommender-system%2f/RK=2/RS=tE8MbsZjJWcvCWeYgHBW3Crw1Rc- check this one out to have a better idea of what content based filtering is, and about how to implement it.
