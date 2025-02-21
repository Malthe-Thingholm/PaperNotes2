# CUDACLAW: A high-performance programmable GPU framework for the solution of hyperbolic PDEs
CUDACLAW: A high-performance programmable GPU framework for the solution of hyperbolic PDEs [https://arxiv.org/abs/1805.08846](https://arxiv.org/abs/1805.08846)

Super cool paper. So this is all for solving hyperbolic PDEs/parallelised Riemann problems. This paper is about CUDAClaw which slots into Clawpack, which can use various Riemann solvers, to parallelize the Riemann solving. Then to allow for usage of CUDAClaw, they want to open it up to PyClaw which interfaces with Clawpack through Python (aka it's a Python library that can transform the function calls into FORTRAN code implementations for Clawpack stuff). Sadly this implementation seems to not have been finished (reading outside the paper), though another paper ["Accelerating wave-propagation algorithms with adaptive mesh refinement using the Graphics Processing Unit (GPU)"](https://arxiv.org/abs/1808.02638) appears to have also implemented a CUDA extension of Claw, this time into AMRClaw (and PyClaw from superficial reading). 

The paper itself is cool, a lot of knowledge on GPU/CUDA programming and their decision process.
