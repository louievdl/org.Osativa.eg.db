# org.Osativa.eg.db

Annotation package relating NCBI gene identifiers of genes in the IRGSP-1.0 rice genome to GO terms.


## Data Sources

This package used rice gene annotations and Gene Ontology associations from agriGO v2.0, in particular the Uniprot 2016_06 release annotated with GO terms (file name 648_slimGO.txt).

agriGO v2.0:
https://systemsbiology.cau.edu.cn/agriGOv2/

## Citation

If you use this package, please cite the following resources:

### agriGO v2.0

Tian T, Liu Y, Yan H, You Q, Yi X, Du Z, Xu W, Su Z.
*agriGO v2.0: a GO analysis toolkit for the agricultural community, 2017 update*.
Nucleic Acids Research (2017).
doi:10.1093/nar/gkx382

### Gene Ontology

The Gene Ontology Consortium.
*The Gene Ontology resource: enriching a GOld mine*.
Nucleic Acids Research (2021).
doi:10.1093/nar/gkaa1113



## Installation

This package requires AnnotationHub, so ensure it is installed. Then install this package.

```r
if (!require(AnnotationHub)) {
  BiocManager::install("AnnotationHub")
}
remotes::install_github("louievdl/org.Osativa.eg.db")
```
