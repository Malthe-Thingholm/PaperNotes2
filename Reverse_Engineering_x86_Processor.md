# Reverse Engineering x86 Processor Microcode
Reverse Engineering x86 Processor Microcode [arXiv:1910.00948](https://arxiv.org/abs/1910.00948)

Cool paper. Through applying microcode patches to vulnerable architectures (here K8 and K10) without sufficient cryptographic security, they'd then be able to utilize microcode hooks to execute another piece of malicious software when encountering the code for said hook (which can be provoked through a web browser when browsing an injected website). 

The vulnerability seems to just be that they have broken the cryptographic measures for those architectures, as it seems to just be a hash over the microcode patch itself. 

With the encryption broken they spam random changes as microcode patches while observing if they get any changes corresponding to observables (register adresses and integers i believe). Afterwards they continually expand the scope of the reversed microcode, along with physical observation of part of the CPU after having 'flayed' it (metaphorically, they do multiple things including 'delayering'). 
