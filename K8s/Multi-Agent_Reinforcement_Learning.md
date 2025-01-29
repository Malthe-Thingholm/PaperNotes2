# Multi-Agent Reinforcement Learning for Network Load Balancing in Data Center
Multi-Agent Reinforcement Learning for Network Load Balancing in Data Center [arXiv:2201.11727](https://arxiv.org/abs/2201.11727)

Such a good paper. Has a great review-heavy section in the beginning and continues with useful references throughout. The approach of modelling load balancing as a cooperative game is insightful, allowing for reductions in latency overhead as well as computing consumption for complicated load balancers by shrinking them to subsections of both hardware (area to cover) and load (requests etc.).

However, the major use cases for such a load balancer that is both tough to implement and maintain as well as consuming a considerable overhead (I'd expect so at least), seem to be better covered better by fx. work-stealing approaches that I've seen. Perhaps in scenarios where services themselves cannot be trusted between each other. Yet that seems to also mess up this papers approach (with how the services/nodes need to report their status to the LB). 

The useful scenario I'm currently thinking of would be for workloads with wide inaccuracy/variance in estimation, so adjustment is needed. Even adjustments necessitated by node downtime (crash, power outtage etc.) shouldn't be covered well by this approach. 

To wrap it up: This algorithm seems less practical than other approaches. Yet the approach looks super promising as an alternative for when RL/ML is performed anyway.
