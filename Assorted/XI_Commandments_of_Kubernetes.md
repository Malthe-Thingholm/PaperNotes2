# XI Commandments of Kubernetes Security: A Systematization of Knowledge Related to Kubernetes Security Practices
XI Commandments of Kubernetes Security: A Systematization of Knowledge Related to Kubernetes Security Practices [arXiv:2006.15275](https://arxiv.org/abs/2006.15275)

Very useful paper. Serves as a 'what are people saying' overview of security practices regarding Kubernetes, retaining a count of how many are saying what. The 'best practices' are most likely a bit outdated seeing that the paper is from 2020, but following them seems to at most be a tiny bit of tedium or redundant work for the benefit of securing the clusters better.

My top 3 takeaways: 1 make sure impersonation is disabled unless any explicit case is needed and then set up that specific case. 2 use quotas (as inferred in other papers as well). 3 Separate namespaces. Additionally there are a number of points which Istio (or other service meshes) would seem to solve such as controlling access (now the role of ingress controllers) for API and having firewall and controlling internal access and logging etc. etc.
