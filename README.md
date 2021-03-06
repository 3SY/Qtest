# QUBIC

QUBIC is a Qualitative BiCluster Algorithms for Expression Data Analysis

# Description

This package provides a biclustering program for microarray data. For a set of genes and a set of conditions, the program outputs a block-like structure which shows uniform pattern within the block, the block would contain only subsets of all given genes under subsets of all given conditions. 

## Installation

You can install `QUBIC` from `github` using the `devtools` package

```coffee
require(devtools)
install_github('yu-shang/QUBIC')
```

+ Package: QUBIC
+ Version: 1.0
+ Date: 2015-02-01
+ Author: Qin Ma, Yu Shang, Ying Xu
+ Maintainer: Yu Shang <yushang@uga.edu>, Qin Ma <maqin@uga.edu>, Ying Xu <xyn@bmb.uga.edu>
+ Depends: R (>= 3.0.3), Rcpp (>= 0.11.3)
+ Type: Package
+ License: GPL (>= 2)
+ LinkingTo: Rcpp
+ LazyLoad: yes
+ LazyData: true
