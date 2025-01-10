# Custom Scheduling in Kubernetes: A Survey on Common Problems and Solution Approaches
Custom Scheduling in Kubernetes: A Survey on Common Problems and Solution Approaches [https://dl.acm.org/doi/pdf/10.1145/3544788](https://dl.acm.org/doi/pdf/10.1145/3544788)

Super survey, again on scheduling in K8s. This one is a bit more specific in its domain constraints. Is intended, and looks to work great, as a referential work where you find the thing you want to improve upon and then go to some paper(s) that touches on that subject.

The general areas this paper, and the other scheduling surveys, revolve around are: Custom Resources and their integration, dynamic scheduling policies typically involving ML, better utilization of GPU's, consideration of physical topologies, energy consumption/'green-ness', generically better scheduling algorithms for specific areas (typically some reason they aren't the default, but if that doesn't apply to the implementation area then it's pure up-side), and a little bit of focus on 'fair' scheduling (fair as in Game Theory fairness/lack of envy etc.).

On the topic of better utilization of GPU's, I attended yesterdays Kubernetes Scheduling SIG meeting and a main topic was changes related to the compartmentalization of GPU's dedicated to the cluster such that different pods can have different segments, and that this can be coupled with generic improvements to the GPU scheduling problems though this work originally was related to a different Kubernetes SIG. But maybe it will be included in the February update.
