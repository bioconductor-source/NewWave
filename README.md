# NewWave

A scalable R package for dimensionality reduction and batch effect removal of single-cell RNA-seq data.

## How to install 

Clone this repository on your machine and than install it

```
install.packages("path/to/NewWave", repos = NULL, type="source")
```

## How to use

If you have your data stored in a SummarizedExperiment object with a batch effect variable called "batch" stored in colData then:

```
newWave(data,X = "~batch")
```

A more deteiled case of use is shown in the vignette.