# A Cost-Efficient Container Orchestration Strategy in Kubernetes-Based Cloud Computing Infrastructures with Heterogeneous Resources
A Cost-Efficient Container Orchestration Strategy in Kubernetes-Based Cloud Computing Infrastructures with Heterogeneous Resources [http://clouds.cis.unimelb.edu.au/papers/HeteroContainerCloud-TOIT.pdf](http://clouds.cis.unimelb.edu.au/papers/HeteroContainerCloud-TOIT.pdf)

Excellent paper. Expands on topics related to the cost-cutting taken in the Stratus paper, with an increase in awareness of inequality between resources/nodes etc. Good paper to not confuse Heterogeneous for homogeneous...

Would love to see their implementation code, although their pseudocode is fairly readable. The actual application of it to the uninitiated is more nebulous. 

Some interesting areas they expand in compared to Stratus. The idea of batching jobs is again nice, the focus on letting nodes become 'cullable' instead of just utilization is sensible, the approach of categorizing tasks into different groups for batch jobs vs long-running services leads to a bit of thought. Such as when to ignore such (only similar tasks), when to use their kind of measures, and when to split some tasks/services out into new clusters and have inter-cluster communication. Also how much 'human' control is left I'm a bit unsure of.
