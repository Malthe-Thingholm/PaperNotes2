# Locality-Aware Scheduling for Containers in Cloud Computing
Locality-Aware Scheduling for Containers in Cloud Computing [https://ieeexplore.ieee.org/document/8259462](https://ieeexplore.ieee.org/document/8259462)

Good paper. Mainly about congestion vs locality. Congestion is kind of inversely related to batching, where multiple services hogging the same resource are unwanted, resulting in a preference for more spread (ala daemons etc.), and they then scale for that and minimizing 'travel' costs from localisation. So a mix of batching correlated stuff close together without trying to generally spread out. 

Good pseudoalgorithms.

Sparks the thought of whether batching algorithms might want to 'minibatch' and then spread the batches around. 
