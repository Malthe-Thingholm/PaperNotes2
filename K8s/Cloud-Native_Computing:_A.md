# Cloud-Native Computing: A Survey from the Perspective of Services
Cloud-Native Computing: A Survey from the Perspective of Services [arXiv:2306.14402](https://arxiv.org/abs/2306.14402)

Incredible survey. Does not have the same focus on scheduling (although large parts still fall under scheduling-related areas), and instead takes a more broad holistic view from the topic of services themselves. If I have a (major) critique, it is how, and what, can fit together from the different papers/technologies, without obstructing each other.

Two topics stood out as particularly new compared to the scheduling surveys: load balancing, and service migration. Service migration is a topic i have given little thought to this point, but it should probably be given serious thought at the beginning of projects to what degree the state of containers matter. 

The other topic of load balancing a new perspective to the topic of scheduling. As the right hand shouldn't war with the left, the scheduler must seek harmony with the load balancer. I do not believe that any paper covered in the surveys I've read has covered the interaction between load balancer and scheduler when discussing ML based custom variants. 

Though more and more I see the necessity of dynamic custom variants, and the use case for ML based ones. However still their universality seems lacking. The load-balancing papers are next for review, hopefully they will prod greater thoughts forward. 

Current thoughts are that MLE-based ML-models could be used in an Ensemble format to give indicators for nodes/pods/etc. both for scheduling and for load-balancing. Then have non-ML-based models operating on those indicators. This kind of approach should allow for universality through the 'voting' nature of Ensemble models coupled with the coverage said Ensemble models would have, dynamism through the resources (nodes/pods/etc.) automatically being fitted to the model, manual overrides being possible by configuring indicators oneself and adjusting the overall model to value some indicators higher or lower per the situation.

Not necessarily a critique of this survey, but the topics of security and testing were both practically omitted. An argument can be made that security isn't vital from the POV of a service, testing surely is. Slightly calling into question whether other important areas related to surveys too were omitted.
