## Somatic Variant Detection In Cancer Samples Using Whole Exome Sequencing Data

### 1.1 Overview


Welcome to the world of deciphering the genomic secrets hidden within cancer samples! In this guide, we expound on a detailed protocol involved in the identification of somatic single nucleotide polymorphisms (SNPs) and small insertions/deletions (Indels) using the power of Whole Exome Sequencing (WES). This guide is based on the Broad Institute's "Best Practices," utilizing the Genome Analysis Toolkit (`GATK`) for next-gen sequencing data analysis. Beyond mere variant identification, we delve into the intricacies of SNPs and Indels, annotating them with population allele frequencies and curated insights from GnomAD and ClinVar exploring tools such as VCFtools, SnpEff, and SnpSift enhance our genomic exploration, providing context to the identified variants. We highlight the cost-effective power of WES, focusing on protein-coding regions for a comprehensive view of the genetic landscape. To unearth somatic variants, we enlist Mutect2, a somatic variant caller that acts as our genomic detective. We'll guide you through the setup, ensuring you have the required files and software to embark on your variant discovery quest. But wait, there's more! We'll also touch upon alternative workflows using `VarScan Somatic`, offering you a diverse set of tools to tackle the genomic enigma.

