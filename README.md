# Music-opinion-dynamics

# Introduction
The aim of this research was focused on the dynamics of the opinion among teenagers through the implementation of an agent based model. The empirical data obtained from the analysis of social networks were compared with the data from the simulation model in order to reproduce this social phenomenon and to confirm the theoretical assumptions behind the model itself.

# Model
The model assumes a hybrid interaction system (Axelrod, 1997; Deffuant et al., 2000; 2002) from real data: agents influence each other with a strength based on a mu parameter (µ). This represents that feature which tells how strongly the talker (Ego) get the opinion of the receiver (Alter), only if the difference between the features of the agents is less than a theta parameter (θ). 

On one hand, these two inner workings suppose the exchange of views takes place according to the similarity/difference between the agents, but on the other, there are agents characterized by a greater strength (leadership opinion) than others following social influence derived from some of their features.
The distance between the features of the agents is a random number between zero and one: the more the agents are similar the more the similarity value is close to zero; the more they are different the more the similarity value is close to one.

The general aspects of the model are as follows: 
1) the agents, which stand for our analysis units - the students - together with all their features; 
2) the social network, which plays the same relational structure of the school groups; 
3) the opinions on various genres of music, which are "spread" during the simulation through a random algorithm unlike the previous main features.