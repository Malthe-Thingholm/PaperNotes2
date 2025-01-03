# Understanding the Security Implications of Kubernetes Networking
Understanding the Security Implications of Kubernetes Networking [https://balakrishnanc.github.io/papers/minna-ieeesp2021.pdf](https://balakrishnanc.github.io/papers/minna-ieeesp2021.pdf)

Good paper, contains some architecture overview over Kubernetes and their testbed framework, which they utilized for 3 different attack approaches. 1 being kinda typical denial-of-service attack with the other two being reverse-shell attacks assuming malicious user already has some level of entry into the network. All three attacks seem to be mitigated at least partially through use of ingress controllers in Istio and proper logging of network traffic (also in Istio), procedures they themselves also mention as being helpful for those scenarios.

Lastly they have three very nice tables describing different possible attack-vectors/targets in the K8s ecosystem, what areas the three scenarios would affect, and what kind of tools K8s has to protect the different areas following MITRE's D3FEND matrix. 
