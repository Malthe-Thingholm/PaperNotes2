# Container Orchestration Honeypot: Observing Attacks in the Wild
Container Orchestration Honeypot: Observing Attacks in the Wild [link](https://dl.acm.org/doi/pdf/10.1145/3607199.3607205)

Super well-made paper, both informative and applicable. Is centered around assuming open endpoints to the internet in either K8s or Docker themselves (as well as amongst others Airflow). Main points are split into two parts.

First, they perform various scans through Shodan and Masscan for existing open endpoints that don't require authentication. All those they establish contact with through procedures outlined in [https://www.rfc-editor.org/rfc/rfc9116.pdf](https://www.rfc-editor.org/rfc/rfc9116.pdf), which they note few companies had listed properly, confirmed that it was not intended for the endpoints to be open. 

The second part is setting up a Honeypot by letting their various endpoints be open in a similar fashion as to their own search and then logging traffic to it. Here they manage to pinpoint who various attackers were and such, as well as monitoring the types of attacks and the goals of the attacks. Mainly it was to download crypto-mining capacity, through various means depending on the point-of-attack. In addition to Docker and K8s vulnerabilities they also had some VM's running on older and newer versions of Airflow, here they logged no attacks on the newer version and multiple on the old through known vulnerabilities. 

Main takeaways, keep various components updated to mitigate vulnerabilities, especially security-related ones. Set up some contact info for well-meaning researchers to access the security specialist for that section. And if possible check your own clusters through Shodan and masscan as they should not show up unless you have an open vulnerability.
