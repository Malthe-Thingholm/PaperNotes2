# Bunk8s: Enabling Easy Integration Testing of Microservices in Kubernetes
Bunk8s: Enabling Easy Integration Testing of Microservices in Kubernetes [arXiv:2207.06811](https://arxiv.org/pdf/2207.06811)

Valid paper, mainly raises the points that integration tests are important and not supported nor promoted enough in standard Kubernetes or Istio. They have broad-integration-testing as a focus point of something non-existant in Istio, where it seems at the uninitiated glance as something that can be circumvented through making proxies/dummies to simulate external services. (Broad testing in this paper i gather to mean integration testing with a mix of internal and external communication beteween services.)

When not just using Istio the associated technology 'Bunk8s' that they've made is a possibility to include as an alternative, a plus for it is that it is more lightweight than Istio and alternatives. But complicating the stack to save memory and performance is probably only sensible in projects of a size where Istio provides so many other valuable things that the use case seems very specific. 

But main takeaway remains, integration testing is important for microservice architecture as it can be seen as an extreme version of OOP methodologies.
