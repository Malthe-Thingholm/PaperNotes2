# LOAD BALANCING TECHNIQUES IN CLOUD: A REVIEW
LOAD BALANCING TECHNIQUES IN CLOUD: A REVIEW [https://www.jetir.org/papers/JETIR1808252.pdf](https://www.jetir.org/papers/JETIR1808252.pdf)

Pretty poor review paper, might be having a shortened version, however it's pretty hard to find the paper in one of the more proper places. Makes me wonder why it was found by Scholar when searching for another paper.

Seems like fuzzy techniques is a recurring topic wrt. load balancing.

I've independently had the thought that SVM/Kernel/Feature mapping could be useful for cluster topology wrt. load balancing where an underlying feature representation is learnt for the jobs arriving. Then perhaps in conjunction with clustering (number of clusters being the number of physical clusters/machines), jobs can be binned/batched hopefully in a fashion where they fit together (jobs averse to each other through fx. congestion should also be learnable) without huge compute at time of delegation. Clusters can have a higher scalar if they got more compute, load can be represented by a bias (underloaded = larger cluster). 

Followup thought, seems like load balancing maybe should be preferred to be ahead of scheduling in ML setups. 
