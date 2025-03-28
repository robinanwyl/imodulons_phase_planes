# imodulons_phase_planes
**BENG 212 Systems Biology and Bioengineering II - Winter 2025 - Project 2**

**iModulons and Phase Planes**

iModulons are independently modulated gene sets that are computed from gene expression data using independent component analysis. iModulon analysis is used to elucidate transcriptional regulatory networks in organisms such as *E. coli*. This project concerns the purine and pyrimidine iModulons in *E. coli*, which govern nucleotide metabolism and transport. The biological functions of these iModulons and their genes are explored using the `pymodulon` package. 

In addition, this project further analyzes data from Lim et al (2025), where the authors investigated transcriptional changes occurring in the transition from the exponential growth phase to the stationary phase in *E. coli*. My analysis focuses on the "recovery" of iModulon activity during the stationary phase, which was observed under carbon and nitrogen depletion conditions for the purine iModulon but not the pyrimidine iModulon. After examining time course plots of iModulon activity and gene expression, my findings suggest that this phenomenon is primarily connected to the expression of genes in the purine biosynthesis pathway - not purine salvage pathway genes or genes involved with purine iModulon regulation. Further analysis is required to determine the underlying mechanism.


Sources:

Sastry AV, Gao Y, Szubin R, Hefner Y, Xu S, Kim D, Choudhary KS, Yang L, King ZA, Palsson BO. The Escherichia coli transcriptome mostly consists of independently regulated modules. Nat Commun. 2019 Dec 4;10(1):5536.

Kundu BB, Krishnan J, Szubin R, Patel A, Palsson BO, Zielinski DC, Ajo-Franklin CM. Extracellular Respiration is a Latent Energy Metabolism in Escherichia coli. bioRxiv 2024.05.30.596743.

Lim HG, Gao Y, Rychel K, Lamoureux C, Lou XA, Palsson BO. 2025. Revealing systematic changes in the transcriptome during the transition from exponential growth to stationary phase. mSystems 10:e01315-24.
