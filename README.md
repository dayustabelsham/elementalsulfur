# elementalsulfur
This project outlines the code and raw sequence data used for the project titled "Consequences of elemental sulfur induced soil acidification on bacterial and fungal communities in southern Okanagan vineyard soil"

Elemental Sulphur (So) can be used as a fertilizer, acidifier or biocide in many
agricultural systems. So changes soil pH and results in the production of metabolites toxic to many microbes. Bacteria and fungi have differential
susceptibility to So which may lead to changes in soil microbial communities and functioning. Recent insights into the importance of microbes in soil and ecosystem health warrants a better characterization of soil microbial communities’ response
to So. This study will assess the sensitivity of fungi and bacteria to a So amended soil in a commercial vineyard in the southern Okanagan. Using bacterial and fungal
isolates collected on site, we will test their tolerance to both So and pH. In addition, we will measure changes to soil bacterial and fungal communities
following the addition of So. Finally, we will assess microbial decomposition and above ground plant diversity following So application for functional analysis.

# Sample information
Land Type: Agricultural (vineyards)
Geographic Region: Okanagan, Southern British Columbia, Canada
Soil Types (pooled): Loam and sandy-loam
Sampling Location: 49.2414504 N 119.5672703 W
Sample Type: Soil
Collection Date: October 15, 2024

# DNA Extraction and PCR
DNA Extraction: QIAGEN DNeasy PowerSoil Kit (0.25 g samples)
Targeted Region: SSU rRNA V3V4 and ITS2

PCR:
16S: AML1 (forward) & AML2 (reverse) - Lee et al., 2008
ITS: WANDA (forward) & AML2 (reverse) - Dumbrell et al., 2011

# PCR Conditions
The PCR reagent recipe and cycling conditions were performed according to a modified version of methods outlined in (Aleklett et al., 2022), and (Greg Caporaso et al., 2018; P. Smith et al., 2018)

Platform: Illumina NextSeq 2000 (2×300 bp)
Facility: UBC Sequencing and Bioinformatics Consortium

# Data Files
Imported paired-end Illumina NextSeq 2000 reads (gzip-compressed fastq format) can be found in the NCBI Sequence Read Archive at the following links:
ITS2: http://www.ncbi.nlm.nih.gov/bioproject/1453436
16S: http://www.ncbi.nlm.nih.gov/bioproject/1453704


METADATA.tsv:	Sample metadata including sample-id, row, plot, treatment, shannon, simpson, buffer, phosphorous, and pH.
Chemical.csv: Data containing available phosphorous (Bray 1) and CaCO3 equivalent (%)
GrowthData.csv: Data containing growth assay slope and max OD for each isolate
PlantDiv.csv: Data containing species counts per quadrat
WeightData.csv: Data containing weight measurements over time of green teabags collected from feild soil
pH.csv: Data containing pH measurements taken from feild soil over time, measuresd using a pH probe


# References 

Aleklett, K., Rosa, D., Pickles, B. J., & Hart, M. M. (2022). Community Assembly and Stability in the Root Microbiota During Early Plant Development. Frontiers in Microbiology, 13, 826521. https://doi.org/10.3389/fmicb.2022.826521

Greg Caporaso, J., Ackermann, G., Apprill, A., Bauer, M., Berg-Lyons, D., Betley, J., Fierer, N., Fraser, L., A. Fuhrman, J., A. Gilbert, J., Gormley, N., Humphrey, G., Huntley, J., K. Jansson, J., Knight, R., L. Lauber, C., A. Lozupone, C., McNally, S., M. Needham, D., ... Weber, L. (2018). EMP 16S Illumina Amplicon Protocol v1. https://doi.org/10.17504/protocols.io.nuudeww

P. Smith, D., G. Peay, K., Ackermann, G., Apprill, A., Bauer, M., Berg-Lyons, D., Betley, J., D.
Bruns, T., Greg Caporaso, J., Fierer, N., Fraser, L., A. Fuhrman, J., Gardes, M., A. Gilbert, J., Gormley, N., Humphrey, G., Huntley, J., K. Jansson, J., Knight, R., ... J. White, T. (2018). EMP ITS Illumina Amplicon Protocol v1. https://doi.org/10.17504/protocols.io.pa7dihn

