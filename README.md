# CulturalNetworks
agent-based model of cultural evolution on dynamic networks
## About this Model
In this model we examine the relationship between cultural evolution and the evolution of social network structure. In particular, we investigate the interplay between selectively neutral cultural trait variants, selectively neutral external markers (“tags”), and the maintenance of social ties in environments where collaboration is necessary and coordination of efforts is crucial to success.

we assume conditions under which it is (a) necessary to coordinate efforts of multiple actors to solve complex problems, (b) costly to maintain meaningful social connections necessary for cooperation, (c) disproportionately difficult for actors to ascertain possession of cultural traits in others directly, (d) possible for actors to direct their behavior based on the possession of observable markers, and we hypothesize that over time such populations will form distinct cultural clusters and meaningful cultural signs will emerge.

The model is a direct extension of the original Cultural Evolution Model. As in the previous model, agents possess cultural trait variants which are hidden to other agents and which are equivalent to choices in coordination games that the agents play with each other. They also possess tags, which are directly observable by the other agents, and a set of preferences for the tags. However, simulations of the original model demonstrated that the results heavily depend on the chosen network structure of the agent population. Moreover, the original assumption that social networks remain fixed throughout agent’s lifetimes, even for entire generations, is barely realistic in real-world scenarios. Therefore, the purpose of this model is to elucidate how the dynamics differ in the case when social networks are allowed to change during simulations, and if it is assumed that the cultural makeup of the agents and their cultural preferences have a direct effect on the deletion and creation of social ties.
## Instructions for running this Model

the main model is function 'culture_rewired.m'. The code is well-commented; in the comments you will find instructions on how to run the model from the MATLAB command line with the desired parameters. The 'matrices.mat' file contains sample matrices (networks) that need to passed to the 'culture' function as parameters. The user can generate other networks (matrices) with the use of the included 'adjmats' (for random networks) and 'small_world_batch' (for small-world networks) scripts. A complete description of the model can be found in the attached documentation PDF.
