# Collaborative Learning-Based Scheduling for Kubernetes-Oriented Edge-Cloud Network
Collaborative Learning-Based Scheduling for Kubernetes-Oriented Edge-Cloud Network [arXiv:2305.05935](https://arxiv.org/abs/2305.05935)

Super high quality paper. Maybe dubious conclusions they reach. The premise is that computing might be split between a pure-Cloud based setup and some semi-local machines (Edge Computing), where typically you would want the local machines to constantly be dedicated to the task at hand, and then scale to the more latency-heavy Cloud machines when local latency increases. 

This is solved by being smart with schedulers and load balancing and such. Fairly certain that this can be done in vanilla K8s, at least it is possible to write policy like this for Istio. What they propose is using a GNN (Graph-Neural-Network) to depict the edges and then using that network to adjust policy values instead of setting them manually, and this would also keep them updated automatically if needs adjust. 

Other various ML approaches to doing this are briefly visited, but i believe that while ML does actually make sense for this situation, one should really examine whether a manual approach wouldn't just make more sense. As setting up the ML environment and such is much more effort and still quite error prone when compared with playing whack-a-mole with a couple of machines for the load balancing.

Additionally, setting up a more generic but examinable statistics-based setup for determining load-balancing values might be a better approach. 
