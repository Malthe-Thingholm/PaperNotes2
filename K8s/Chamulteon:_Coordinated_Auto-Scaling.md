# Chamulteon: Coordinated Auto-Scaling of Micro-Services
Chamulteon: Coordinated Auto-Scaling of Micro-Services [https://atlarge-research.com/pdfs/2019-bauer-icdcs-chamulteon.pdf](https://atlarge-research.com/pdfs/2019-bauer-icdcs-chamulteon.pdf)

Paper about autoscaling (particularly 'grouped' kind of scaling), but seems to be mostly centered around scaling on VM's. Comparisons are mostly made with a variety of old scaling algorithms.

It does contain a variety of solid performance indexes in its analysis, such as over/under provisioning, worst-point provisioning, performance. 

The way it functions through some predictive/proactive elements does spark the thought that there could be use cases in schedulers that are 'rush-hour' aware. Fx. one could model the average traffic timeline of a day as a normal distribution, when the scheduler encounters enough increase in traffic in accordance with the model it beings overprovisioning to account for the 'next time-index's predicted traffic. Together with this algorithms focus on group-scheduling this could also take the form of grouped services being tagged with 'swelling 2pm' or something to that form, with this being a taint that 'burstable 2pm' pods are resistant to. 
