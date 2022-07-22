# project-cell-type-annotation

See project webpage: [Link](https://speckerf.github.io/cell_type_annotation/index.html)

A [workflowr][] project by Felix Specker & Stine Anzböck available

[workflowr]: https://github.com/jdblischak/workflowr

## Project Description: Cell type annotation methods project

### Methods

3 recent cell type annotation methods for single cell RNA-seq data are being compared: [SingleR], [scClassify], [Seurat v3].

[Seurat v3]: https://satijalab.org/seurat/v3.2/integration.html
[SingleR]: http://bioconductor.org/packages/release/bioc/html/SingleR.html
[scClassify]: http://www.bioconductor.org/packages/release/bioc/html/scClassify.html

### Datasets
The methods will be run on two selected pre-labelled pancreas datasets - each once as a reference and once as a test dataset. 
The datasets were loaded from the [scRNAseq library].

**Baron** dataset: From [this paper](https://pubmed.ncbi.nlm.nih.gov/27667365/), droplet-based scRNA-seq

**Muraro** dataset: From [this paper](https://www.cell.com/cell-systems/fulltext/S2405-4712(16)30292-7?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2405471216302927%3Fshowall%3Dtrue), CEL-seq

[scRNAseq library]: https://bioconductor.org/packages/release/data/experiment/vignettes/scRNAseq/inst/doc/scRNAseq.html#available-data-sets

### Performance metrics: 

The performance of the methods will be evaluated with the following performance metrics:

* AdjRandIndex

* F1 score for each cell type


