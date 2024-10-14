# Unicycler

#### Read Assembly
- **Why Perform Assembly?**: Once reads are cleaned and filtered, genome assembly is performed to reconstruct the entire genome or transcriptome from the sequencing reads. This process is especially crucial for de novo assemblies, where a reference genome is not available.

- - **Tool (Hybrid Assembly)**: Unicycler (combining short and long reads)
  - **Installation**:
    ```bash
    conda install -c bioconda unicycler
    ```
  - **Usage**:
    ```bash
    unicycler -1 input_R1.fastq -2 input_R2.fastq -l long_reads.fastq -o output_directory
    ```
