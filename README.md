# nMyo

We have developed the **nMyo** R shiny applet and associated R package to visualise the single-cell RNAseq expression profiles of 2031 high-quality mouse cardiac non-myocytes. The detailed vignette can be found at https://github.com/ArisStefanosSn/nMyo/blob/master/vignette.pdf. 

The repository can be cloned as:

```bash
$ git clone https://github.com/ArisStefanosSn/nMyo
```

The package can be installed in R as:

```r
R> install.packages("nMyo_1.0.0.tar.gz")
```

**nMyo**'s functions are described in detail in the vignette. The R shiny applet allows the non-computational scientist to use the most important functions of **nMyo** and explore our rich dataset. The applet is accessed by:

```r
R> library(nMyo)
R> run_nMyo()
```
