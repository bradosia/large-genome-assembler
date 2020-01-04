# large-genome-assembler

GAGE is an evaluation of the very latest large-scale genome assembly algorithms.

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

