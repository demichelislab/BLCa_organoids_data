# Bladder cancer organoids as a functional system to model different disease stages and therapy response

Authors: 
*M. Minoli, T. Cantore, D. Hanhart, M. Kiener, T. Fedrizzi, F. La Manna, S. Karkampouna, P. Chouvardas, V. Genitisch, A. Rodriguez-Calero, E. Comperat, I. Klima, P. Gasperini, B. Kiss, R. Seiler-Blarer, F. Demichelis, G. N. Thalmann, M. Kruithof-de Julio*

## Study summary  
The study reports the genomic characterization at the single allele level upon Whole Exome Sequencing of Bladder Cancer Patient Tumor (PT) samples obtained from 18 patients and corresponding Patients Derived Organoids (PDOs), implementing the SPICE pipeline. The cohort includes 21 PTs and 22 PDOs.

## Data summary 
| File name  | Download | Description |
| ------------- | ------------- | ------------- |
| **`./data/samples_info_file.txt`**  | [TXT](https://github.com/demichelislab/BLCa_organoids_data/raw/main/data/samples_info_file.txt) | sample info file with per-sample ids along with genomics-derived metrics and statistics. |
| **`./data/samples_copy_number_segments.txt`** | [TXT](https://github.com/demichelislab/BLCa_organoids_data/raw/main/data/samples_copy_number_segments.txt) | complete list of copy-number segments per sample along with statistics obtained as output from the SPICE pipeline (1). |
| **`./data/samples_somatic_point_mutations.txt`** | [TXT](https://github.com/demichelislab/BLCa_organoids_data/blob/main/data/samples_somatic_point_mutations.txt) | complete list of somatic point mutations comprising annotation performed by VEP (2) |
|  **`./data/samples_per_gene_allele_specific_cn_and_point_mutations.txt`** | [TXT](https://github.com/demichelislab/BLCa_organoids_data/blob/main/data/samples_per_gene_allele_specific_cn_and_point_mutations.txt) | per-sample, per-gene summary of allele-specific copy-number mutations and point mutations |


## References 
1. Ciani Y et al, Allele-specific genomic data elucidates the role of somatic gain and copy number neutral loss of heterozygosity in cancer. Cell Syst. (2022) 
2. McLaren, W. et al. The Ensembl Variant Effect Predictor. Genome Biol 17, 122 (2016).
