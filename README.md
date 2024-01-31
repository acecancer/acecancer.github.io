## Somatic Variant Detection In Cancer Samples Using Whole Exome Sequencing Data

### 1.1 Overview

 Alternative workflows using VarScan Somatic are also discussed briefly.


Welcome to the world of deciphering the genomic secrets hidden within cancer samples! In this guide, we expound on a detailed protocol involved in the identification of somatic single nucleotide polymorphisms (SNPs) and small insertions/deletions (Indels) using the power of Whole Exome Sequencing (WES). This guide is based on the Broad Institute's "Best Practices," utilizing the Genome Analysis Toolkit (`GATK`) for next-gen sequencing data analysis. Beyond mere variant identification, we delve into the intricacies of SNPs and Indels, annotating them with population allele frequencies and curated insights from GnomAD and ClinVar exploring tools such as VCFtools, SnpEff, and SnpSift enhance our genomic exploration, providing context to the identified variants. We highlight the cost-effective power of WES, focusing on protein-coding regions for a comprehensive view of the genetic landscape. To unearth somatic variants, we enlist Mutect2, a somatic variant caller that acts as our genomic detective. We'll guide you through the setup, ensuring you have the required files and software to embark on your variant discovery quest. But wait, there's more! We'll also touch upon alternative workflows using `VarScan Somatic`, offering you a diverse set of tools to tackle the genomic enigma.





# Somatic Variant Detection in Cancer Samples Using Whole Exome Sequencing Data

## 1.1 Overview

Welcome to the world of deciphering the genomic secrets hidden within cancer samples! In this guide, we'll take you on a journey through the intricacies of identifying somatic single nucleotide polymorphisms (SNPs) and small insertions/deletions (Indels) using the power of Whole Exome Sequencing (WES).

### Unveiling Genomic Mysteries

Unlocking the genetic mysteries of cancer requires cutting-edge techniques, and one such method is analyzing next-generation sequencing data from both tumor and normal samples. We'll be following the footsteps of the genomics gurus at the Broad Institute, adhering to their "Best Practices" guidelines and harnessing the computational prowess of the Genome Analysis Toolkit (GATK) platform.

### Beyond the Code: Annotating Variants

Genomic exploration doesn't stop at reading the code; it extends to understanding its nuances. Our protocol doesn't just stop at variant identification; we annotate these genetic alterations with population allele frequencies and insights from curated resources like GnomAD and ClinVar. The tools in our arsenal for this task include VCFtools, SnpEff, and SnpSift, adding layers of context to our genomic findings.

### The Power of Whole Exome Sequencing

Why limit ourselves when we can sequence the entire exome? We'll delve into the cost-effective marvel that is Whole Exome Sequencing, focusing on the analysis of protein-coding regions. Unraveling the secrets of the exome provides a comprehensive view of the genetic landscape, guiding us through the intricate web of protein-coding elements.

### Mutect2: Your Somatic Sleuth

To unearth somatic variants, we enlist Mutect2, a somatic variant caller that acts as our genomic detective. We'll guide you through the setup, ensuring you have the required files and software to embark on your variant discovery quest. But wait, there's more! We'll also touch upon alternative workflows using VarScan Somatic, offering you a diverse set of tools to tackle the genomic enigma.

Join us on this bioinformatics odyssey, where every nucleotide tells a story, and every variant is a clue waiting to be uncovered. Get ready to decode the language of cancer genomes with precision and insight!
