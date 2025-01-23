# A Robust Service Mapping Scheme for Multi-Tenant Clouds
A Robust Service Mapping Scheme for Multi-Tenant Clouds[link](http://staff.ustc.edu.cn/~zgm1993/papers/2021+ToN+A%20Robust%20Service%20Mapping%20Scheme%20for%20Multi-Tenant%20Clouds.pdf)

Great paper, more of a surface/skim read this time. The approach of two-phasing it with a scheduling part run on a slower cycle and a load balance being run more often is interesting. The knapsack approach for scheduling is one that I've noticed recurring in regards to scheduling. The use of the Hungarian Algorithm where requests and service providers are treated as opposing sides in a bipartite graph is fascinating. In general i think there's a lot of work-room in graph representation of nodes and requests, especially as bipartite graphs. 

Randomized knapsack seems like it could be good for scheduling perhaps.
