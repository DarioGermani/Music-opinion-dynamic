# Music-opinion-dynamics

# Introduction
Music, across all ages, is an essential component that marks the important steps of people's lives: it leads the beginning or end of a love affair or friendship, it helps people to process and overcome a disappointment, or it revives good times. Even if we think that it all happens so spontaneously, scientific research tells us that the sympathy, the closeness and the similarity play a crucial role in social relationships: in our specific case we are therefore interested in better understanding the role of these factors by reconstructing the processes of influence that takes place among students during their interactions.

The aim of this research was focused on the dynamics of the opinion among teenagers through an Agent-Based Model. The empirical data obtained from a web survey were compared with the data from the simulation model in order to reproduce the above social phenomenon and to confirm the theoretical assumptions behind the model itself.

The integration between multi-agent systems and sociometry is considered to allow for conceptualizing the phenomenon as a diffusion study, especially in view of the sociological tradition and in particular the concepts of "personal influence" (Katz, Lazarsfeld, 1955) and "homophily" (Lazarsfeld, Merton, 1954) which, in this case, we hypothesise can be traced back to a dual mechanism able of explaining it: (1) the behaviour of peers occupying a high status within certain relational groups; (2) the interaction favoured by specific elements linked to the similarity between individuals.

The information had been collected through self-compiled online questionnaire, which consists of 24 questions, and submitted to 85 students from 7 classes of two different schools. Having interviewed limited groups such as the students of the school classes, it has made possible to use easily a proposal of integration between web survey and sociometry, deepening for each student the structure and the intensity of the relationships established with their classmates.

# Model
The model assumes a hybrid interaction system (Axelrod, 1997; Deffuant et al., 2000; 2002) from real data: agents influence each other with a strength based on a mu parameter (??). This represents that feature which tells how strongly the talker (Ego) get the opinion of the receiver (Alter), only if the difference between the features of the agents is less than a theta parameter (??). On one hand, these two inner workings suppose the exchange of views takes place according to the similarity/difference between the agents, but on the other, there are agents characterized by a greater strength (leadership opinion) than others following social influence derived from some of their features.

The distance between the features of the agents is a number between zero and one: the more the agents are similar the more the similarity value is close to zero; the more they are different the more the similarity value is close to one.

The general aspects of the model are as follows: 
1) the agents, which stand for our analysis units - the students - with all their features; 
2) the social network, which plays the same relational structure of the school groups; 
3) the opinions on various genres of music, which are "spread" during the simulation through a random algorithm unlike the previous main features.

![image](https://user-images.githubusercontent.com/67426509/145727169-52d3a5bd-2ba1-4613-877b-16a0c9302780.png)


# References
R. Axelrod (1997), ??The dissemination of culture: A model with local convergence and global polarization??, The Journal of Conflict Resolution, 41(2), pp. 203-226.

G. Deffuant, D. Neau, F. Amblard, G. Weisbuch (2000), ??Mixing beliefs among interacting agents??, Advances in Complex Systems, 3, pp. 87-98.

G. Deffuant, F. Amblard, G. Weisbuch, T. Faure (2002) ??How can extremism prevail? A study based on the relative agreement interaction model??, Journal of Artificial Societies and Social Simulation, 5(4), https://www.jasss.org/5/4/1.html.

E. Katz, P.F. Lazarsfeld (1955), Personal Influence: The Part Played by People in the Flow of Mass Communications, New York, Free Press; tr. it. L'influenza personale nelle comunicazioni di massa, Torino, ERV-ERI, 1968.

P.F. Lazarsfeld, R.K. Merton (1954), ??Friendship as a social process: A substantive and methodological analysis??, Berger, M., Abel T. e Page C. H. (a cura di), Freedom and Control in Modern Society (pp. 18-66), New york, Toronto, London, Van Nostrand, tr. it. in Lombardo C. (2001) (a cura di), Paul F. Lazarsfeld, Saggi storici e metodologici (pp. 45-101), Roma, Edizioni Eucos.
