# Genomic_Nextflow
Simple variant calling pipeline with GATK (Genome Analysis Toolkit)
Source: [nf](https://training.nextflow.io/latest/nf4_science/genomics/)

## Learning Objectives
1. Write a linear workflow to apply variant calling to a single sample
2. Handle accessory files such as index files and reference genome resources appropriately
3. Leverage Nextflow's dataflow paradigm to parallelize per-sample variant calling
4. Implement multi-sample variant calling using relevant channel operators
5. Configure pipeline execution and manage and optimize resource allocations
6. Implement per-step and end-to-end pipeline tests that handle genomics-specific idiosyncrasies appropriately

## Define Matter
**Variant calling** is a genomic analysis method that aims to identify variations in a genome sequence relative to a reference genome. 

## Workflow Pipeline

![image](https://github.com/user-attachments/assets/c1d10593-a287-4611-9a25-c1419692a097)

