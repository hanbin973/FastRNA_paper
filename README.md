# FastRNA reproducible repository
Lee and Han (2022) currently under review at American Journal of Human Genetics

# Contents

## Code description
The codes for running `R` code are in the `fastrna_r` folder.
The codes for running `python` code are in the `fastrna_py` folder.
Data can be downloaded following the instruction in the manuscript's `Materials and Methods`.

`Figure 1` can be produced using `*-mouse-organogenesis.ipynb`.
`Figure 2` can be produced using `*-zhengmix8eq.ipynb`.
`Figure 3` can be produced using `*-pbmcssc.ipynb`.
`Figure 4` can be produced using `*-mouse-organogenesis.ipynb` and `*-splatter-*.ipynb`.


## Data availability
For all datasets, the matrix files were converted to numpy sparse file format `.npz`.
It was because the `.npz` format was the fastest to load into memory especially for the mouse embryo organogenesis dataset which was large in size.


[Mouse embryo organogenesis data](https://oncoscape.v3.sttrcancer.org/atlas.gs.washington.edu.mouse.rna/landing)

[Zhengmix8eq](https://bioconductor.org/packages/release/data/experiment/html/DuoClustering2018.html)

[PBMC SSC](https://singlecell.broadinstitute.org/single_cell/study/SCP424/single-cell-comparison-pbmc-data)







