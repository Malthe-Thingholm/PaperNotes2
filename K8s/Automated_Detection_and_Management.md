# Automated Detection and Management of Deprecated Helm Releases in Kubernetes Clusters
Automated Detection and Management of Deprecated Helm Releases in Kubernetes Clusters [link](https://www.researchgate.net/profile/Ionut-Catalin-Donca/publication/376024259_Automated_Detection_and_Management_of_Deprecated_Helm_Releases_in_Kubernetes_Clusters/links/6569f3c1b86a1d521b25fd75/Automated-Detection-and-Management-of-Deprecated-Helm-Releases-in-Kubernetes-Clusters.pdf)

Cool short paper, introduces a tool for Helm that in practice just checks for new versions of packages and whether the currently used version is decidedly deprecated. Seems useful and sensible. There is no linking to said tool however and many of the references used show no results on Google Scholar etc. 

The tool would work as a service in the cluster. Giving it access to also have some automated control over renewing and removing package versions would probably also introduce a significant security risk, so it might be for the best to make it in-house. Preferably a large vendor makes something similar or it's incorporated directly into Helm/K8s/Istio.
