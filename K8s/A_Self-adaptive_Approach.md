# A Self-adaptive Approach for Managing Applications and Harnessing Renewable Energy for Sustainable Cloud Computing
A Self-adaptive Approach for Managing Applications and Harnessing Renewable Energy for Sustainable Cloud Computing [arXiv:2008.13312](https://arxiv.org/abs/2008.13312)

Cool paper. Brings a couple of points up (mostly in references to focuses of other papers) about hardware utilization where fx. temperature and such are important factors to cost-effectiveness (and 'green-ness'). The paper itself is well written with nice graphs and tests.

Core concepts that seemed to help them was to cull the processes they could at 'peak' hours either for redistribution or to delay. And optimize towards utilization of batch jobs. The idea of collecting tasks that can be made parallel and wait with running them till a resource can be optimally utilized is intriguing, especially with progress being made for 'subletting' GPUs wrt. K8s. In general, proper pipelining of tasks to run cost-effectively might not have as adverse impacts on performance as one might think. 
