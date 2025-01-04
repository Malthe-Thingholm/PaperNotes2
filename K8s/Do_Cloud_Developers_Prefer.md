# Do Cloud Developers Prefer CLIs or Web Consoles?
Do Cloud Developers Prefer CLIs or Web Consoles? [arXiv:2209.07365](https://arxiv.org/abs/2209.07365)

Poor execution of the graphs in the paper. The question asked in its title is answered through a pretty small sample size survey of 60 respondents and isn't qualitatively deep either. 

Most respondents prefer CLI for CRUD stuff and debugging, as expected, whilst there is more of a split with regards to general monitoring tasks where a sizable portion prefer web console. My own preferences that is in agreement with this result, is grounded in whilst doing CRUD and debugging one generally has some specific indicator to look for. Same goes for short-term monitoring (i.e does the specific service immediately crash upon traffic), whilst long-term monitoring you generally want to have the overall states filtered down to something easily interpretable preferably in the form of shapes etc. that can grant instant recognition of error states.
