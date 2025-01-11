# Atoll: A Scalable Low-Latency Serverless Platform
Atoll: A Scalable Low-Latency Serverless Platform [https://dl.acm.org/doi/pdf/10.1145/3472883.3486981](https://dl.acm.org/doi/pdf/10.1145/3472883.3486981)

Cool paper with a cool implementation. Aims to lower latency, with a focus on not missing deadlines (this includes being deadline-aware).

The way it does this is mainly through a decentralized scheduling approach, a decoupling of scheduling and allocation, and the allocation mainly being preallocated. They justify the preallocation through it mainly taking up memory resources which has tended towards being abundant in recent times. And the decentralization is to mitigate the control plane bottlenecking the cluster. 

In general/their testing it seems to have paid off, though they do not monitor actual resource usage to my discerning eye. Additionally, in the comparison to other approaches it is noticeable that in many cases they simply get the same performance as adopting preallocation with instant kickout (GDPI). 

Also, subjectively i dislike their graphs. Logarithmic graphs for a percentage of failure is not something i personally like. Additionally having 'deadline misses' as a metric when comparing to non-deadline-aware implementations is a bit much (might have missed that they are aware i guess). 
