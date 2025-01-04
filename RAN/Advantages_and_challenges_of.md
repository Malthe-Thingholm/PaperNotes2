# NeutRAN: An Open RAN Neutral Host Architecture for Zero-Touch RAN and Spectrum Sharing
NeutRAN: An Open RAN Neutral Host Architecture for Zero-Touch RAN and Spectrum Sharing [arXiv:2301.07653](https://arxiv.org/abs/2301.07653)

A new category of papers, my familiarity with its contents comes from a Game Theory mindset specifically spectrum auction theory.

The setup for their situation is such that a vendor has ownership over a section of spectrum (bands of frequency etc. etc.), they then function as a neutral host that sublets that spectrum out to whoever wishes to use it for traffic without needing to own spectrum themselves on a permanent basis. The manner in which said subletting is performed is more of the central focus of this paper through their subletting/allocation algorithm which functions as a 'Quadratically Constrained Quadratic Programming (QCQP) optimization problem', i.e. an optimization problem with a set of constraints. 

To meet said algorithm they propose that K8s-like orchestration should handle the optimizer itself as it has to work continuously on input with a timestep output that requires listening to many external services, so many internal components on the cluster responsible for the subletting decisions, and those services themselves might sensible also be contained on some K8s platform as the temporary nature of the subletting defines their nature as waning and waxing (they themselves need to be scaled when in use).
