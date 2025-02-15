# Empirical Analysis on CI/CD Pipeline Evolution in Machine Learning Projects
Empirical Analysis on CI/CD Pipeline Evolution in Machine Learning Projects [https://arxiv.org/abs/2403.12199v1](https://arxiv.org/abs/2403.12199v1)

Great paper. Very similar to "[CI/CD Pipelines Evolution and Restructuring: A Qualitative and Quantitative Study](https://mdipenta.github.io/files/icsme2021.pdf)". I like this one a bit better in approach and results found though, as it's a bit more up front with the approaches they're going to apply and why that's the case.

One main takeaway is that ML tasks tend towards modifying the build policy vastly more than other types of tasks/projects do. This could seem like it's because of many different reasons, some main ones that dependencies are more fragile for ML tasks, that they change often making it even more fragile, the building itself is fragile wrt. ordering etc. and ML tasks might tend towards 'meta' optimization through changes to the build policy.
