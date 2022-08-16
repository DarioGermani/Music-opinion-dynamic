# Music-opinion-dynamics

# Introduction
The main goal of this research was focused on study the dynamics of the opinion among teenagers by reconstructing the process of influence that take place during their interactions, raising further questions about the ways and reasons why individuals get in touch with others. The integration between Agent-Based Modelling and sociometry allowed the conceptualization of the phenomenon as a diffusion study, considered as the outcome of the imitative process triggered by any compliance motives especially in view of the sociological tradition. In particular, the concepts of personal influence (Katz & Lazarsfeld, 1955) and homophily (Lazarsfeld & Merton, 1954) can be traced back to a dual mechanism able of explaining it: (1) the behaviour of peers occupying a relevant position within relational groups (school classes); (2) the interaction favoured by specific elements linked to the similarity between individuals. The empirical data obtained from a web survey will compared with the data from the simulation model in order to re-produce the above social phenomenon and to confirm the theoretical as-sumptions behind the model itself. 

# Methodology
The collection of the information was carried out through the construction and administration of a self-compiled online questionnaire divided into 24 questions for a total of 85 respondents, divided into seven classes of two different schools. Having interviewed limited groups such as the students of the school classes, it was possible to use easily a proposal of integration between web survey and so-ciometry, thus deepening for each student the structure and the intensity of the relationships established with their classmates. 

# Model
The model integrates some features of «bounded confidence» (Deffuant et al., 2000; 2002) and «dissemination of culture» (Axelrod, 1997) assuming the following interaction dynamic: agents influence each other with a strength based on a convergence parameter (µ), which tells how strongly the talker gets the opinion of the receiver, but only if the difference between the features of the agents is less than a tolerance parameter (θ).  On one hand, these two inner workings suppose the exchange of views takes place according to the similarity among the agents; on the other hand, there are agents characterized by a greater strength than others in connection with the so-cial influence from their features themselves.

The distance among the features of the agents (2) is a real number between zero and one: where the more the agents are similar the more the similarity value is close to zero; the more they are different the more the similarity value is close to one.

The simulation is set up in the following way: (i) an agent-set (students) repro-ducing the same features of those obtained from the empirical analysis; (ii) a network topology reproducing the same structure obtained from the empirical analysis; (iii) a spread of music opinions through a random algorithm at the first step. 

# Results
The idea that people tend to interact more with their own kind has been empiri-cally validated also in the course of this investigation: the average value of the opinion distance increases as the similarity decreases. Basically, students with the same opinion on a certain musical genre are also those characterised by high similarity and strong ties. 

To understand the best match among parameters, capable of reproducing an opin-ion dynamic similar to the one observed, we implemented the model running some initial experiments. Through the analysed combinations, we can report those two that lead to the simulative results close to the empirical ones. In partic-ular: (i) low convergence and tolerance parameter (µ & θ = 0.25), where agents influence and interact lightly («low reciprocity»); (ii) high convergence and tol-erance parameter (µ & θ = 1), where agents influence and interact a lot («high reciprocity»).

Although none of them can replicate exactly the same empirical pattern, the «low reciprocity» scenario is the one that comes closest on certain values. The algo-rithm we suggested poses how individuals interact and convey opinions on musi-cal preferences: based on this, Agent-Based Modelling has proved to be a power-ful tool for testing hypotheses on social mechanisms.

# References
R. Axelrod (1997), «The dissemination of culture: A model with local convergence and global polarization», The Journal of Conflict Resolution, 41(2), pp. 203-226.

G. Deffuant, D. Neau, F. Amblard, G. Weisbuch (2000), «Mixing beliefs among interacting agents», Advances in Complex Systems, 3, pp. 87-98.

G. Deffuant, F. Amblard, G. Weisbuch, T. Faure (2002) «How can extremism prevail? A study based on the relative agreement interaction model», Journal of Artificial Societies and Social Simulation, 5(4), https://www.jasss.org/5/4/1.html.

E. Katz, P.F. Lazarsfeld (1955), Personal Influence: The Part Played by People in the Flow of Mass Communications, New York, Free Press; tr. it. L'influenza personale nelle comunicazioni di massa, Torino, ERV-ERI, 1968.

P.F. Lazarsfeld, R.K. Merton (1954), «Friendship as a social process: A substantive and methodological analysis», Berger, M., Abel T. e Page C. H. (a cura di), Freedom and Control in Modern Society (pp. 18-66), New york, Toronto, London, Van Nostrand, tr. it. in Lombardo C. (2001) (a cura di), Paul F. Lazarsfeld, Saggi storici e metodologici (pp. 45-101), Roma, Edizioni Eucos.
