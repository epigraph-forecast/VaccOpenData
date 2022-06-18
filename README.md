# VaccOpenData
# README #

EpiGraph is a scalable, fully distributed simulator that is able to perform large scale stochastic and realistic simulations of the propagation of the flu virus. The current implementation of EpiGraph allows modeling the population via a realistic local interconnection network based on actual individual interactions extracted from social networks and demographic data. At inter-urban scale, we use a transportation model which allows the study of the spatial dynamics of the virus propagation over large geographical areas. EpiGraph also includes a model of the interaction between influenza spreading and climatic and meteorological factors, such as temperature, atmospheric pressure and humidity levels. From the computational perspective, EpiGraph is a network bound application written in C language and implemented on MPI. Internally, EpiGraph performs irregular memory access patterns related to sparse matrices used to model the individual interactions.



### Data ###

Each compresed file corresponds to the output data related to each experiment. The experiment list is:

6001 -> No vaccination

6002 -> Young first

6000 -> Elderly first

6500 -> Elderly first 56D

6700 -> Elderly first 2D
