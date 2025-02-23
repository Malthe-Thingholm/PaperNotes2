# Accelerating wave-propagation algorithms with adaptive mesh refinement using the Graphics Processing Unit (GPU)
Accelerating wave-propagation algorithms with adaptive mesh refinement using the Graphics Processing Unit (GPU) [https://arxiv.org/abs/1808.02638](https://arxiv.org/abs/1808.02638)

Very cool paper. Is mostly about the AMR part, how it's implemented, and the effect of meta-parameters relating to that approach on performance. This performance testing is very extensive, and I'd venture that the results obtained could be used to inform other unrelated parallelization, as they relate to the overhead of CUDA thread creation vs computation needed on said threads, and other such topics.

The graphs themselves are of varying quality though.
