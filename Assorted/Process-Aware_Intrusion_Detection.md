# Process-Aware Intrusion Detection in MQTT Networks
Process-Aware Intrusion Detection in MQTT Networks[https://dl.acm.org/doi/pdf/10.1145/3626232.3653271](https://dl.acm.org/doi/pdf/10.1145/3626232.3653271)

Probably a good paper, haven't read enough similar papers to properly evaluate it. Is centered around the MQTT protocol for network messaging and describing a framework for datamining telemetry logs under MQTT protocol.

Raised the thought of even in 'secure' clusters where proper procedures are followed when utilizing fx. Istio, i.e. configuring ingress controllers and sanitizing input etc. That in 'shared' enough clusters (fx. multiple teams deliver different services), intra-network traffic might still need serious afterthought more than just following default Istio setups. 
