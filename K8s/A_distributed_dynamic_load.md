# A distributed dynamic load balancer for iterative applications
A distributed dynamic load balancer for iterative applications [https://typeset.io/pdf/a-distributed-dynamic-load-balancer-for-iterative-kzrcst51vm.pdf](https://typeset.io/pdf/a-distributed-dynamic-load-balancer-for-iterative-kzrcst51vm.pdf)

Excellent paper. Their solution is made by gossiping between processors and kind of stealing workload, though the stealing can be prevented. 

It has introduced to me the concepts of viewing load balancing between centralized, decentralized, and hierarchical/hybrid. Immediately centralized seems more robust/secure, though less adaptive for adjusting currently queued jobs, decentralized seems like a security risk, even in this paper it seems like malicious nodes would be able to hamstring entire clusters in a multitude of ways. Hierarchical seems to at least have zones of control to mitigate damage, and is what my heart drifts to. 
