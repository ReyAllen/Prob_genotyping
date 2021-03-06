# Prob_genotyping
R simulation of allelic dropout based on probabilistic genotyping of forensic software, BulletProof

A new statistical tecnhique in forensic PCR called probabilistic genotyping has been recently developed. It uses a statistical model (Cowell 2015) to accurately analyze human DNA samples that are too degraded for traditional forensic PCR analysis.

The statistical model is the basis for new forensic PCR software, which is being adopted internationally (EuroForMix, BulletProof) in private and federal, state forensics labs.

In order to train forensic scientists about the theoretical basis of BulletProof, training modules and simulations were developed.

This R script runs a simulation based on a random gamma distribution to illustrate allelic dropout differences between homozygous and heterozygous forensic markers for individual DNA contributions to a crime scene sample. 
Graph also prints Mu (estimation of average PCR peak height) and Sigma (peak standard deviation) per each simulation.

End product upon completion will include an additional tidyverse script for web-based interactive simulation for end-users unfamiliar with R. 
