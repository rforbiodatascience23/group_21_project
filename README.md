# Group 21 project

# Project Contributors

buniaia (s215085), emmaqingjie (s215090), JoannaRasmussen (s215092), ThobiasAChristiansen (s215105), & utte123 (s223163),

# Exploration of TCR Repertoire Development during Childhood

Investigating how T-cell receptor (TCR) repertoires develop during childhood is a fascinating area of research that sheds light on the evolution of the immune system. In healthy children, this research uncovers how T-cells adapt over time. Understanding this progression aids in comprehending how the immune system learns to identify threats while preserving tolerance towards the body's cells.

When researching childhood diseases like type 1 diabetes (T1D), examining TCR repertoires reveals potential differences in T-cell diversity and function that might precede disease symptoms. This exploration seeks early markers for conditions like T1D, aiming for earlier diagnoses and potentially new ways to intervene before symptoms emerge.

Studies such as these manage deepen our understanding of how the immune system matures and offer hope for better diagnostic methods and treatments, especially in conditions affecting children like T1D. Unravelling the complexities of TCR repertoire development has the potential of paving the way for innovative approaches to delay or prevent the onset of such diseases in childhood.

Digging deeper into this area, Mitchell et al. (2022) investigate the 'Temporal Development of T Cell Receptor Repertoires during Childhood in Health and Disease.' Featured in the Journal of Clinical Investigation, their study explores the dynamics guiding TCR repertoire evolution and its impact on childhood health, specifically in conditions like Type 1 Diabetes (T1D).

# Reference

Angela M. Mitchell, Erin E. Baschal,1 Kristen A. McDaniel, Kimber M. Simmons, Laura Pyle, Kathleen Waugh, Andrea K. Steck, Liping Yu, Peter A. Gottlieb, Marian J. Rewers, Maki Nakayama, and Aaron W. Michels (2022). Temporal development of T cell receptor repertoires during childhood in health and disease. DOI: 10.1172/jci.insight.161885.

# Data

## Data Retrieval

Access to the data link is available in the Methods section, specifically within the 'Data and Materials Availability' subsection (NOTE: you may have to create an account for accessibility). To obtain the sample overview file, navigate to 'Open in Analyses', select the 'analysis' option, and proceed to click the 'export' button. Once downloaded, rename the file as 'raw.tsv' and upload it to the '\_raw' folder.

## Data description

This dataset comprises a detailed record of immunological and demographic attributes across 216 observations and 41 variables. It encompasses data from 54 patients undergoing testing across four distinct visits. The information includes demographic specifics such as gender, ethnicity, race, and age at both diagnosis and visit. Additionally, it covers immunological markers like antibody expression (GAD65, IA_2, IAA, ZnT8) and comprehensive HLA allele information (HLA_A, HLA_B, HLA_C, HLA_DPA1, HLA_DPB1, HLA_DQA1, HLA_DQB1, HLA_DRB1). This dataset conveys the interplay between demographic factors and immunological profiles across multiple patient visits, offering insights crucial for in-depth analysis and understanding.

## Project Structure Overview

This project, is spread across four main folders:

-   **data**: Holds project data files, including a **_raw** folder for raw data.

-   **R**: Contains R scripts for data processing, analysis, and a master script (00_all.qmd).

-   **results**: Contains rendered HTML documents and key plots.

-   **doc**: Stores project documentation and the presentation in source and rendered HTML formats.

This layout separates data, scripts, results, and documentation, aiding in easy navigation and understanding.

# Goal

This project aims to analyze the data provided by Mitchell et al. (2022) in a further attempt to uncover potential relations between allele repertoire development during childhood and the susceptibility to obtaining type 1 diabetes (T1D).

The project proceeds to clean, augment, and analyze the data with the intention of reducing the dimensionality of the dataset through Principal Component Analysis (PCA), and identifying and proposing conditions connected to outcome for patients.

The results are naturally a product of our own logical interpretations of the experiment and data.

For usage, run the 00_all.qmd file. This file contains all the individual analyses run, and will output the results.

[Link to Project Presentation](https://raw.githack.com/rforbiodatascience23/group_21_project/main/doc/presentation.html)
