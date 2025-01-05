# Kubernetes Scheduling: Taxonomy, ongoing issues and challenges
Kubernetes Scheduling: Taxonomy, ongoing issues and challenges [https://dl.acm.org/doi/abs/10.1145/3539606](https://dl.acm.org/doi/abs/10.1145/3539606)

Very very impressive survey paper. Focuses almost completely on the scheduling part of K8s, with really comprehensive tables for lookups and related discussion sections for their opinion on how they stack up.

Of note, they view GPU resource scheduling as still being in its initial stages as a field, gang scheduling as something that when it's applicable is almost mandatory for optimization, and that some things to keep in mind when analyzing scheduling should be: Fairness (as in Game Theory), energy consumption/cost, resource utilization, dependency (gang scheduling), special resources like GPU's, and latency. 

That of course doesn't cover the entirety of this very dense paper, but it works best as a referential work that one can revisit when pondering optimization/architectural paths, exactly because of how dense it is. 
