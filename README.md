# open-chromatin
Assaying open chromatin to understand genetic and epigenetic mechanisms of lung disease

# ATAC-seq methods
- **Transposition of native chromatin for fast and sensitive epigenomic profiling of open chromatin, DNA-binding proteins and nucleosome position.** Buenrostro JD, Giresi PG, Zaba LC, Chang HY, Greenleaf WJ. *Nat. Methods.* 2013 Dec;10(12):1213-8. PMID: [24097267](https://www.ncbi.nlm.nih.gov/pubmed/24097267) PMCID: [PMC3959825](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3959825/) DOI: [10.1038/nmeth.2688](https://doi.org/10.1038/nmeth.2688)

- **ATAC-seq: A Method for Assaying Chromatin Accessibility Genome-Wide.** Buenrostro JD, Wu B, Chang HY, Greenleaf WJ. *Curr Protoc Mol Biol.* 2015 Jan 5;109:21.29.1-9. PMID: [25559105](https://www.ncbi.nlm.nih.gov/pubmed/25559105) PMCID: [PMC4374986](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4374986/) DOI: [10.1002/0471142727.mb2129s109](https://doi.org/10.1002/0471142727.mb2129s109)

- **Lineage-specific and single-cell chromatin accessibility charts human hematopoiesis and leukemia evolution.** Corces MR, Buenrostro JD, Wu B, Greenside PG, Chan SM, Koenig JL, Snyder MP, Pritchard JK, Kundaje A, Greenleaf WJ, Majeti R, Chang HY. Nat Genet. 2016 Oct;48(10):1193-203. PMID: [27526324](https://www.ncbi.nlm.nih.gov/pubmed/27526324) PMCID: [PMC5042844](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5042844/) DOI: [10.1038/ng.3646](https://doi.org/10.1038/ng.3646)

- **An improved ATAC-seq protocol reduces background and enables interrogation of frozen tissues.** Corces MR, Trevino AE, Hamilton EG, Greenside PG, Sinnott-Armstrong NA, Vesuna S, Satpathy AT, Rubin AJ, Montine KS, Wu B, Kathiria A, Cho SW, Mumbach MR, Carter AC, Kasowski M, Orloff LA, Risca VI, Kundaje A, Khavari PA, Montine TJ, Greenleaf WJ, Chang HY. *Nat Methods*. 2017 Oct;14(10):959-962. PMID: [28846090](https://www.ncbi.nlm.nih.gov/pubmed/28846090) PMCID: [PMC5623106](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5623106/) DOI: [10.1038/nmeth.4396](https://doi.org/10.1038/nmeth.4396)

- PMID: []() PMCID: []() DOI: []()

# Data standards
- [ATAC-seq Data Standards and Prototype Processing Pipeline](https://www.encodeproject.org/atac-seq/) The prototype ATAC-seq pipeline was developed by Anshul Kundaje's lab at Stanford University. Upon revision and full implementation, it will be a part of the [ENCODE Uniform Processing Pipelines series](https://www.encodeproject.org/pipelines/). The full ATAC-seq pipeline code is available on [Github](https://github.com/ENCODE-DCC/atac-seq-pipeline). Describes standards for pipeline and experiment design (such as library complexity, FRiP score and TSS enrichment score guidelines; see [defintions of terms](https://www.encodeproject.org/data-standards/terms).


# Software for analysis of ATAC-seq data
## Technical analysis and quality control
- [ATACseqQC](https://bioconductor.org/packages/release/bioc/html/ATACseqQC.html) - [R] Produces diagnostic plots of fragment size distribution, proportion of mitochondria reads, nucleosome positioning pattern, and CTCF or other Transcript Factor footprints; [examples](https://bioconductor.org/packages/release/bioc/vignettes/ATACseqQC/inst/doc/ATACseqQC.html).
- [esATAC](https://bioconductor.org/packages/release/bioc/html/esATAC.html) - [R] Provides a framework and complete preset pipeline for quantification and analysis of ATAC-seq reads; [examples](https://bioconductor.org/packages/release/bioc/vignettes/esATAC/inst/doc/esATAC-Introduction.html).
## For single-cell ATAC analysis
- [ChromVAR](https://bioconductor.org/packages/release/bioc/html/chromVAR.html) - [R] - Determine variations in chromatin accessibility across sets of annotations or peaks. Designed primarily for single-cell or sparse chromatin accessibility data, e.g. from scATAC-seq or sparse bulk ATAC or DNAse-seq experiments. [BioRxiv](https://www.biorxiv.org/content/early/2017/02/21/110346)
- [cicero](https://cole-trapnell-lab.github.io/cicero-release/) - [R] - Predicts enhancer-gene pairs by co-accessibility. Also adapts [monocle](http://cole-trapnell-lab.github.io/monocle-release/) for single-cell ATAC-seq (clustering, trajectories, differential accessibility).

# ATAC-seq papers
### 2019
- 

### 2018
- **Evaluation of chromatin accessibility in prefrontal cortex of individuals with schizophrenia.** Bryois J, Garrett ME, Song L, Safi A, Giusti-Rodriguez P, Johnson GD, Shieh AW, Buil A, Fullard JF, Roussos P, Sklar P, Akbarian S, Haroutunian V, Stockmeier CA, Wray GA, White KP, Liu C, Reddy TE, Ashley-Koch A, Sullivan PF, Crawford GE. *Nat Commun.* 2018; 9: 3121. PMID: 30087329 PMCID: PMC6081462 DOI: 10.1038/s41467-018-05379-y

### 2017
