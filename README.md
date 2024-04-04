# Variant-Calling-Workflow

This repository provides a comprehensive workflow for variant calling analysis using bioinformatics tools. It encompasses both single sample and multiple samples' variant calling processes.

## Usage Instructions

### Environment Setup

Run the provided setup script `setup.sh` to install the necessary tools using Conda.

```bash
bash setup.sh
```
## Work flow 

1- Install tools (fastqc, multiqc, samtools, BWA, Freebays, bcftools, tabix). 

2- Download the exapmle data (parird-end FASTQ Reads).

3- Download the reference Genome.

4- Assess Quality of Reads.

5- Read Mapping.

6- Filter Alignment Records.

7- Mark Duplicates.

8- Variant calling.

9- Basic statistic.

10- Filter the Variants.

## Tools Used

The following bioinformatics tools are used in this workflow:

- FastQC
- Trimmomatic
- BWA
- SAMtools
- BCFtools
- VCFtools
- MultiQC

## Note

- Make sure to update file paths according to your directory structure.
- Customize the workflow based on your specific requirements.
