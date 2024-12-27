# Making Secure Software Insecure without Changing Its Code: The Possibilities and Impacts of Attacks on the DevOps Pipeline
Making Secure Software Insecure without Changing Its Code: The Possibilities and Impacts of Attacks on the DevOps Pipeline [arXiv:2201.12879](https://arxiv.org/abs/2201.12879)

Fun paper, outlines weak points with default K8s setups if not kept in mind. Most useful information is formatted neatly into two tables first being the weak points and second outlining specific attacks, with the mitigations outlined directly in the first table and for the second table in section 5.

It also documents the attacks themselves through command line code, could be incorporated in standard tests potentially.

Does not account for the use of service meshes, which at a cursory glance should mitigate the weaknesses outlined in the first table not mitigated by 2-factor authentication, and should help with all attacks outlined through the second table by mitigating privilege escalation.
