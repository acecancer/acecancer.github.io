## Somatic Variant Detection In Cancer Samples Using Whole Exome Sequencing Data

### 1.1 Overview

In this section, we cover a detailed protocol for analyzing next-generation sequencing data from tumor and matching normal samples to identify somatic single nucleotide polymorphisms (SNPs) and small insertions/deletions (Indels). The protocol is based on the Broad Institute's "Best Practices" guidelines and utilizes their Genome Analysis Toolkit (GATK) platform. Variants are annotated with population allele frequencies and information from curated resources like GnomAD and ClinVar using VCFtools, SnpEff, and SnpSift. This document highlights the importance of whole exome sequencing (WES) for cost-effective analysis of protein-coding regions. The Mutect2 somatic variant caller is employed, with instructions provided for setting up the required files and software. Alternative workflows using VarScan Somatic are also discussed briefly.
