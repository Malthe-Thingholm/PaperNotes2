# Zero trust implementation in the emerging technologies era: a survey
Zero trust implementation in the emerging technologies era: a survey [https://www.researchgate.net/publication/384451867_Zero_trust_implementation_in_the_emerging_technologies_era_a_survey](https://www.researchgate.net/publication/384451867_Zero_trust_implementation_in_the_emerging_technologies_era_a_survey)

Harmful paper. "As quantum computing presents new challenges to ZT", get real. Has a section breaking down the history of Zero Trust use and implementation, the validity of which the rest of the paper casts doubts over, as well as a couple of other segments.

One of these segments is about the dangers quantum computing presents, which devolves down to quantum Fourier transformations and Shor's algorithm, i.e. nothing new or at all relevant to Zero Trust (that's for encoding part of security to care about not policy adjustment). 

Another segment is about the dangers and opportunities of AI. For the dangers part it's at least somewhat on point with remarking on 'AI' and 'GPT' lowering the floor for access to developing fishing attacks etc. whilst otherwise being remarkably non-committal on other dangers. In the opportunity segment is the harmful part, they push forward the idea of using AI (non-specific as to what precisely they mean by 'AI' here) to monitor (kind of makes sense), recognize patterns (i.e. finding abnormalities, sure, that's a good use), and getting total responsibility for dynamically making and enforcing Zero Trust policies (wtf). 

A couple of additional comments. Surely Zero Trust is only this tough to implement when doing it from the bottom up yourself, options for defaulting to no access exist in Istio (and default Kubernetes to my belief). The 'standard' scenario these Zero Trust papers in general compare to is with a complete lack of security, in general what they provide is not much more sophisticated than following standard procedures of: compartmentalize processes, only allow necessary traffic, log traffic, don't give other processes admin levels over you just because they are internal. 

The survey part of this paper also leaves one wanting for more, they do include a lot of papers as reference, but mainly they draw a conclusion with no comment on what the paper itself said leaving me to have to trust the author of the survey (i do not).
