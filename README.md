# Music-opinion-dynamics

# Introduction
The aim of this research was focused on the dynamics of the opinion among teenagers through the implementation of an agent based model. The empirical data obtained from the analysis of social networks were compared with the data from the simulation model in order to reproduce this social phenomenon and to confirm the theoretical assumptions behind the model itself.

# Model
The model assumes a hybrid interaction dynamic (Axelrod, 1997; Deffuant et al., 2000; 2002) from real data: agents influence each other with a strength that is decided by a mu parameter (µ), a feature who tells how strongly the talker (Ego) takes the opinion of the receiver (Alter), but only if the difference about their features is less than theta parameter (θ). These two mechanisms assume that, on the one hand, the exchange of opinions takes place on the basis of the similarity/difference between the agents, while, on the other hand, there are agents characterised by a greater strength (leadership opinion) than others on the basis of the social influence derived from some of their features.

Distance between agents features is equivalent to a number between zero and one: the more similar the agents are, the similarity value will be to zero; the more different they are, they will tend towards the value one. 

Model's general aspects can be summarised as follows: (1) the agents, which correspond precisely to our units of analysis - the students - together with all their same features; (2) the social network, which also reproduces the same relational structure of school classes; (3) the opinions on the various genres of music, which, unlike the first two main features, are "diffused" during the simulation through a random algorithm.

