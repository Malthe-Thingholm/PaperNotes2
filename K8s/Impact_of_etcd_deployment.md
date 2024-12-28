# Impact of etcd deployment on Kubernetes, Istio, and application performance
Impact of etcd deployment on Kubernetes, Istio, and application performance [arXiv:2004.00372](https://arxiv.org/abs/2004.00372)

Probably very high quality paper. Has an introductory section on how network routing is done in Kubernetes native and with Istio. Has awakened a wish for a complete end-to-end overview of both processes, preferably with illustrations, and with implications for testing areas and security weak points.

The remainder of the paper covers their experiments for the impact of Istio on performance, where they end up with a finding for etcd as a critical area when under heavy load. Here their finding is "Our data shows, however, that while Istio does cost in terms of resources, it is able to give a better overall performance for highly loaded systems in terms of successfully served requests". This is to be understood as the settings where there are fewer workers overall, and fewer workers per pod, Istio provides an increase in successfully served requests when compared to native. Yet as the number of workers increases the resource usage impact of Istio is felt. 

Overall, main takeaway is that for important setups one should probably have some tests specifically aimed at putting etcd under duress, and monitoring its behaviour. Understanding what puts it under the most stress and how to alleviate that should be a priority in the case of it showing signs of buckling.
