# Robbery on DevOps: Understanding and Mitigating Illicit Cryptomining on Continuous Integration Service Platforms
Robbery on DevOps: Understanding and Mitigating Illicit Cryptomining on Continuous Integration Service Platforms [https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833803](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833803)

Cool paper, aimed to detect malicious crypto-mining on CI platforms and combating it. The way they hamper such suspicious activity is to delay all hashing operations (majority of all crypto mining activity) with a whitelist for the few normal things that use hashing operations such as package installers. This does impact non-malicious hashing operations which they shrug off more or less. 

The crypto-mining which they detect is for trial versions on CI platforms, so checking for such should probably be done if you're ever to host such a platform.

An interesting relation they found is a large increase in this form of crypto-mining related to a currency when said currency peaks in value. I extrapolate this to the insight that maybe the value of these 'dark' cryptocurrencies should be followed and whatever checks possible should be run whenever they tend towards peaking.
