# org.Osativa.eg.db
Annotation package relating NCBI gene identifiers of genes in the IRGSP-1.0 rice genome to GO terms. Initial source of GO terms is from AgriGOv2, the Uniprot 2016_06 release annotated with GO terms (file name 648_slimGO.txt)

### Installation

This package requires AnnotationHub, so ensure it is installed. Then install this package.

```r
if (!require(AnnotationHub)) {
  BiocManager::install("AnnotationHub")
}
remotes::install_github("louievdl/org.Osativa.eg.db")
```
