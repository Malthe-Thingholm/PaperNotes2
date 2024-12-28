# Dynamically meeting performance objectives for multiple services on a service mesh
Dynamically meeting performance objectives for multiple services on a service mesh [arXiv:2210.04002](https://arxiv.org/abs/2210.04002)

Cool paper, entirely about using reinforcement learning to adjust policy for routing between services. Purely run on simulated data though as far as i can tell. Does 'call back' to the paper 'Collaborative Learning-Based Scheduling for Kubernetes-Oriented Edge-Cloud Network' wherein they also tried to use machine learning to adjust policy. I prefer this papers approach of directly specifying utility functions to maximize towards, and further i'd prefer if working without the machine-learning part when possible to simply optimize depending on the last time-step for the utility function.

ML does seem to have its place though, and as seen in this paper, the underlying distribution model for the real-world interaction with the services is important for how such models should be trained, be that interaction genuine or malicious. 

Nice table for related work in scaling algorithm approaches towards the end.
