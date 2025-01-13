# Evolving High-Performance Computing Data Centers with Kubernetes, Performance Analysis, and Dynamic Workload Placement Based on Machine Learning Scheduling
Evolving High-Performance Computing Data Centers with Kubernetes, Performance Analysis, and Dynamic Workload Placement Based on Machine Learning Scheduling [https://www.mdpi.com/2079-9292/13/13/2651](https://www.mdpi.com/2079-9292/13/13/2651)

Deep methodical paper. Is almost entirely centered around the testing of an ML based scheduler for K8s. Also includes a section extolling the virtues of Cloud Native technologies in the beginning that's pretty good.

So this paper provides actual performance documentation for ML based scheduling in a meaningful way. Their data tells me three things, first that a dynamic scheduler taking minimum 'human' discernment to set up is something that provides actual value. Second that ML based scheduling can provide a lot of improvement in latency, and most likely many other areas, over both default and custom schedulers (unknown what custom scheduler but oh well). Thirdly that ML based scheduling is highly field/data-specific, i.e it does not transfer well, as was as I feared. 

This tells me that a dynamic optimization scheduler, based on key indicators that one can adjust or automate, could have a real impact.
