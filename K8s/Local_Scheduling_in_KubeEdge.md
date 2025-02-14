# Local Scheduling in KubeEdge-Based Edge Computing Environment
Local Scheduling in KubeEdge-Based Edge Computing Environment [https://www.mdpi.com/1424-8220/23/3/1522](https://www.mdpi.com/1424-8220/23/3/1522)

Both an excellent paper, as well as a quite unuseful proposed algorithm. So a lot of interesting approaches are mentioned (I did not know about Lyapunov optimization beforehand) as well as a thorough, though fast-paced, explanation of KubeEdge's architecture/stack. 
Their figures/graphs also illustrate the throughput and delay impact of routing traffic between nodes. But their solution seems overly simplistic (if it's as described, just run each node as its own internal cluster wrt. load balancing i.e. independent of other nodes), though knowing if it's actually as described is a bit impossible as the code isn't available and no 'pseudoalgorithm' nor equally detailed detailing was given. 

All in all, illustrates well the problem in not deciding on a load balancing approach, yet I'd go with even the standard approach over theirs.
