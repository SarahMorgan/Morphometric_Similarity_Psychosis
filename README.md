# Morphometric_Similarity_Psychosis

This repository contains code to analyse morphometric similarity matrices from patients with schizophrenia and healthy control subjects, as reported by [Morgan et al, 2018](https://www.biorxiv.org/content/10.1101/501494v2). Please cite that paper if you find this code helpful in your own analyses. The PLS code to relate gene expression to the neuroimaging signal was written by Dr Petra Vértes and introduced in [Whitaker and Vértes et al, PNAS 2016](http://www.pnas.org/content/113/32/9105) and [Vértes et al, Philosophical Transactions of the Royal Society B](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2015.0362), please cite those papers if you this approach in your own work.

The Yeo network mapping ('Yeo_500_overlap.txt') was performed by [Jakob Seidlitz](https://github.com/jms290) as part of the paper [Váša et al, Cereb Cortex. 2018](https://doi.org/10.1093/cercor/bhx249). The von Economo class mapping ('vonEcon_500_overlap.txt ') was performed by [Konrad Wagstyl](https://github.com/kwagstyl) and [Dr Kirstie Whitaker](https://github.com/kirstiejane) as part of the paper [Whitaker and Vértes, PNAS 2016](https://doi.org/10.1073/pnas.1601745113). Please cite those papers if you use either 'Yeo_500_overlap.txt' or 'vonEcon_500_overlap.txt'.

The code is written in [MATLAB](https://uk.mathworks.com/products/matlab.html). Data to go with the code can be downloaded [here](https://doi.org/10.6084/m9.figshare.7908488.v1). The code is split into three main files- 'MS_analyses.md' contains the code needed to construct the morphometric similarity matrices and analyse the global and regional differences in MS between control subjects and patients, 'Gene_analyses.md' contains the code needed for the gene analyses (building on inputs from 'MS_analyses.md') and 'magma_enrichments.md' contains the code to calculate gene enrichments using the software [Magma](https://ctg.cncr.nl/software/magma).
