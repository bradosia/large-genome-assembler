# large-genome-assembler

https://en.wikipedia.org/wiki/List_of_sequence_alignment_software#Short-read_sequence_alignment

GAGE is an evaluation of the very latest large-scale genome assembly algorithms.
De-novo vs. mapping assembly

| Sequencer | Reads | Error Rate |
| :-- | :-- | :-- |
| Illumina | short | low |
| PacBio/MinION | long | high |

| File Type | Description |
| :-- | :-- |
| fasta | sequences |
| fastq | sequences with quality |
| sam/bam | alignment |

## mapping assembly

| Algorithm | Output |
| :-- | :-- |
| Minimap2 | paf |
| bowtie2 | bt2 |

## De-novo assembly
https://academic.oup.com/bioinformatics/article/34/4/678/4553153

System:
* Intel Xeon 2.2 GHz processor using 32 cores and 1TB of RAM. 
* Assembly evaluation was performed using LASER (Khiste and Ilie, 2015).

Inputs:
* Caenorhabditis elegans and Drosophila melanogaster

| Algorithm | Assembly Time | Memory Used | Algorithm Class |
| :-- | :-- | :-- | :-- | 
| SOAPdenovo2 | <1 day |  more | de-bruijn-graph |
| SAGE2 | <2 days | more | overlap–layout–consensus |
| ABySS | >2 days | more | de-bruijn-graph |
| SGA | 5–19 days | <100GB | overlap–layout–consensus |

| Algorithm | Algorithm Class | Output File |
| MaSuRCA | deBruijn graph/Overlap-Layout-Consensus | fasta |


