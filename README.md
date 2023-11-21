# Group 21 project

# Exploration of TCR Repertoire Development during Childhood

Investigating how T-cell receptor (TCR) repertoires develop during childhood is a fascinating area shedding light on the immune system's evolution. In healthy children, this research uncovers how T-cells grow, change, and adapt over time. Understanding this progression aids in comprehending how the immune system learns to identify threats while also preserving tolerance towards the body's own cells.

When looking at childhood diseases like type 1 diabetes (T1D), examining TCR repertoires reveals potential differences in T-cell diversity and function that might precede disease symptoms. This exploration seeks early markers for conditions like T1D, aiming for earlier diagnoses and potentially new ways to intervene before symptoms emerge.

These studies not only deepen our understanding of how the immune system matures but also offer hope for better diagnostic methods and treatments, especially in conditions affecting children like T1D. Unraveling the complexities of TCR repertoire development could pave the way for innovative approaches to delay or prevent the onset of such diseases in childhood.

Digging deeper into this area, Mitchell et al. (2022) investigate the 'Temporal Development of T Cell Receptor Repertoires during Childhood in Health and Disease.' Featured in the Journal of Clinical Investigation, their study explores the dynamics guiding TCR repertoire evolution and its impact on childhood health, specifically in conditions like Type 1 Diabetes (T1D).

# Reference

Angela M. Mitchell, Erin E. Baschal,1 Kristen A. McDaniel, Kimber M. Simmons, Laura Pyle, Kathleen Waugh, Andrea K. Steck, Liping Yu, Peter A. Gottlieb, Marian J. Rewers, Maki Nakayama, and Aaron W. Michels (2022). Temporal development of T cell receptor repertoires during childhood in health and disease. DOI: 10.1172/jci.insight.161885.

# Data

### Data Retrieval

The data link is accessible within the 'data and materials availability' section (NOTE: you may have to create an account for accessibility). To obtain the sample overview file, navigate to 'Open in Analyses', select the 'analysis' option, and proceed to click the 'export' button. Once downloaded, rename the file as 'raw.tsv' and proceed to upload it into the '\_raw' folder.

### Data description

This dataset comprises a detailed record of immunological and demographic attributes across 216 observations and 41 variables. It encompasses data from 54 patients undergoing testing across four distinct visits. The information includes demographic specifics such as gender, ethnicity, race, and age at both diagnosis and visit. Additionally, it covers immunological markers like antibody expression (GAD65, IA_2, IAA, ZnT8) and comprehensive HLA allele information (HLA_A, HLA_B, HLA_C, HLA_DPA1, HLA_DPB1, HLA_DQA1, HLA_DQB1, HLA_DRB1). This dataset serves to elucidate the interplay between demographic factors and immunological profiles across multiple patient visits, offering insights crucial for in-depth analysis and understanding.

# Goal

This project aims to analyse the data provided by Mitchell et al. (2022) in a further attempt to uncover potential relations between allele repertoire development during childhood and the susceptibility to obtaining type 1 diabetes (T1D).

The project proceeds to clean, augment, and analyze the data with the intention of reducing the dimensionality of the dataset through PCA, and then identifying and proposing conditions connected to outcome for patients.

The results are naturally a product of our own logical interpretations of the experiment and data.

# Usage

For usage, run the 00_all.qmd file. This contains all the individual analyses run, and will output the expected result.
