# Performance Analysis of Zero-Trust multi-cloud
Performance Analysis of Zero-Trust multi-cloud [arXiv:2105.02334](https://arxiv.org/abs/2105.02334)

Short and sweet paper, does not have a lot of useful data or tests but does showcase that for testing performance in cloud settings one should not just test for one single cluster necessarily, but also between clouds. For this paper it was especially relevant as it relates to security and thus inter-cloud security whilst working with a single-setup environment through fx. Istio.

The measurements they themselves made do not illustrate too much however, so further testing should be performed if relevant to determine best approach. Their criteria were specifically for Zero-Trust configuration which they mention is implemented through the application of Istio.
