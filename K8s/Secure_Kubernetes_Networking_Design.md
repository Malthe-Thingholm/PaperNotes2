# Secure Kubernetes Networking Design Based on Zero Trust Model: A Case Study of Financial Service Enterprise in Indonesia
Secure Kubernetes Networking Design Based on Zero Trust Model: A Case Study of Financial Service Enterprise in Indonesia [https://www.researchgate.net/publication/333879377_Secure_Kubernetes_Networking_Design_Based_on_Zero_Trust_Model_A_Case_Study_of_Financial_Service_Enterprise_in_Indonesia](https://www.researchgate.net/publication/333879377_Secure_Kubernetes_Networking_Design_Based_on_Zero_Trust_Model_A_Case_Study_of_Financial_Service_Enterprise_in_Indonesia)

Okay paper. Doesn't really expand on what is described in other 'Zero Trust' papers (verify access and default to blocking traffic, also log everything).

It does add offhandedly that a majority of hacking is done by internal actors. Making ingress control and logging not too helpful. Luckily Istio also helps with internal logging and security if configured right (can do zero trust). Thought here is that logging is more important, security will always fail at some point if the actor simply has physical access.
